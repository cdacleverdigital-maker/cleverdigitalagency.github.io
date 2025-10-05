<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Clever Digital Agency — Premium Shopify & eCommerce Development</title>
  <meta name="description" content="Clever Digital Agency — Premium Shopify Plus development, Product Traffic Optimization and high-ticket eCommerce growth." />
  <!-- Open Graph -->
  <meta property="og:title" content="Clever Digital Agency — Premium Shopify & eCommerce Development">
  <meta property="og:description" content="Premium Shopify Plus development and Product Growth solutions.">
  <link rel="stylesheet" href="style.css" />
  <link rel="icon" href="assets/favicon.ico" />
</head>
<body class="dark">
  <!-- Header -->
  <header class="site-header">
    <div class="container header-inner">
      <a href="#" class="logo-link" aria-label="Clever Digital Agency">
        <!-- === REPLACE THIS SVG/IMG with your exported logo file (logo.svg or logo.png) === -->
        <!-- Put your logo at: public/assets/logo.svg OR ./assets/logo.svg (relative to index.html) -->
        <img id="site-logo" src="assets/logo.svg" alt="Clever Digital Agency logo" />
      </a>

      <nav id="nav" class="nav">
        <ul class="nav-list">
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#analyzer">Website Analyzer</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
          <li><a href="#team">Team</a></li>
          <li><a href="#contact">Contact</a></li>
          <li><a class="cta" href="#contact">Get Started</a></li>
        </ul>
      </nav>

      <button id="nav-toggle" class="nav-toggle" aria-label="Open menu">☰</button>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="hero">
    <div class="container hero-inner">
      <div class="hero-copy">
        <h1>We build Shopify stores that scale — design, dev & growth.</h1>
        <p class="lead">Premium Shopify Plus development, Product Traffic Optimization (PTO) and Product Growth Engine (PGE) — for ambitious brands ready to scale.</p>
        <div class="hero-ctas">
          <a class="btn btn-primary" href="#contact">Book Strategy Call</a>
          <a class="btn btn-outline" href="#portfolio">View Work</a>
        </div>
      </div>
      <div class="hero-media">
        <!-- Replace this with a hero image / video if you have one -->
        <div class="hero-card">
          <h3>Product Growth Snapshot</h3>
          <ul class="stats">
            <li><strong>+37%</strong><span>Avg. conversion lift</span></li>
            <li><strong>+52%</strong><span>Avg. AOV growth</span></li>
            <li><strong>1–2 weeks</strong><span>to first iterate</span></li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="section">
    <div class="container">
      <h2 class="section-title">What we do</h2>
      <p class="section-sub">End-to-end Shopify & eCommerce services — product-first, data-forward, built for revenue.</p>

      <div class="cards">
        <article class="card">
          <h3>Shopify Plus Development</h3>
          <p>Custom themes, headless implementations, performance-first builds and scalable storefront architecture.</p>
        </article>
        <article class="card">
          <h3>Product Traffic Optimization</h3>
          <p>Conversion-first product pages, visual stacks, and checkout simplicity that drive more purchases per visit.</p>
        </article>
        <article class="card">
          <h3>Growth & CRO</h3>
          <p>Experimentation, AI personalization, and revenue-justifying roadmaps focused on LTV and ROAS.</p>
        </article>
        <article class="card">
          <h3>Paid Media & Funnels</h3>
          <p>End-to-end campaign structuring, measurement plan and on-site funnel optimizations for paid channels.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- Website Analyzer (replaces Blog) -->
  <section id="analyzer" class="section dark-section">
    <div class="container">
      <h2 class="section-title white">Website Analyzer</h2>
      <p class="section-sub white">Paste a store URL to run a quick product & page-level audit — mock results below. This mirrors the Ecommark "Instant Store Viewer".</p>

      <div class="analyzer">
        <input id="analyze-url" class="input" type="url" placeholder="https://example-store.com" />
        <!-- === CHANGE THE REDIRECT BELOW: set REDIRECT_URL in script.js variable `FORM_REDIRECT_URL` === -->
        <button id="analyze-btn" class="btn btn-primary">Analyze</button>
      </div>

      <div id="analysis-result" class="analysis-result hidden" aria-live="polite">
        <!-- Mock results injected via script.js -->
      </div>

      <p class="muted">This is a static demo analyzer. In a production build we'd fetch live metrics via serverless functions and integrate FLARE™ diagnostics.</p>
    </div>
  </section>

  <!-- Portfolio / Case Studies -->
  <section id="portfolio" class="section">
    <div class="container">
      <h2 class="section-title">Selected Work</h2>
      <p class="section-sub">Real results for Shopify stores — showcase, approach and metrics.</p>

      <div class="portfolio-grid">
        <figure class="work-card">
          <img src="assets/portfolio-1.jpg" alt="Portfolio 1 — store redesign" />
          <figcaption>
            <h3>Conversion-First Redesign</h3>
            <p>Shopify theme rebuild focused on conversions — 28% revenue lift in 90 days.</p>
          </figcaption>
        </figure>

        <figure class="work-card">
          <img src="assets/portfolio-2.jpg" alt="Portfolio 2 — headless storefront" />
          <figcaption>
            <h3>Headless Storefront</h3>
            <p>Headless implementation with custom PDPs and visual merchandising.</p>
          </figcaption>
        </figure>

        <figure class="work-card">
          <img src="assets/portfolio-3.jpg" alt="Portfolio 3 — visual stack & AR" />
          <figcaption>
            <h3>Visual Stack & AR</h3>
            <p>AR product previews and dynamic visual stacks for higher add-to-cart rates.</p>
          </figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- Team -->
  <section id="team" class="section dark-section">
    <div class="container">
      <h2 class="section-title white">Our Team</h2>
      <p class="section-sub white">Small, senior team. Replace images & names below with your own team files.</p>

      <div class="team-grid">
        <!-- === REPLACE team-member-1.jpg with your team photos (assets/team-1.jpg, etc.) === -->
        <!-- Update names, titles, and links below inside the markup or in script.js if you prefer dynamic data -->
        <div class="team-card">
          <img src="assets/team-1.jpg" alt="Abdul Malik — Founder" />
          <h4>Abdul Malik</h4>
          <p class="muted">Founder & Shopify Lead</p>
        </div>

        <div class="team-card">
          <img src="assets/team-2.jpg" alt="Growth Strategist" />
          <h4>Jamal Smith</h4>
          <p class="muted">Growth Strategist</p>
        </div>

        <div class="team-card">
          <img src="assets/team-3.jpg" alt="Creative Director" />
          <h4>Leila Tech</h4>
          <p class="muted">Creative Director</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="section">
    <div class="container contact-inner">
      <div class="contact-copy">
        <h2 class="section-title">Start a Project</h2>
        <p class="section-sub">Tell us about your store and goals. We only take premium clients who are ready to move fast.</p>

        <ul class="features">
          <li>Premium Shopify + Headless</li>
          <li>Product-first CRO</li>
          <li>Dedicated fractional team</li>
        </ul>
      </div>

      <form id="contact-form" class="contact-form" onsubmit="return false;">
        <label>
          <span class="label-text">Full name</span>
          <input id="name" class="input" type="text" required placeholder="Jane Doe" />
        </label>

        <label>
          <span class="label-text">Work email</span>
          <input id="email" class="input" type="email" required placeholder="you@brand.com" />
        </label>

        <label>
          <span class="label-text">Website</span>
          <input id="website" class="input" type="url" placeholder="https://yourstore.com" />
        </label>

        <label>
          <span class="label-text">Brief message</span>
          <textarea id="message" class="input" rows="4" placeholder="Short summary of the project / budget"></textarea>
        </label>

        <div class="form-row">
          <button id="submit-btn" class="btn btn-primary" type="submit">Send inquiry</button>
          <button id="book-btn" class="btn btn-outline" type="button">Book a call</button>
        </div>

        <p id="form-status" class="muted small hidden" role="status"></p>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="site-footer">
    <div class="container footer-inner">
      <div class="footer-left">
        <a href="#" class="logo-link">
          <img src="assets/logo.svg" alt="Clever Digital Agency logo" />
        </a>
        <p class="muted small">© <span id="year"></span> Clever Digital Agency — All rights reserved.</p>
      </div>

      <div class="footer-right">
        <nav class="footer-nav">
          <a href="#services">Services</a>
          <a href="#portfolio">Portfolio</a>
          <a href="#contact">Contact</a>
        </nav>
        <div class="socials">
          <!-- Replace with your links -->
          <a href="#" aria-label="Instagram">IG</a>
          <a href="#" aria-label="LinkedIn">LI</a>
        </div>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
