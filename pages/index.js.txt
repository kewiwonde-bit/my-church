export default function Home() {
  return (
    <div style={{ textAlign: "center", marginTop: "50px" }}>
      <h1>Welcome to My Church</h1>
      <p>This is our new website built with Next.js 🚀</p>

      <div style={{ marginTop: "30px" }}>
        <h2>Donation</h2>
        <form>
          <input type="text" placeholder="Your Name" required /><br /><br />
          <input type="email" placeholder="Your Email" required /><br /><br />
          <input type="number" placeholder="Donation Amount" required /><br /><br />
          <button type="submit">Donate Now</button>
        </form>
      </div>
    </div>
  );
}

