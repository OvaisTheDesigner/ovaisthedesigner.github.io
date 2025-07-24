<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ovais | Professional Web Designer</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #1e2a38;
      --secondary-color: #f7f9fb;
      --accent-color: #2a9d8f;
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
      scroll-behavior: smooth;
    }
    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
      color: var(--primary-color);
      text-align: center;
      margin-bottom: 1.5rem;
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
      max-width: 650px;
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
      transition: background-color 0.3s ease;
    }
    .cta-button:hover {
      background-color: #21867a;
    }
    .projects-grid, .reviews-grid, .services-grid, .pricing-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      text-align: center;
    }
    .about-section {
      display: flex;
      gap: 2rem;
      align-items: center;
      flex-wrap: wrap;
    }
    .about-section img {
      width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .about-section div {
      flex: 1;
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
    .popup {
      position: fixed;
      top: 20px;
      right: 20px;
      background-color: var(--accent-color);
      color: white;
      padding: 1rem 2rem;
      border-radius: 8px;
      box-shadow: 0 2px 12px rgba(0,0,0,0.2);
      display: none;
      z-index: 999;
    }
  </style>
</head>
<body>

  <div class="popup" id="popup">Thanks for visiting my portfolio!</div>

  <section class="hero">
    <h1>Ovais – Professional Web Designer</h1>
    <p>I help brands and businesses build clean, modern, and high-converting websites using Shopify & Figma-based custom design tools.</p>
    <button class="cta-button" onclick="showPopup()">Let’s Work Together</button>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <div class="about-section">
      <img src="https://via.placeholder.com/300x300" alt="Ovais - Web Designer">
      <div>
        <p>Hello, I'm Ovais – a creative and detail-oriented web designer with experience in crafting high-converting websites using Shopify and Figma. My focus is on clean aesthetics, usability, and optimized UX/UI experiences that connect businesses with their ideal clients.</p>
        <p><strong>Skills:</strong> Shopify, Responsive Web Design, UX/UI Strategy, Figma, Conversion Optimization, Branding, Animation, Mobile Optimization</p>
      </div>
    </div>
  </section>

  <section id="services">
    <h2>What I Offer</h2>
    <div class="services-grid">
      <div class="card">
        <h3>Shopify Website Design</h3>
        <p>Clean, conversion-focused designs with mobile responsiveness and fast performance.</p>
      </div>
      <div class="card">
        <h3>Landing Pages</h3>
        <p>High-converting sales pages for product launches, services, and lead generation.</p>
      </div>
      <div class="card">
        <h3>UX Strategy</h3>
        <p>Wireframes, user journeys, and intuitive interfaces to increase engagement.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Featured Projects</h2>
    <div class="projects-grid">
      <div class="card">
        <img src="https://via.placeholder.com/300x180" alt="Furniture Store">
        <h3>Furniture Store</h3>
        <p>Minimalist layout with trust-building elements and beautiful product presentation.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x180" alt="Clothing Brand">
        <h3>Clothing Brand</h3>
        <p>Mobile-optimized layout with strong branding and custom animations.</p>
      </div>
    </div>
  </section>

  <section id="reviews">
    <h2>Client Reviews</h2>
    <div class="reviews-grid">
      <div class="card">
        <p>"Ovais delivered an elegant site, and my conversions increased 2x. Highly professional!"</p>
        <strong>— Sarah L., US</strong>
      </div>
      <div class="card">
        <p>"He redesigned our Shopify store and the experience was smooth, organized, and fast."</p>
        <strong>— Ahmed M., UK</strong>
      </div>
      <div class="card">
        <p>"Creative, responsive, and result-driven. Will work with him again."</p>
        <strong>— Julia R., Germany</strong>
      </div>
    </div>
  </section>

  <section id="pricing">
    <h2>Pricing</h2>
    <div class="pricing-grid">
      <div class="card">
        <h3>Starter</h3>
        <p>$299 – One-page portfolio/site, optimized for mobile & fast delivery.</p>
      </div>
      <div class="card">
        <h3>Business</h3>
        <p>$599 – Up to 5 pages with branding, responsive layout, and basic SEO.</p>
      </div>
      <div class="card">
        <h3>Pro</h3>
        <p>$999+ – Complete Shopify store setup with custom design and integrations.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Ready to take your online presence to the next level? Let’s connect.</p>
    <form>
      <input type="text" placeholder="Your Name" required><br><br>
      <input type="email" placeholder="Your Email" required><br><br>
      <textarea placeholder="Your Message" rows="5" required></textarea><br><br>
      <button class="cta-button" type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Ovais. All rights reserved. | Designed by <strong>OvaisTheDesigner</strong></p>
  </footer>

  <script>
    function showPopup() {
      const popup = document.getElementById('popup');
      popup.style.display = 'block';
      setTimeout(() => {
        popup.style.display = 'none';
      }, 4000);
    }
  </script>

</body>
</html>
