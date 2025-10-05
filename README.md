<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Clever Digital Agency — Premium Shopify & eCommerce Dev</title>
  <meta name="description" content="Clever Digital Agency — premium Shopify Plus development, Product Growth Engine™, FLARE™ audits and high-ticket eCommerce strategies." />
  <meta property="og:title" content="Clever Digital Agency — Premium Shopify & eCommerce Dev" />
  <meta property="og:description" content="Premium Shopify Plus development, FLARE™ product audits, conversion optimization and headless commerce." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="/path/to/social-preview.jpg" />
  <link rel="icon" href="/path/to/favicon.ico"> <!-- TODO: Replace with your favicon -->
  <meta name="theme-color" content="#111111">

  <!-- Styles: Inline for single-file delivery. Replace color tokens below if desired. -->
  <style>
    /* ===== Brand tokens - change here ===== */
    :root{
      --bg: #0b0b0b; /* dark premium background */
      --card: #0f0f10;
      --muted: #9aa0a6;
      --accent: #FF4500; /* orange-red */
      --white: #ffffff;
      --glass: rgba(255,255,255,0.04);
      --max-width: 1200px;
      --radius: 14px;
      --brand-font: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }

    /* Reset + base */
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family:var(--brand-font); background:linear-gradient(180deg,var(--bg) 0%, #060606 100%); color:var(--white); -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale; line-height:1.5;
    }

    .container{width:calc(100% - 32px); max-width:var(--max-width); margin:0 auto}

    /* Header */
    header{position:sticky; top:0; backdrop-filter:blur(6px); background:linear-gradient(180deg, rgba(11,11,11,0.6), rgba(11,11,11,0.3)); border-bottom:1px solid rgba(255,255,255,0.03); z-index:50}
    .nav{display:flex; align-items:center; justify-content:space-between; padding:18px 0}
    .brand{display:flex; gap:12px; align-items:center}
    .brand img{height:44px}
    .brand .title{font-weight:700; letter-spacing:0.2px}
    nav ul{display:flex; gap:20px; list-style:none; margin:0; padding:0}
    nav a{color:var(--muted); text-decoration:none; font-weight:600}
    .cta{background:linear-gradient(90deg,var(--accent), #ff6a2b); padding:10px 16px; border-radius:10px; color:var(--white); font-weight:700; text-decoration:none}

    /* Mobile nav */
    .menu-toggle{display:none; background:transparent; border:0; color:var(--muted); font-size:20px}
    @media(max-width:900px){
      nav ul{display:none}
      .menu-toggle{display:block}
    }

    /* Hero */
    .hero{padding:72px 0 48px; display:grid; grid-template-columns:1fr 420px; gap:40px; align-items:center}
    .hero h1{font-size:42px; margin:0 0 12px; line-height:1.03}
    .hero p{color:var(--muted); margin:0 0 20px}
    .hero .kpis{display:flex; gap:12px; margin-top:18px}
    .kpi{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); padding:12px 14px; border-radius:10px; min-width:110px; text-align:left}
    .kpi .value{font-weight:700}

    /* Right column card */
    .audit-card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:16px; padding:18px; box-shadow:0 6px 20px rgba(0,0,0,0.6); border:1px solid rgba(255,255,255,0.03)}
    .audit-card small{color:var(--muted)}
    .audit-card .btn{display:block; margin-top:14px; text-align:center}

    /* Services */
    .services{padding:36px 0}
    .services-grid{display:grid; grid-template-columns:repeat(3,1fr); gap:18px}
    .service{background:var(--card); padding:18px; border-radius:12px; border:1px solid rgba(255,255,255,0.02)}
    .service h3{margin:0 0 8px}
    .service p{color:var(--muted); margin:0}
    @media(max-width:900px){.services-grid{grid-template-columns:1fr}}

    /* Portfolio */
    .portfolio{padding:36px 0}
    .projects{display:grid; grid-template-columns:repeat(3,1fr); gap:16px}
    .project{position:relative; overflow:hidden; border-radius:12px}
    .project img{width:100%; height:220px; object-fit:cover; display:block; transform:scale(1.03); transition:transform .6s}
    .project:hover img{transform:scale(1.0)}
    .project .overlay{position:absolute; inset:0; display:flex; align-items:flex-end; padding:12px; background:linear-gradient(180deg, transparent, rgba(0,0,0,0.6))}

    @media(max-width:900px){.projects{grid-template-columns:1fr}}

    /* CTA strip */
    .cta-strip{margin:28px 0; padding:22px; border-radius:12px; background:linear-gradient(90deg, rgba(255,69,0,0.06), rgba(255,69,0,0.02)); display:flex; justify-content:space-between; align-items:center}
    .cta-strip .lead{color:var(--white); font-weight:700}

    /* Footer */
    footer{padding:28px 0 48px; color:var(--muted)}
    .footer-grid{display:flex; justify-content:space-between; gap:20px}
    .socials{display:flex; gap:10px}

    /* Forms */
    input, textarea{width:100%; padding:12px; border-radius:10px; border:1px solid rgba(255,255,255,0.04); background:transparent; color:var(--white)}
    label{display:block; margin-bottom:8px; color:var(--muted); font-size:13px}
    .form-row{display:grid; grid-template-columns:1fr 1fr; gap:12px}
    @media(max-width:900px){.form-row{grid-template-columns:1fr}}

    /* Small utility classes */
    .muted{color:var(--muted)}
    .lead{font-size:18px}
    .btn-primary{background:var(--accent); border:none; padding:12px 16px; border-radius:10px; color:var(--white); font-weight:700; cursor:pointer}
    .sr-only{position:absolute; left:-10000px; top:auto; width:1px; height:1px; overflow:hidden}

    /* Smooth fade-in on load */
    .reveal{opacity:0; transform:translateY(10px); transition:opacity .6s ease, transform .6s ease}
    .reveal.visible{opacity:1; transform:none}

  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <!-- TODO: Replace the src with your logo (transparent PNG / SVG recommended) -->
        <img src="/path/to/logo.svg" alt="Clever Digital Agency logo" />
        <div>
          <div class="title">Clever Digital Agency</div>
          <div class="muted" style="font-size:12px">Premium Shopify + eCommerce Engineering</div>
        </div>
      </div>

      <nav aria-label="Primary Navigation">
        <button class="menu-toggle" id="menuToggle" aria-expanded="false">☰</button>
        <ul id="navList">
          <li><a href="#services">Services</a></li>
          <li><a href="#portfolio">Work</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>

      <a class="cta" href="#contact">Get Started</a>
    </div>
  </header>

  <main>
    <section class="container hero" aria-labelledby="home-heading">
      <div>
        <h1 id="home-heading">We build premium Shopify experiences that scale revenue — fast.</h1>
        <p>Design-forward Shopify Plus development, Product Growth Engine™ (PGE), and FLARE™ product audits for high-growth merchants ready to scale. We focus on product-led funnels, visual merchandising, and conversion architecture — not just checkout tricks.</p>

        <div class="kpis">
          <div class="kpi"><div class="value">$1.2M+</div><small class="muted">Revenue generated (sample)</small></div>
          <div class="kpi"><div class="value">+34%</div><small class="muted">Avg CRO uplift</small></div>
          <div class="kpi"><div class="value">24/7</div><small class="muted">Support for clients</small></div>
        </div>

        <p style="margin-top:22px"><a class="btn-primary" href="#contact">Book a FLARE™ Audit</a> <a style="margin-left:12px; color:var(--muted); font-weight:700" href="/portfolio.html">See case studies</a></p>

        <div style="margin-top:20px" class="muted">Trusted by fast-scaling brands — Shopify Experts, Headless implementers, CRO specialists.</div>
      </div>

      <aside class="audit-card reveal" id="auditCard">
        <small class="muted">Free FLARE™ Store Snapshot</small>
        <h3 style="margin:6px 0 0">Instant Product Audit</h3>
        <p class="muted" style="margin-top:8px; font-size:14px">Enter your store URL and get a concise, revenue-focused audit tailored to product merchandising and conversion hooks.</p>

        <!-- NOTE: replace the form action with your server endpoint or a Tally / Typeform link. UTM tracking already supported in script. -->
        <form id="auditForm" action="#" onsubmit="return onAuditSubmit(event)">
          <label for="storeUrl">Store URL</label>
          <input id="storeUrl" name="storeUrl" type="url" placeholder="https://example.myshopify.com" required />
          <div style="display:flex; gap:8px; margin-top:12px">
            <button class="btn-primary" type="submit">Get Snapshot</button>
            <button type="button" class="btn" onclick="openWhatsApp()" style="background:transparent; color:var(--white); border:1px solid rgba(255,255,255,0.04); padding:10px 12px; border-radius:10px">WhatsApp</button>
          </div>
          <p style="margin-top:10px; font-size:13px" class="muted">We won't contact you unless you opt-in. The snapshot is automated and limited to one free audit per store.</p>
        </form>
      </aside>
    </section>

    <section id="services" class="container services">
      <h2>What we do</h2>
      <div class="services-grid">
        <article class="service reveal">
          <h3>Shopify Plus & Headless</h3>
          <p>Custom store builds, headless architectures (Hydrogen, Next.js), and performance-first implementations focused on conversion and scale.</p>
        </article>
        <article class="service reveal">
          <h3>Product Growth Engine™</h3>
          <p>Product-led growth: visual merchandising, pricing experiments, subscriptions, and data-driven catalog strategies.</p>
        </article>
        <article class="service reveal">
          <h3>Conversion Rate Optimization</h3>
          <p>FLARE™ audits, A/B testing strategy, and UI experiments that reliably increase average order value and conversion.</p>
        </article>
      </div>
    </section>

    <section id="portfolio" class="container portfolio">
      <h2>Selected Work</h2>
      <div class="projects">
        <!-- Replace images/links with your real case studies. Use consistent image sizes. -->
        <a class="project" href="#" aria-label="Project 1"><img src="/path/to/project-1.jpg" alt="Project 1 — storefront redesign"><div class="overlay"><div><strong>Brand Name</strong><div class="muted">Headless replatform & CRO</div></div></div></a>
        <a class="project" href="#" aria-label="Project 2"><img src="/path/to/project-2.jpg" alt="Project 2 — visual merchandising"><div class="overlay"><div><strong>Brand Name</strong><div class="muted">Product merchandising redesign</div></div></div></a>
        <a class="project" href="#" aria-label="Project 3"><img src="/path/to/project-3.jpg" alt="Project 3 — subscription model"><div class="overlay"><div><strong>Brand Name</strong><div class="muted">Subscription & retention</div></div></div></a>
      </div>

      <div class="cta-strip" style="margin-top:18px">
        <div>
          <div class="lead">Want a high-converting product page in 14 days?</div>
          <div class="muted">We prioritize product-first funnels that increase purchase intent and average order value.</div>
        </div>
        <div><a class="btn-primary" href="#contact">Start a Project</a></div>
      </div>
    </section>

    <section id="about" class="container" style="padding:28px 0">
      <h2>About Clever Digital Agency</h2>
      <p class="muted">We build premium Shopify experiences for founders who want measurable growth, not vanity metrics. Our approach combines expert Liquid engineering, headless storefronts, product-led conversion architecture, and a relentless focus on revenue. We only take on clients who value long-term, technical excellence and strategic product thinking.</p>
    </section>

    <section id="contact" class="container" style="padding:28px 0 80px">
      <h2>Contact</h2>
      <div style="display:grid; grid-template-columns:1fr 380px; gap:28px">
        <div>
          <form id="contactForm" onsubmit="return onContactSubmit(event)">
            <label for="name">Full name</label>
            <input id="name" name="name" required />
            <label for="email">Email address</label>
            <input id="email" name="email" type="email" required />
            <label for="project">Tell us about your project</label>
            <textarea id="project" name="project" rows="6" placeholder="Budget, timeline, main goals"></textarea>
            <div style="margin-top:12px"><button class="btn-primary" type="submit">Request Proposal</button></div>
          </form>
        </div>

        <aside style="background:var(--card); padding:18px; border-radius:12px; border:1px solid rgba(255,255,255,0.03)">
          <h4 style="margin-top:0">Quick info</h4>
          <p class="muted">If you’re reaching out for a project, include your current monthly revenue, target revenue, and preferred start date. That helps us qualify fit fast.</p>
          <p class="muted">Links:</p>
          <ul class="muted">
            <li><a href="https://cleverdigital.agency" style="color:var(--accent); text-decoration:none">Portfolio</a></li>
            <li><a href="https://www.instagram.com/cleverdigital.agency" style="color:var(--accent); text-decoration:none">Instagram</a></li>
            <li><a href="https://www.fiverr.com/" style="color:var(--accent); text-decoration:none">Fiverr</a></li>
          </ul>
        </aside>
      </div>
    </section>
  </main>

  <footer>
    <div class="container footer-grid">
      <div>
        <div style="font-weight:700">Clever Digital Agency</div>
        <div class="muted" style="font-size:13px">Premium Shopify & eCommerce Engineering</div>
      </div>
      <div class="muted">© <span id="year"></span> Clever Digital Agency — All rights reserved.</div>
      <div>
        <div class="socials">
          <!-- Replace # with your social links -->
          <a href="#" aria-label="Instagram">IG</a>
          <a href="#" aria-label="LinkedIn">LI</a>
        </div>
      </div>
    </div>
  </footer>

  <!-- Scripts: inline for single-file delivery. Move to external script.js in production. -->
  <script>
    // ====== Small client-side interactions & analytics placeholders ======

    // Accessibility: set current year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Mobile menu toggle
    const menuToggle = document.getElementById('menuToggle');
    const navList = document.getElementById('navList');
    if(menuToggle){
      menuToggle.addEventListener('click', ()=>{
        const expanded = menuToggle.getAttribute('aria-expanded') === 'true';
        menuToggle.setAttribute('aria-expanded', String(!expanded));
        if(navList.style.display === 'flex') navList.style.display = 'none'; else navList.style.display = 'flex';
        navList.style.flexDirection = 'column'; navList.style.gap = '14px'; navList.style.alignItems='flex-end';
      })
    }

    // Reveal animations on intersection
    const observer = new IntersectionObserver((entries)=>{
      entries.forEach(e=>{ if(e.isIntersecting) e.target.classList.add('visible'); });
    }, {threshold: 0.12});
    document.querySelectorAll('.reveal').forEach(el=>observer.observe(el));

    // Audit form handler (example: send to serverless endpoint or Tally)
    function onAuditSubmit(e){
      e.preventDefault();
      const url = document.getElementById('storeUrl').value.trim();
      if(!url) return alert('Please enter a store URL');

      // TODO: Replace this with your real endpoint or Tally/typeform link
      // Example: send to /api/audit (serverless) or open a Tally form with UTM params
      console.log('Audit requested for', url);
      alert('Thanks — we received your request. We will email a short snapshot to you. (Replace this alert with real submission code.)');
      return false;
    }

    // Contact form handler
    function onContactSubmit(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      const project = document.getElementById('project').value.trim();
      if(!name || !email) return alert('Please enter your name and email');

      // TODO: Replace with real submission: fetch('/api/contact', {method:'POST', body: JSON.stringify({name,email,project})})
      console.log('Contact submission', {name,email,project});
      alert('Thanks! Your request has been recorded. Replace this with a real submission to your CRM or email webhook.');
      e.target.reset();
      return false;
    }

    // Quick open WhatsApp helper
    function openWhatsApp(){
      // TODO: replace phone number
      const phone = '+1234567890';
      const text = encodeURIComponent('Hi Clever Digital Agency — I need help with my Shopify store');
      const url = `https://wa.me/${phone.replace(/[^\d]/g,'')}?text=${text}`;
      window.open(url, '_blank');
    }

    // Simple form of UTM capture (stores in localStorage)
    (function captureUTM(){
      try{
        const params = new URLSearchParams(location.search);
        ['utm_source','utm_medium','utm_campaign','utm_content','utm_term'].forEach(k=>{
          const v = params.get(k); if(v) localStorage.setItem(k,v);
        });
      }catch(e){console.warn('UTM capture failed', e)}
    })();

    // Placeholder for analytics scripts (Google Analytics, Microsoft Clarity, GTM)
    // NOTE: Add your real script tags here in production. Do not leak keys in public repos.

  </script>
</body>
</html>
