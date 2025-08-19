<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Just4Thrillz</title>
  <link rel="stylesheet" href="styles.css" />
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #0f0f0f;
      color: #fff;
    }
    header {
      background: #ff4c4c;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('banner.jpg') center/cover no-repeat;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      background: rgba(0,0,0,0.6);
      padding: 1rem;
      border-radius: 10px;
    }
    section {
      padding: 2rem;
    }
    .cta-button {
      background: #ff4c4c;
      color: #fff;
      padding: 1rem 2rem;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    footer {
      background: #222;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h2>Just4Thrillz</h2>
    <nav>
      <a href="#about">About</a>
      <a href="#events">Events</a>
      <a href="#merch">Merch</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Live Bold. Connect Deep. Just4Thrillz.</h1>
  </div>

  <section id="about">
    <h2>About Us</h2>
    <p>We curate unforgettable experiences blending wellness, entertainment, and travel. Our merch is iconic, our events magnetic, and our community unstoppable.</p>
  </section>

  <section id="events">
    <h2>Upcoming Events</h2>
    <p>From rooftop yoga to international retreats, we’ve got your next thrill lined up.</p>
    <button class="cta-button">Book Now</button>
  </section>

<section id="booking">
  <h2>Book Your Spot</h2>
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="text" name="name" placeholder="Your Name" required />
    <input type="email" name="email" placeholder="Email" required />
    <select name="event">
      <option value="retreat">Retreat</option>
      <option value="popup">Pop-Up</option>
    </select>
    <button type="submit" class="cta-button">Submit</button>
  </form>
</section>

<section id="booking">
  <h2>Book Your Spot</h2>
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="text" name="name" placeholder="Your Name" required />
    <input type="email" name="email" placeholder="Email" required />
    <select name="event">
      <option value="retreat">Retreat</option>
      <option value="popup">Pop-Up</option>
    </select>
    <button type="submit" class="cta-button">Submit</button>
  </form>
</section>

  <section id="merch">
    <h2>Shop the Drop</h2>
    <p>Streetwear that speaks your truth. Bold, wearable, unforgettable.</p>
    <button class="cta-button">Shop Merch</button>
  </section>

  <section id="contact">
    <h2>Stay Connected</h2>
    <p>Follow us on Instagram, TikTok, and Twitter @Just4Thrillz</p>
    <p>Email: hello@just4thrillz.com</p>
  </section>

  <footer>
    &copy; 2025 Just4Thrillz. All rights reserved.
  </footer>
</body>
</html>

