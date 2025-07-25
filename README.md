<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ovais | Web Designer</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #1a1a1a;
      --secondary-color: #ffffff;
      --accent-color: #005f73;
      --text-color: #222;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--secondary-color);
      color: var(--text-color);
      line-height: 1.6;
    }
    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
      color: var(--primary-color);
      text-align: center;
      margin-bottom: 1rem;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: 0 auto;
      animation: fadeInUp 1s ease both;
    }
    .hero {
      text-align: center;
      background: linear-gradient(to bottom, #f0f4f8, #ffffff);
      padding: 6rem 2rem;
    }
    .hero h1 {
      font-size: 3rem;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 1rem auto 2rem;
    }
    .cta-button {
      padding: 0.75rem 2rem;
      background-color: var(--accent-color);
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    .reviews-grid, .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    }
    footer {
      background: var(--primary-color);
      color: white;
      text-align: center;
      padding: 2rem;
    }
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
[image alt](https://github.com/OvaisTheDesigner/ovaisthedesigner.github.io/blob/3deb9fdf7024507c7e645ea9aab42ddbde93ae5b/still-xvii-photo-12.jpg)
  <section class="hero">
    <h1>Ovais – Professional Web Designer</h1>
    <p>I design clean, modern Shopify websites that are built to convert. Elevate your online presence with a site that truly represents your brand.</p>
    <button class="cta-button">Let’s Work Together</button>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hey, I’m Ovais – a professional web designer helping brands thrive online through smart, user-centered design. I specialize in Shopify, Figma, and mobile-first UX principles to build websites that not only look great, but also perform exceptionally well.</p>
    <p>I’ve worked with growing businesses from Pakistan to the UK, helping them attract more customers through impactful digital experiences.</p>
    <p><strong>Skills:</strong> Shopify, Figma, Mobile Design, UX/UI, Conversion-Focused Layouts, Brand Identity, Wireframes, and Modern Styling.</p>
  </section>

  <section id="projects">
    <h2>Featured Projects</h2>
    <div class="projects-grid">
      <div class="card">
        <h3>Furniture Store</h3>
        <p>Modern, minimalist layout with strong trust-building elements and seamless navigation.</p>
        [image alt](https://github.com/OvaisTheDesigner/ovaisthedesigner.github.io/blob/3deb9fdf7024507c7e645ea9aab42ddbde93ae5b/still-xvii-photo-12.jpg)
      </div>
      <div class="card">
        <h3>Clothing Brand</h3>
        <p>Mobile-optimized fashion site with bold visuals and a clean user journey focused on sales.</p>
      </div>
    </div>
  </section>

  <section id="services">
    <h2>What I Offer</h2>
    <ul>
      <li>Custom Shopify Website Design</li>
      <li>Conversion Optimization</li>
      <li>Landing Page Design</li>
      <li>Responsive Mobile Design</li>
      <li>UX Strategy & Wireframes</li>
    </ul>
  </section>

  <section id="reviews">
    <h2>Client Reviews</h2>
    <div class="reviews-grid">
      <div class="card">
        <p>“Ovais turned my idea into a live store that looks amazing and sells well. Smooth process!”</p>
        <strong>— Fatima K., UAE</strong>
      </div>
      <div class="card">
        <p>“Very professional and talented. The site looks premium and performs better than our old one.”</p>
        <strong>— Hassan R., Pakistan</strong>
      </div>
      <div class="card">
        <p>“Great design sense and fast turnaround. Ovais delivered more than expected!”</p>
        <strong>— Leah P., Australia</strong>
      </div>
      <div class="card">
        <p>“Super happy with the service. I loved the way he communicated and refined the site until perfect.”</p>
        <strong>— Kamal D., Canada</strong>
      </div>
    </div>
  </section>

  <section id="pricing">
    <h2>Pricing</h2>
    <div class="projects-grid">
      <div class="card">
        <h3>Starter</h3>
        <p>$299 – One-page design, mobile-friendly, fast delivery.</p>
      </div>
      <div class="card">
        <h3>Business</h3>
        <p>$599 – Up to 5 pages, brand styling, optimization, contact form.</p>
      </div>
      <div class="card">
        <h3>Pro</h3>
        <p>$999+ – Custom Shopify store, animations, SEO setup, and support.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Have a project in mind? Let’s discuss how I can bring your vision to life.</p>
    <form>
      <input type="text" placeholder="Your Name" required><br><br>
      <input type="email" placeholder="Your Email" required><br><br>
      <textarea placeholder="Your Message" rows="5" required></textarea><br><br>
      <button class="cta-button" type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Ovais. All rights reserved. | Designed by OvaisTheDesigner</p>
  </footer>

</body>
</html>
