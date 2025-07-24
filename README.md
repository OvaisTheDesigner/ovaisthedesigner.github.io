<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ovais | Web Designer</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet" />
  <style>
    :root {
      --primary: #3b82f6;
      --bg: #0f172a;
      --light-bg: #1e293b;
      --text: #ffffff;
      --muted: #94a3b8;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background-color: var(--bg);
      color: var(--text);
    }
    header {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      height: 100vh;
      padding: 0 20px;
      background: linear-gradient(to right, #1e293b, #0f172a);
      animation: fadeIn 2s ease-in-out;
    }
    header h1 {
      font-size: 3.5rem;
      color: var(--primary);
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
      color: var(--muted);
    }
    .btn {
      margin-top: 20px;
      padding: 12px 25px;
      background: var(--primary);
      color: white;
      text-decoration: none;
      border-radius: 6px;
      transition: 0.3s;
    }
    .btn:hover {
      background: #2563eb;
    }
    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
      animation: fadeInUp 1s ease-in-out;
    }
    section h2 {
      text-align: center;
      font-size: 2.5rem;
      color: var(--primary);
      margin-bottom: 40px;
    }
    .about, .contact, .footer {
      text-align: center;
    }
    .projects, .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }
    .card {
      background: var(--light-bg);
      padding: 25px;
      border-radius: 10px;
      text-align: center;
      transform: scale(1);
      transition: 0.4s ease;
    }
    .card:hover {
      transform: scale(1.05);
      background-color: #334155;
    }
    .footer {
      padding: 30px;
      color: var(--muted);
      font-size: 0.9rem;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <!-- Hero -->
  <header>
    <h1>Hello, I'm Ovais</h1>
    <p>Professional Web & Shopify Designer</p>
    <a href="#contact" class="btn">Contact Me</a>
  </header>

  <!-- About -->
  <section class="about" id="about">
    <h2>About Me</h2>
    <p>
      I design visually stunning and user-friendly websites. My passion is building
      modern, responsive layouts that not only look great but convert well. I specialize in Shopify and custom web design.
    </p>
  </section>

  <!-- Services -->
  <section class="services" id="services">
    <h2>My Services</h2>
    <div class="services">
      <div class="card">
        <h3>Website Design</h3>
        <p>Creative and clean website design with responsive layout and modern UI.</p>
      </div>
      <div class="card">
        <h3>Shopify Stores</h3>
        <p>Complete Shopify setup, customization, and optimization.</p>
      </div>
      <div class="card">
        <h3>Brand Identity</h3>
        <p>Visual branding solutions including logo design, typography, and color themes.</p>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section class="projects" id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Furniture Store</h3>
        <p>Built a modern furniture store with minimalistic layout and high-conversion design.</p>
      </div>
      <div class="card">
        <h3>Abaya Brand</h3>
        <p>Developed a luxury fashion website for an abaya clothing brand with elegant UI.</p>
      </div>
      <div class="card">
        <h3>Tech Landing Page</h3>
        <p>Landing page for a startup showcasing products and features with CTA sections.</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="contact" id="contact">
    <h2>Contact Me</h2>
    <p>Email: youremail@example.com</p>
    <p>Instagram: @ovaisthedesigner</p>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>© 2025 Ovais. All Rights Reserved.</p>
  </footer>

</body>
</html>
