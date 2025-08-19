# Just4Thrillz.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Just4Thrillz</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      background-color: #111;
      text-align: center;
      padding: 20px;
    }
    header img {
      max-width: 220px;
    }
    nav {
      background-color: #222;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #ff0000;
    }
    .hero {
      background: linear-gradient(to right, #0000ff, #ff0000);
      text-align: center;
      padding: 60px 20px;
    }
    .hero h1 {
      font-size: 3em;
      color: #ffff00;
    }
    .section {
      padding: 50px 20px;
      max-width: 900px;
      margin: auto;
    }
    .section h2 {
      color: #ff0000;
      font-size: 2em;
      margin-bottom: 20px;
    }
    .form-group {
      margin-bottom: 15px;
    }
    input, textarea, select {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 5px;
      margin-top: 5px;
    }
    button {
      background-color: #0000ff;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }
    button:hover {
      background-color: #ff0000;
    }
    .social-links a {
      margin: 0 10px;
      color: #ffff00;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      background-color: #111;
      text-align: center;
      padding: 30px 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.jpeg" alt="Just4Thrillz Logo" />
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#booking">Book</a>
    <a href="#merch">Merch</a>
    <a href="#reviews">Reviews</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h1>Welcome to Just4Thrillz</h1>
    <p>Entertainment. Wellness. Travel. Connection. We create unforgettable experiences that spark joy and build community.</p>
  </section>

  <section class="section" id="about">
    <h2>About Us</h2>
    <p>Just4Thrillz is based in Baltimore, Maryland. We specialize in entertainment events for healthy living, relationship coaching, talk dining, travel adventures, retreats, and community empowerment. Founded by Lorraine, our mission is to help people live boldly and connect deeply.</p>
  </section>

  <section class="section" id="booking">
    <h2>Book an Experience</h2>
    <form>
      <div class="form-group">
        <label for="name">Full Name</label>
        <input type="text" id="name" required />
      </div>
      <div class="form-group">
        <label for="email">Email Address</label>
        <input type="email" id="email" required />
      </div>
      <div class="form-group">
        <label for="service">Select Service</label>
        <select id="service">
          <option>Wellness Retreat</option>
          <option>Relationship Coaching</option>
          <option>Talk Dining</option>
          <option>Travel Experience</option>
          <option>Merch Order</option>
        </select>
      </div>
      <div class="form-group">
        <label for="message">Additional Notes</label>
        <textarea id="message" rows="4"></textarea>
      </div>
      <button type="submit">Submit Booking</button>
    </form>
  </section>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Just4Thrillz Merch</title>
  <style>
    body {
      font-family: 'Helvetica Neue', sans-serif;
      background: #fff;
      margin: 0;
      padding: 0;
      color: #111;
    }
    header {
      background: #000;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 48px;
      margin: 0;
    }
    .merch-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 40px;
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .item {
      background: #f5f5f5;
      border-radius: 12px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .item img {
      max-width: 100%;
      border-radius: 8px;
      margin-bottom: 20px;
    }
    .item h2 {
      font-size: 24px;
      margin-bottom: 10px;
    }
    .item p {
      font-size: 16px;
      color: #555;
      margin-bottom: 20px;
    }
    .item button {
      background: #000;
      color: #fff;
      padding: 12px 24px;
      font-size: 16px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .item button:hover {
      background: #444;
    }
  </style>
</head>
<body>

<header>
  <h1>🔥 Just4Thrillz Merch</h1>
  <p style="font-size:18px; margin-top:10px;">Wear the vibe. Live the thrill.</p>
</header>

<section class="merch-grid">
  <!-- Hoodie -->
  <div class="item">
    <img src="https://yourdomain.com/images/chrome-hoodie.jpg" alt="Chrome Hoodie">
    <h2>Chrome Hoodie</h2>
    <p>Bold, reflective, and built for movement. Limited drop.</p>
    <a href="https://buy.stripe.com/bJecN7a9c48Z6xLdUa5os00" target="_blank">
      <button>Buy Now – $65</button>
    </a>
  </div>

  <!-- Graphic Tee -->
  <div class="item">
    <img src="https://yourdomain.com/images/graphic-tee.jpg" alt="Graphic Tee">
    <h2>Vibe Graphic Tee</h2>
    <p>Streetwear meets soul. Soft cotton, loud message.</p>
    <a href="https://buy.stripe.com/test-link-graphic-tee" target="_blank">
      <button>Buy Now – $30</button>
    </a>
  </div>

  <!-- Bucket Hat -->
  <div class="item">
    <img src="https://yourdomain.com/images/bucket-hat.jpg" alt="Bucket Hat">
    <h2>Thrillz Bucket Hat</h2>
    <p>Shade with swagger. Embroidered logo. Festival-ready.</p>
    <a href="https://buy.stripe.com/test-link-bucket-hat" target="_blank">
      <button>Buy Now – $25</button>
    </a>
  </div>
</section>

</body>
</html>

<section id="merch">
  <h2>Buy Just4Thrillz Chrome Hoodie</h2>
  <p>Secure your exclusive hoodie now. Limited quantities available.</p>
  <a href="https://buy.stripe.com/bJecN7a9c48Z6xLdUa5os00" target="_blank">
    <button style="background-color:#0000ff; color:#fff; padding:12px 24px; border:none; border-radius:5px; font-size:16px; font-weight:bold;">
      Buy Now – $65
    </button>
  </a>
</section>

<form action="/create-checkout-session" method="POST">
  <button type="submit">Buy Chrome Hoodie – $65</button>
</form>

// server.js
const express = require('express');
const stripe = require('stripe')('sk_test_your_secret_key');
const app = express();
app.use(express.static('public'));
app.use(express.json());

app.post('/create-checkout-session', async (req, res) => {
  const session = await stripe.checkout.sessions.create({
    line_items: [{
      price_data: {
        currency: 'usd',
        product_data: {
          name: 'Just4Thrillz Chrome Hoodie',
        },
        unit_amount: 4500, // $65.00
      },
      quantity: 1,
    }],
    mode: 'payment',
    success_url: 'https://yourdomain.com/success',
    cancel_url: 'https://yourdomain.com/cancel',
  });

  res.redirect(303, session.url);
});

app.listen(4242, () => console.log('Running on port 4242'));




<!-- success.html -->
<h1>Thanks for your purchase!</h1>
<p>Your Chrome Hoodie is on the way. Stay Thrillz’d.</p>

<!-- cancel.html -->
<h1>Payment canceled</h1>
<pNo worries — you can try again anytime.</p>

<header style="background:#000; color:#fff; padding:80px 20px; text-align:center;">
  <h1 style="font-size:60px; margin-bottom:10px;">JUST4THRILLZ MERCH</h1>
  <p style="font-size:20px; max-width:600px; margin:auto;">Wear the energy. Rep the movement. Every piece tells a story.</p>
  <a href="#shop" style="display:inline-block; margin-top:30px;">
    <button style="background:#fff; color:#000; padding:14px 28px; font-size:18px; border:none; border-radius:8px; cursor:pointer;">
      Shop the Drop
    </button>
  </a>
</header>


  <section class="section" id="merch">
    <h2>Merch & Payments</h2>
    <p>To purchase merch or pay for services, please complete the form below. A team member will follow up with payment options.</p>
    <form>
      <div class="form-group">
        <label for="product">Product or Service</label>
        <input type="text" id="product" required />
      </div>
      <div class="form-group">
        <label for="amount">Amount (USD)</label>
        <input type="number" id="amount" required />
      </div>
      <div class="form-group">
        <label for="payment">Preferred Payment Method</label>
        <select id="payment">
          <option>CashApp</option>
          <option>PayPal</option>
          <option>Venmo</option>
          <option>Zelle</option>
        </select>
      </div>
      <button type="submit">Submit Payment Request</button>
    </form>
  </section>

  <section class="section" id="reviews">
    <h2>Leave a Review</h2>
    <form>
      <div class="form-group">
        <label for="reviewer">Your Name</label>
        <input type="text" id="reviewer" required />
      </div>
      <div class="form-group">
        <label for="review">Your Review</label>
        <textarea id="review" rows="4" required></textarea>
      </div>
      <button type="submit">Submit Review</button>
    </form>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Email: just4thrillzat@gmail.com<br />
       Phone: (410) 245-6537<br />
       Location: Baltimore, Maryland</p>
    <div class="social-links">
      <a href="https://facebook.com/Just4Thrillz" target="_blank">Facebook</a>
      <a href="https://instagram.com/Just4Thrillz" target="_blank">Instagram</a>
      <a href="https://youtube.com/@Just4Thrillz" target="_blank">YouTube</a>
      <a href="https://tiktok.com/@Just4Thrillz" target="_blank">TikTok</a>
    </div>
    <p><strong>Buy Tickets:</strong> <a href="https://eventbrite.com/o/just4thrillz-00000000000" target="_blank">Visit Eventbrite</a></p>
  </section>

  <footer>
    &copy; 2025 Just4Thrillz. All rights reserved.
  </footer>

</body>
</html>
