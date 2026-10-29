
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Professional website design and digital services for small businesses.">
  <title>Nova Business | Grow Your Business Online</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      font-family: Arial, sans-serif;
      color: #172033;
      background: #ffffff;
      line-height: 1.6;
    }
    a { text-decoration: none; }
    .nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 7%;
      background: #fff;
      position: sticky;
      top: 0;
      z-index: 10;
      box-shadow: 0 2px 15px #0000000c;
    }
    .logo { font-size: 24px; font-weight: 800; color: #2563eb; }
    .nav a { color: #172033; font-weight: 600; }
    .hero {
      padding: 85px 7%;
      text-align: center;
      color: white;
      background: linear-gradient(135deg, #10234d, #2563eb);
    }
    .tag {
      display: inline-block;
      padding: 7px 14px;
      border: 1px solid #ffffff70;
      border-radius: 30px;
      margin-bottom: 22px;
      font-size: 14px;
    }
    .hero h1 {
      font-size: clamp(36px, 7vw, 58px);
      line-height: 1.15;
      max-width: 750px;
      margin: 0 auto 22px;
    }
    .hero p {
      max-width: 600px;
      margin: auto;
      color: #e1eaff;
      font-size: 18px;
    }
    .btn {
      display: inline-block;
      background: #16a36a;
      color: white;
      padding: 13px 23px;
      border-radius: 9px;
      font-weight: bold;
      margin-top: 25px;
    }
    .btn:hover { background: #128455; }
    .section { padding: 70px 7%; text-align: center; }
    .section h2 { font-size: 32px; margin-bottom: 12px; }
    .intro {
      color: #64748b;
      max-width: 600px;
      margin: 0 auto 35px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 22px;
      max-width: 1050px;
      margin: 35px auto 0;
      text-align: left;
    }
    .card {
      padding: 27px;
      border: 1px solid #e5eaf2;
      border-radius: 16px;
      background: white;
      box-shadow: 0 8px 25px #10234d09;
    }
    .symbol { font-size: 32px; margin-bottom: 12px; }
    .card h3 { font-size: 20px; margin-bottom: 10px; }
    .card p { color: #64748b; }
    .about { background: #f4f7fc; }
    .price { color: #2563eb; font-size: 28px; font-weight: 800; margin: 15px 0; }
    .card ul { padding-left: 20px; color: #475569; }
    .contact {
      background: #10234d;
      color: white;
    }
    .contact p { color: #dbe6ff; }
    .contact .btn { color: white; }
    footer {
      padding: 22px 7%;
      text-align: center;
      color: #64748b;
      font-size: 14px;
    }
    .note { font-size: 12px; margin-top: 16px; opacity: .8; }
    @media (max-width: 480px) {
      .nav { padding: 15px 5%; }
      .logo { font-size: 21px; }
      .hero { padding: 65px 6%; }
      .section { padding: 55px 6%; }
      .section h2 { font-size: 28px; }
      .grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

  <nav class="nav">
    <a class="logo" href="#home">NOVA.</a>
    <a href="#contact">Contact Us ↗</a>
  </nav>

  <header class="hero" id="home">
    <span class="tag">YOUR BUSINESS, OUR PASSION</span>
    <h1>Grow Your Business With Confidence</h1>
    <p>
      Smart solutions for modern businesses.
      Build your online presence and reach more customers.
    </p>
    <a class="btn" href="#services">Explore Our Services →</a>
  </header>

  <section class="section" id="services">
    <h2>What We Offer</h2>
    <p class="intro">
      Simple, professional services to help your business move forward.
    </p>

    <div class="grid">
      <article class="card">
        <div class="symbol">🌐</div>
        <h3>Website Design</h3>
        <p>Modern, mobile-friendly websites designed for your business.</p>
      </article>

      <article class="card">
        <div class="symbol">📱</div>
        <h3>Online Presence</h3>
        <p>Make it easier for potential customers to discover your business.</p>
      </article>

      <article class="card">
        <div class="symbol">🎯</div>
        <h3>Business Solutions</h3>
        <p>Present your services, business information and contact details clearly.</p>
      </article>
    </div>
  </section>

  <section class="section about" id="about">
    <h2>About Our Business</h2>
    <p class="intro">
      We believe every small business deserves a professional online presence.
      Our goal is to create clean, useful and responsive website experiences.
    </p>
  </section>

  <section class="section" id="pricing">
    <h2>Our Sample Packages</h2>
    <p class="intro">
      Example prices only. Final prices depend on the project and customer needs.
    </p>

    <div class="grid">
      <article class="card">
        <h3>Starter</h3>
        <div class="price">PKR 5,000</div>
        <ul>
          <li>One-page website</li>
          <li>Mobile-friendly layout</li>
          <li>Contact section</li>
        </ul>
        <a class="btn" href="#contact">Ask About This</a>
      </article>

      <article class="card">
        <h3>Business</h3>
        <div class="price">PKR 10,000</div>
        <ul>
          <li>Up to five pages</li>
          <li>Services and about sections</li>
          <li>Contact links</li>
        </ul>
        <a class="btn" href="#contact">Ask About This</a>
      </article>

      <article class="card">
        <h3>Custom</h3>
        <div class="price">Let's Talk</div>
        <ul>
          <li>Custom design</li>
          <li>Features based on requirements</li>
          <li>Project-specific quotation</li>
        </ul>
        <a class="btn" href="#contact">Get a Quote</a>
      </article>
    </div>
  </section>

  <section class="section contact" id="contact">
    <h2>Let's Work Together</h2>
    <p>Have a project in mind? Contact us to discuss your requirements.</p>

    <!-- Replace the sample number below with your WhatsApp number -->
    <a class="btn"
       href="https://wa.me/923001234567"
       target="_blank"
       rel="noopener noreferrer">
      Chat on WhatsApp →
    </a>

    <p class="note">
      Demo template: replace the business name, sample prices,
      service descriptions and contact number before publishing for a client.
    </p>
  </section>

  <footer>
    © <span id="year">2026</span> Nova Business. All rights reserved.
  </footer>

</body>
</html>
