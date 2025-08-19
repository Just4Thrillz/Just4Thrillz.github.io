# Just4Thrillz.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Just4Thrillz - Entertainment, Learning & Activities</title>
  <meta name="description" content="Just4Thrillz brings Baltimore and beyond unforgettable experiences: entertainment, learning, and activities both online and offline.">
  <meta name="keywords" content="Just4Thrillz, Baltimore events, comedy, workshops, learning, activities, membership, entertainment">
  <meta property="og:title" content="Just4Thrillz - Entertainment, Learning & Activities">
  <meta property="og:description" content="Join Baltimore’s hub for fun, creativity, and unforgettable experiences—online and in person.">
  <meta property="og:image" content="logo.png">
  <meta property="og:url" content="http://just4thrillz.com">
  <meta name="twitter:card" content="summary_large_image">

  <style>
    body { margin:0; font-family:Arial, sans-serif; background:#f9f9f9; color:#222; }
    header { background:#ff0000; color:white; padding:1rem; text-align:center; position:sticky; top:0; display:flex; align-items:center; justify-content:space-between; }
    header img { height:50px; }
    header h1 { margin:0; font-size:2rem; display:inline; }
    nav a { margin:0 10px; color:white; text-decoration:none; font-weight:bold; }
    .hero { background:linear-gradient(135deg, #ff0000, #ffd700, #0000ff); color:white; text-align:center; padding:4rem 2rem; }
    .hero h2 { font-size:2.5rem; margin-bottom:1rem; }
    .hero p { font-size:1.2rem; margin-bottom:1.5rem; }
    .hero button { background:white; color:#ff0000; border:none; padding:0.8rem 1.5rem; font-size:1rem; border-radius:8px; cursor:pointer; }
    section { padding:3rem 2rem; max-width:1000px; margin:auto; }
    .features { display:grid; grid-template-columns:repeat(auto-fit, minmax(250px, 1fr)); gap:1rem; }
    .card { background:white; padding:1.5rem; border-radius:12px; box-shadow:0 2px 6px rgba(0,0,0,0.1); }
    .card h3 { color:#ff0000; }
    .events { display:grid; grid-template-columns:1fr 1fr; gap:1rem; }
    .event { background:white; padding:1rem; border-radius:8px; box-shadow:0 2px 4px rgba(0,0,0,0.1); }
    .event button { background:#0000ff; color:white; border:none; padding:0.6rem 1rem; border-radius:6px; cursor:pointer; }
    .pricing { display:grid; grid-template-columns:repeat(auto-fit, minmax(250px, 1fr)); gap:1rem; }
    .plan { background:white; padding:1.5rem; border-radius:12px; box-shadow:0 2px 6px rgba(0,0,0,0.1); text-align:center; }
    .plan h3 { color:#0000ff; }
    .plan button { background:#ff0000; color:white; border:none; padding:0.6rem 1rem; border-radius:6px; cursor:pointer; }
    footer { background:#222; color:white; text-align:center; padding:2rem; margin-top:2rem; }
    input, textarea { width:100%; padding:0.8rem; margin:0.5rem 0; border:1px solid #ccc; border-radius:6px; }
    button.submit { background:#ff0000; color:white; border:none; padding:0.8rem 1.5rem; font-size:1rem; border-radius:6px; cursor:pointer; }
    .newsletter { margin-top:2rem; text-align:center; }
    .newsletter input[type="text"], .newsletter input[type="email"] { max-width:400px; display:block; margin:0.5rem auto; }
    .newsletter button { background:#0000ff; color:white; border:none; padding:0.8rem 1.5rem; border-radius:6px; cursor:pointer; }
  </style>

  <script>
    function subscribeToMailchimp(event) {
      event.preventDefault();
      const name = document.getElementById('subscriberName').value;
      const email = document.getElementById('subscriberEmail').value;
      
      // Replace with your Mailchimp form POST URL
      const mailchimpUrl = "https://YOUR_MAILCHIMP_DC.api.mailchimp.com/subscribe/post-json?u=YOUR_U_ID&id=YOUR_LIST_ID&c=?";
      
      fetch(mailchimpUrl, {
        method: 'POST',
        body: JSON.stringify({ EMAIL: email, FNAME: name }),
        headers: { 'Content-Type': 'application/json' }
      })
      .then(() => alert('Thank you for subscribing!'))
      .catch(() => alert('Subscription failed. Please try again.'));
    }
  </script>

  <!-- Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'G-XXXXXXXXXX'); // Replace with your Measurement ID
  </script>
</head>
<body>
  <header>
    <img src="logo.png" alt="Just4Thrillz Logo">
    <nav>
      <a href="#features">Features</a>
      <a href="#events">Events</a>
      <a href="#pricing">Membership</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Entertainment • Learning • Activities</h2>
    <p>Join Baltimore’s hub for fun, creativity, and unforgettable experiences—online and in person.</p>
    <button onclick="document.getElementById('newsletter').scrollIntoView({behavior:'smooth'})">Join Now</button>
  </section>

  <section id="features">
    <h2>What We Offer</h2>
    <div class="features">
      <div class="card"><h3>Entertainment</h3><p>Comedy nights, live music, themed parties—fun at every turn.</p></div>
      <div class="card"><h3>Learning</h3><p>Workshops, DIY classes, cultural sessions to expand your mind.</p></div>
      <div class="card"><h3>Activities</h3><p>Fitness events, team-building games, creative group activities.</p></div>
    </div>
  </section>

  <section id="events">
    <h2>Upcoming Events in Baltimore</h2>
    <div class="events">
      <div class="event">
        <h3>Open Mic Comedy Night</h3>
        <p>September 12, 2025 | The Downtown Spot, Baltimore</p>
        <button onclick="window.location.href='https://eventbrite.com/e/open-mic-comedy-night-baltimore'">Get Tickets</button>
      </div>
      <div class="event">
        <h3>DIY Art Workshop</h3>
        <p>September 20, 2025 | Online via Zoom</p>
        <button onclick="window.location.href='https://eventbrite.com/e/diy-art-workshop-online'">Reserve Spot</button>
      </div>
      <div class="event">
        <h3>Family Fun Festival</h3>
        <p>October 5, 2025 | Patterson Park, Baltimore</p>
        <button onclick="window.location.href='https://eventbrite.com/e/family-fun-festival-baltimore'">Get Tickets</button>
      </div>
    </div>
  </section>

  <section id="pricing">
    <h2>Membership Options</h2>
    <div class="pricing">
      <div class="plan"><h3>Drop-In</h3><p>$15/event</p><button onclick="window.location.href='https://buy.stripe.com/test_dropin'">Choose</button></div>
      <div class="plan"><h3>Thrillz Pass</h3><p>$40/month</p><button onclick="window.location.href='https://buy.stripe.com/test_thrillzpass'">Choose</button></div>
      <div class="plan"><h3>Team Pack</h3><p>$100/month (up to 5 people)</p><button onclick="window.location.href='https://buy.stripe.com/test_teampack'">Choose</button></div>
    </div>
  </section>

  <section id="about">
    <h2>About Just4Thrillz</h2>
    <p>Founded in Baltimore, Just4Thrillz is a hybrid entertainment and learning platform designed to bring people together through exciting events both online and offline. We believe in inclusivity, fun, and creating memorable experiences for our community in Baltimore and beyond.</p>
  </section>

  <section id="newsletter" class="newsletter">
    <h2>Join Our Mailing List</h2>
    <p>Get updates on upcoming events, special offers, and exclusive content!</p>
    <form onsubmit="subscribeToMailchimp(event)">
      <input type="text" id="subscriberName" placeholder="Your Name" required>
      <input type="email" id="subscriberEmail" placeholder="Enter your email" required>
      <button type="submit">Subscribe</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form onsubmit="alert('Thank you! We will get back to you soon.'); return false;">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="4"></textarea>
      <button type="submit" class="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Just4Thrillz | Baltimore, MD | <a href="http://just4thrillz.com" style="color:#ffd700;">www.just4thrillz.com</a></p>
  </footer>
</body>
</html>
