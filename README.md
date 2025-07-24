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
      overflow-x: hidden;
    }

    section, footer, header {
      padding: 4rem 2rem;
      max-width: 1200px;
      margin: auto;
      opacity: 0;
      transform: translateY(30px);
      transition: all 0.6s ease-out;
    }

    section.visible, footer.visible, header.visible {
      opacity: 1;
      transform: translateY(0);
    }

    h1, h2, h3 {
      font-family: var(--font-heading);
      margin-bottom: 1rem;
      text-align: center;
    }

    h1 {
      font-size: 3.2rem;
    }

    h2 {
      font-size: 2.4rem;
      color: var(--accent);
    }

    .btn {
      background: var(--accent);
      color: #fff;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 600;
      text-decoration: none;
      display: inline-block;
      margin-top: 1rem;
    }

    .centered {
      text-align: center;
    }

    .grid {
      display: grid;
      gap: 2rem;
    }

    .project, .service, .review, .price-card {
      background: #fff;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.05);
      transition: transform 0.3s ease;
    }

    .project:hover, .service:hover, .review:hover, .price-card:hover {
      transform: translateY(-5px);
    }

    .grid-2 { grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); }
    .grid-3 { grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); }

    .project img, .review img {
      width: 100%;
      border-radius: 6px;
      margin-top: 1rem;
    }

    .contact form {
      display: flex;
      flex-direction: column;
      max-width: 600px;
      margin: auto;
    }

    .contact input, .contact textarea {
      padding: 0.75rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }

    footer {
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header class="hero centered">
    <h1>Ovais – Shopify Web Designer</h1>
    <p>I build high-converting, professional Shopify websites that grow your business.</p>
    <a href="#contact" class="btn">Get Your Website</a>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p class="centered">I’m Ovais, a professional Shopify web designer with a passion for clean, modern design and smart digital strategies. I help international businesses build online stores that look great and convert customers.</p>
  </section>

  <section class="projects">
    <h2>Featured Projects</h2>
    <div class="grid grid-2">
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
    </div>
  </section>

  <section class="services">
    <h2>What I Offer</h2>
    <div class="grid grid-3">
      <div class="service">
        <h3>Shopify Design</h3>
        <p>Custom Shopify storefronts optimized for trust, speed, and conversions.</p>
      </div>
      <div class="service">
        <h3>Landing Pages</h3>
        <p>Focused, high-converting landing pages for product launches or campaigns.</p>
      </div>
      <div class="service">
        <h3>Support Plans</h3>
        <p>Ongoing updates, tweaks, and priority support for your site.</p>
      </div>
    </div>
  </section>

  <section class="reviews">
    <h2>Client Testimonials</h2>
    <div class="grid grid-2">
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
    </div>
  </section>

  <section class="pricing">
    <h2>Packages</h2>
    <div class="grid grid-3">
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
    <div class="centered">
      <p>Email: <a href="mailto:hello@ovaisthedesigner.com">hello@ovaisthedesigner.com</a></p>
      <p>Instagram: <a href="https://instagram.com/OvaisTheDesigner" target="_blank">@OvaisTheDesigner</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Ovais – All rights reserved.</p>
    <p><a href="#">Privacy Policy</a> | <a href="#">Terms</a></p>
  </footer>

  <script>
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
          observer.unobserve(entry.target);
        }
      });
    }, {
      threshold: 0.1
    });

    document.querySelectorAll('section, header, footer').forEach(section => {
      observer.observe(section);
    });
  </script>
</body>
</html>
