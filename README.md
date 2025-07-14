<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SixStrong Construction Inc</title>
  <style>
    body { margin:0; font-family: Arial, sans-serif; color: #333; }
    header { background:#222; color:#fff; padding:1rem; position:sticky; top:0; }
    header nav a { color:#fff; margin:0 0.5rem; text-decoration:none; }
    .hero {
      display:flex; flex-direction:column; align-items:center;
      justify-content:center; min-height:60vh; background:url('https://via.placeholder.com/1200x600') center/cover no-repeat;
      color:white; text-align:center; padding:0 1rem;
    }
    .hero h1 { font-size:2.5rem; margin-bottom:0.5rem; }
    .hero p { font-size:1.2rem; margin-bottom:1rem; }
    .hero a { background:#e67e22; color:#fff; padding:0.8rem 1.5rem; text-decoration:none; border-radius:4px; }
    section { padding:2rem 1rem; max-width:1000px; margin:0 auto; }
    .services, .gallery { display:grid; gap:1rem; }
    .services { grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); }
    .service { border:1px solid #ddd; padding:1rem; border-radius:4px; text-align:center; }
    .gallery { grid-template-columns:repeat(auto-fit,minmax(150px,1fr)); }
    .gallery img { width:100%; height:auto; border-radius:4px; }
    .cta { background:#f4f4f4; text-align:center; padding:2rem 1rem; }
    .cta a { background:#27ae60; color:#fff; padding:1rem 2rem; text-decoration:none; border-radius:4px; font-size:1.1rem; }
    .contact-form { max-width:600px; margin:0 auto; display:grid; gap:1rem; }
    .contact-form input, .contact-form textarea, .contact-form select { padding:0.8rem; border:1px solid #ccc; border-radius:4px; width:100%; }
    footer { background:#222; color:#fff; text-align:center; padding:1rem; }
    @media(min-width:600px) {
      .hero { min-height:80vh; }
      .hero h1 { font-size:3.5rem; }
    }
  </style>
</head>
<body>

  <header>
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#quote">Quote</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>We Build the 6ix Strong</h1>
    <p>Trusted construction services across the GTA</p>
    <a href="#quote">Get a Free Quote</a>
  </section>

  <section id="services">
    <h2>What We Do</h2>
    <div class="services">
      <div class="service"><h3>Framing & Drywall</h3><p>Precise, reliable, on schedule.</p></div>
      <div class="service"><h3>Full Renovations</h3><p>Kitchens, bathrooms, basements.</p></div>
      <div class="service"><h3>Painting & Finishing</h3><p>Fresh, clean, professional results.</p></div>
      <div class="service"><h3>General Contracting</h3><p>Coordinated & fully managed projects.</p></div>
      <div class="service"><h3>Residential & Commercial</h3><p>Flexible service for all property types.</p></div>
      <div class="service"><h3>Mobile Handyman</h3><p>Quick fixes, repairs & small jobs.</p></div>
    </div>
  </section>

  <section id="gallery">
    <h2>Our Work</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Project+1" alt="Project 1">
      <img src="https://via.placeholder.com/300x200?text=Project+2" alt="Project 2">
      <img src="https://via.placeholder.com/300x200?text=Project+3" alt="Project 3">
      <img src="https://via.placeholder.com/300x200?text=Project+4" alt="Project 4">
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>SixStrong was built on hard work, reliability, and representing the 6ix the right way.</p>
    <p><strong>Licensed & Insured • Serving the GTA • Years of Experience</strong></p>
  </section>

  <section id="quote">
    <h2>Get a Free Quote</h2>
    <form class="contact-form" action="mailto:buildingthe6ixup@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="Name" placeholder="Your Name" required>
      <input type="tel" name="Phone" placeholder="Phone Number" required>
      <input type="email" name="Email" placeholder="Email Address" required>
      <select name="Service">
        <option value="">Which service?</option>
        <option>Framing & Drywall</option>
        <option>Full Renovation</option>
        <option>Painting & Finishing</option>
        <option>General Contracting</option>
        <option>Handyman Service</option>
      </select>
      <textarea name="Details" rows="4" placeholder="Describe your project (optional)"></textarea>
      <input type="text" name="Location" placeholder="Project Location (e.g. Brampton, ON)" required>
      <button type="submit">Send Quote</button>
    </form>
  </section>

  <section id="contact" class="cta">
    <h2>Let's Get Started</h2>
    <p>📞 <a href="tel:2892708339">289-270-8339</a> | ✉️ <a href="mailto:buildingthe6ixup@gmail.com">buildingthe6ixup@gmail.com</a></p>
    <p>Serving the Greater Toronto Area</p>
  </section>

  <footer>
    <p>&copy; 2025 SixStrong Construction Inc. All rights reserved.</p>
  </footer>

</body>
</html>