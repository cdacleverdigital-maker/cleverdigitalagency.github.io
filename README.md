<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Clever Digital Agency</title>
  <meta name="description" content="Premium Shopify & eCommerce solutions by Clever Digital Agency — global leader in digital transformation." />
  <link rel="icon" type="image/png" href="favicon.png" />
  <style>
    :root {
      --brand-bg: #0b1220;
      --brand-accent: #ff4500;
      --brand-text: #f9f9f9;
      --brand-muted: #9ca3af;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }
    body {
      background-color: var(--brand-bg);
      color: var(--brand-text);
      scroll-behavior: smooth;
    }
    header {
      width: 100%;
      background: rgba(11, 18, 32, 0.9);
      position: fixed;
      top: 0;
      z-index: 1000;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1rem 5%;
      backdrop-filter: blur(8px);
      border-bottom: 1px solid rgba(255,255,255,0.05);
    }
    header img {
      height: 40px;
    }
    nav a {
      color: var(--brand-text);
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: var(--brand-accent);
    }
    .hero {
      min-height: 100vh;
      background: linear-gradient(to right, rgba(11,18,32,0.9), rgba(11,18,32,0.8)), url('https://images.unsplash.com/photo-1522199794611-8e3563a36a1a?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 5%;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
      color: var(--brand-accent);
    }
    .hero p {
      max-width: 600px;
      margin: 0 auto 2rem;
      color: var(--brand-muted);
      line-height: 1.7;
    }
    .btn {
      background: var(--brand-accent);
      color: #fff;
      padding: 0.9rem 2rem;
      border: none;
      border-radius: 5px;
      font-weight: 600;
      cursor: pointer;
      transition: 0.3s;
    }
    .btn:hover {
      background: #ff5e1f;
    }
    section {
      padding: 5rem 5%;
    }
    h2 {
      text-align: center;
      font-size: 2.5rem;
      color: var(--brand-accent);
      margin-bottom: 2rem;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .service {
      background: rgba(255,255,255,0.05);
      padding: 2rem;
      border-radius: 10px;
      transition: 0.3s;
    }
    .service:hover {
      transform: translateY(-5px);
      background: rgba(255,255,255,0.08);
    }
    .service h3 {
      margin-bottom: 1rem;
      color: var(--brand-text);
    }
    .service p {
      color: var(--brand-muted);
      line-height: 1.6;
    }
    .team {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      text-align: center;
    }
    .member {
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
      padding: 2rem;
      transition: 0.3s;
    }
    .member:hover {
      transform: translateY(-5px);
    }
    .member img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 1rem;
    }
    .member h4 {
      color: var(--brand-text);
      margin-bottom: 0.5rem;
    }
    .member p {
      color: var(--brand-muted);
      font-size: 0.9rem;
    }
    form {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    input, textarea {
      background: rgba(255,255,255,0.05);
      border: none;
      padding: 0.8rem;
      color: var(--brand-text);
      border-radius: 5px;
      font-size: 1rem;
    }
    footer {
      background: rgba(255,255,255,0.05);
      text-align: center;
      padding: 2rem;
      margin-top: 3rem;
    }
    footer p {
      color: var(--brand-muted);
      font-size: 0.9rem;
    }
    @media(max-width:768px) {
      .hero h1 {font-size: 2.2rem;}
      header {flex-direction: column;}
      nav {margin-top: 1rem;}
    }
  </style>
</head>

<body>
  <header>
    <img src="<!-- 🔧 EDIT THIS: your logo file e.g. assets/logo.png -->" alt="Clever Digital Agency Logo" />
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#team">Team</a>
      <a href="#analyzer">Website Analyzer</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div>
      <h1>We Build Profitable Shopify Stores</h1>
      <p>At Clever Digital Agency, we craft high-performing eCommerce solutions that turn visitors into loyal customers. We power global brands with advanced Shopify Plus innovation.</p>
      <button class="btn" onclick="document.querySelector('#contact').scrollIntoView({behavior:'smooth'})">Get Started</button>
    </div>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service">
        <h3>Shopify Development</h3>
        <p>Custom Shopify Plus storefronts engineered for scalability, conversion, and visual excellence.</p>
      </div>
      <div class="service">
        <h3>Headless Commerce</h3>
        <p>Future-proof architecture integrating storefront APIs, AI personalization, and lightning-fast experiences.</p>
      </div>
      <div class="service">
        <h3>Conversion Optimization</h3>
        <p>Data-driven design, neuromarketing strategies, and predictive analytics that boost your ROI.</p>
      </div>
      <div class="service">
        <h3>Web3 Payments</h3>
        <p>Blockchain-enabled transactions and privacy-first data integrations for next-gen commerce.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p style="max-width:700px;margin:0 auto;text-align:center;color:var(--brand-muted);line-height:1.7;">
      Clever Digital Agency is a global Shopify development powerhouse, helping visionary brands achieve exponential growth. We combine strategy, creativity, and technology to deliver measurable results and future-proof eCommerce infrastructure.
    </p>
  </section>

  <section id="team">
    <h2>Our Team</h2>
    <div class="team">
      <div class="member">
        <img src="<!-- 🔧 EDIT THIS: your photo e.g. assets/malik.jpg -->" alt="Abdul Malik" />
        <h4>Abdul Malik</h4>
        <p>Founder & Shopify Lead</p>
      </div>
      <div class="member">
        <img src="<!-- 🔧 EDIT THIS: team member photo -->" alt="Team Member" />
        <h4>Team Member Name</h4>
        <p>Position / Role</p>
      </div>
    </div>
  </section>

  <section id="analyzer">
    <h2>Website Analyzer</h2>
    <p style="text-align:center;max-width:700px;margin:0 auto;color:var(--brand-muted);">
      Instantly analyze your eCommerce store’s performance and discover optimization opportunities powered by FLARE™ diagnostics.
    </p>
    <div style="text-align:center;margin-top:2rem;">
      <button class="btn" onclick="window.open('<!-- 🔧 EDIT THIS: your analyzer link e.g. https://cleverdigital.agency/audit -->','_blank')">Run Audit</button>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form id="contactForm">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <textarea id="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© <span id="year"></span> Clever Digital Agency. All Rights Reserved.</p>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();

    document.getElementById("contactForm").addEventListener("submit", function(e){
      e.preventDefault();
      const redirectURL = "<!-- 🔧 EDIT THIS: your redirect link e.g. https://tally.so/r/wXYZ -->";
      alert("Form submitted successfully!");
      if(redirectURL && redirectURL.indexOf("http")===0){
        window.location.href = redirectURL;
      }
    });
  </script>
</body>
</html>
