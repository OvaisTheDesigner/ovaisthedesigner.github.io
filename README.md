<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ovais | Web Designer Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #1F2937;
      --secondary: #4B5563;
      --accent: #10B981;
      --background: #F9FAFB;
      --font-heading: 'Playfair Display', serif;
      --font-body: 'Inter', sans-serif;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: var(--font-body);
      background: var(--background);
      color: var(--primary);
      line-height: 1.6;
    }

    header, section, footer {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: auto;
    }

    h1, h2, h3 {
      font-family: var(--font-heading);
      margin-bottom: 1rem;
    }

    h1 {
      font-size: 3rem;
    }

    .btn {
      background: var(--accent);
      color: #fff;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-weight: 600;
      text-decoration: none;
    }

    .hero {
      text-align: center;
    }

    .projects, .services, .reviews, .pricing, .contact {
      margin-top: 3rem;
    }

    .project, .service, .review, .price-card {
      background: #fff;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      margin-bottom: 1.5rem;
    }

    .project img, .review img {
      width: 100%;
      border-radius: 6px;
      margin-top: 1rem;
    }

    .contact form {
      display: flex;
      flex-direction: column;
    }

    .contact input, .contact textarea {
      padding: 0.75rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    footer {
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header class="hero">
    <h1>Ovais – Shopify Web Designer</h1>
    <p>I build high-converting, professional Shopify websites that grow your business.</p>
    <a href="#contact" class="btn">Get Your Website</a>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>I’m Ovais, a professional Shopify web designer with a passion for clean, modern design and smart digital strategies. I help international businesses build online stores that look great and convert customers.</p>
  </section>

  <section class="projects">
    <h2>Featured Projects</h2>
    <div class="project">
      <h3>Modern Home Decor</h3>
      <p>Shopify website for an international home decor brand, focused on clean navigation and conversion-friendly layout.</p>
      <img src="https://via.placeholder.com/800x400" alt="Project Screenshot">
    </div>
    <div class="project">
      <h3>Fitness Gear Store</h3>
      <p>A bold, energetic design for a fitness product brand targeting European markets.</p>
      <img src="https://via.placeholder.com/800x400" alt="Project Screenshot">
    </div>
  </section>

  <section class="services">
    <h2>What I Offer</h2>
    <div class="service">
      <h3>Shopify Website Design</h3>
      <p>Custom Shopify storefronts optimized for trust, speed, and conversions.</p>
    </div>
    <div class="service">
      <h3>Landing Page Design</h3>
      <p>Focused, high-converting landing pages for product launches or campaigns.</p>
    </div>
    <div class="service">
      <h3>Ongoing Support</h3>
      <p>Need updates or tweaks? I offer monthly retainers and priority support options.</p>
    </div>
  </section>

  <section class="reviews">
    <h2>Client Testimonials</h2>
    <div class="review">
      <p>“Ovais turned our messy online store into a beautiful, professional platform. Our sales increased 40%!”</p>
      <strong>— Emily, UK</strong>
    </div>
    <div class="review">
      <p>“He really understood our brand and made something better than we imagined.”</p>
      <strong>— Daniel, Germany</strong>
    </div>
    <div class="review">
      <p>“Super smooth communication, reliable, and very creative. Highly recommend.”</p>
      <strong>— Fatima, UAE</strong>
    </div>
  </section>

  <section class="pricing">
    <h2>Packages</h2>
    <div class="price-card">
      <h3>Starter</h3>
      <p>$300 – 1 Page Landing</p>
      <p>Perfect for simple campaigns or launches.</p>
    </div>
    <div class="price-card">
      <h3>Business</h3>
      <p>$750 – 4 Pages</p>
      <p>Ideal for growing brands needing a solid foundation.</p>
    </div>
    <div class="price-card">
      <h3>Pro</h3>
      <p>$1500 – 7+ Pages + Custom Features</p>
      <p>Tailored for international brands with scaling needs.</p>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Let’s Work Together</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Tell me about your project..." rows="5" required></textarea>
      <button class="btn" type="submit">Send Message</button>
    </form>
    <p>Email: <a href="mailto:hello@ovaisthedesigner.com">hello@ovaisthedesigner.com</a></p>
    <p>Instagram: <a href="https://instagram.com/OvaisTheDesigner" target="_blank">@OvaisTheDesigner</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Ovais – All rights reserved.</p>
    <p><a href="#">Privacy Policy</a> | <a href="#">Terms</a></p>
  </footer>

</body>
</html>
