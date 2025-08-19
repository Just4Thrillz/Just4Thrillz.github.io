<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Just4Thrillz</title>
  <style>
    /* Reset and base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
    }
    a {
      color: #007bff;
      text-decoration: none;
    }
    img {
      max-width: 100%;
      height: auto;
      display: block;
    }

    /* Layout */
    header, footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
    }
    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 1rem;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 1rem;
    }
    nav a {
      color: #fff;
      font-weight: bold;
      padding: .5rem 1rem;
      transition: background .3s;
    }
    nav a:hover {
      background: #444;
    }

    /* Hero */
    .hero {
      text-align: center;
      padding: 2rem 1rem;
      background: url('https://i.imgur.com/4zQJZ4T.jpg') center/cover no-repeat;
      color: #fff;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: .5rem;
    }
    .hero p {
      font-size: 1.1rem;
    }

    /* Sections */
    section {
      margin: 2rem 0;
    }
    .services ul {
      list-style: disc inside;
      column-count: 2;
      gap: 1rem;
    }

    /* Contact & Payment */
    .contact-info p, .payment a {
      margin: .5rem 0;
    }
    .payment a {
      display: inline-block;
      background: #5469d4;
      color: #fff;
      padding: .75rem 1.5rem;
      border-radius: 4px;
      transition: background .3s;
    }
    .payment a:hover {
      background: #4353b3;
    }

    /* Footer */
    footer p {
      font-size: .9rem;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .services ul {
        column-count: 1;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="/attachments/xh4xYbBsDP1Z27v5rJUv6.jpeg" alt="Just4Thrillz Logo" style="max-width:180px;">
    <nav class="container">
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#payment">Book Now</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="container">
      <h1>Welcome to Just4Thrillz</h1>
      <p>Where healthy living, fun events, and empowering retreats meet.</p>
    </div>
  </section>

  <main class="container">

    <section id="about">
      <h2>About Us</h2>
      <p>
        Just4Thrillz is Baltimore’s premier lifestyle brand dedicated to blending entertainment with wellness.
        From relationship coaching and culinary travel talks to adrenaline-pumping trips and restorative retreats,
        we curate experiences that inspire self-growth and strengthen our community.
      </p>
    </section>

    <section id="services" class="services">
      <h2>Our Services</h2>
      <ul>
        <li>Healthy Living Workshops</li>
        <li>Relationship Activities & Coaching</li>
        <li>Culinary & Travel Destination Talks</li>
        <li>Fun Events & Adventure Trips</li>
        <li>Self-Improvement Retreats</li>
        <li>Community Encouragement Sessions</li>
      </ul>
    </section>

    <section id="contact" class="contact-info">
      <h2>Contact Us</h2>
      <p>Phone: (443) 814-4430</p>
      <p>Phone: (410) 245-6537</p>
      <p>Email: <a href="mailto:just4thrillzat@gmail.com">just4thrillzat@gmail.com</a></p>
      <p>Home Base: Baltimore, Maryland</p>
    </section>

    <section id="payment" class="payment">
      <h2>Reserve Your Spot</h2>
      <a href="https://buy.stripe.com/bJecN7a9c48Z6xLdUa5os00" target="_blank" rel="noopener">
        Pay with Stripe
      </a>
    </section>

  </main>

  <footer>
    <p>&copy; 2025 Just4Thrillz. All Rights Reserved.</p>
  </footer>

</body>
</html>
