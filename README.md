<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio | Raji Abdulmalik</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- HEADER SECTION -->
  <header class="header">
    <div class="container">
      <!-- Logo / Brand -->
      <div class="logo">Raji<span>Dev</span></div>

      <!-- Navigation -->
      <nav class="nav">
        <ul>
          <li><a href="#home" class="active">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>

      <!-- CTA Button -->
      <a href="https://wa.me/2348149159089" target="_blank" class="cta-btn">Let’s Talk 🚀</a>
    </div>
  </header>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio Hero</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <section class="hero">
    <div class="overlay"></div>
    <div class="hero-content">
      <h1>Transforming E-Commerce Ideas<br>Into Profitable Shopify Stores 🚀</h1>
      <p>I design and build premium, scalable websites that drive growth and conversions.</p>
      <div class="cta-buttons">
        <a href="#portfolio" class="btn primary">View My Work</a>
        <a href="https://wa.me/2348149159089" class="btn secondary">Let’s Talk on WhatsApp</a>
      </div>
    </div>
  </section>
</body>
</html>
/* Reset & Base */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: #0f0f10;
  color: #fff;
}

/* Header */
.header {
  width: 100%;
  padding: 20px 0;
  background: rgba(15, 15, 16, 0.95);
  border-bottom: 1px solid rgba(255, 255, 255, 0.05);
  position: fixed;
  top: 0;
  z-index: 1000;
  backdrop-filter: blur(10px);
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

/* Logo */
.logo {
  font-size: 1.8rem;
  font-weight: 700;
  letter-spacing: 1px;
  color: #fff;
}

.logo span {
  color: #4f8cff;
}

/* Navigation */
.nav ul {
  list-style: none;
  display: flex;
  gap: 2rem;
}

.nav ul li a {
  color: #ccc;
  text-decoration: none;
  font-size: 1rem;
  transition: color 0.3s ease;
}

.nav ul li a:hover,
.nav ul li a.active {
  color: #4f8cff;
}

/* CTA Button */
.cta-btn {
  padding: 10px 22px;
  background: linear-gradient(90deg, #4f8cff, #0077ff);
  color: #fff;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  transition: background 0.3s ease, transform 0.2s ease;
}

.cta-btn:hover {
  background: linear-gradient(90deg, #0077ff, #4f8cff);
  transform: translateY(-2px);
}

/* Responsive */
@media (max-width: 768px) {
  .nav {
    display: none;
  }
  .cta-btn {
    font-size: 0.9rem;
    padding: 8px 18px;
  }
}

/* Global Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  background-color: #0a0a0a;
  color: #f5f5f5;
  line-height: 1.6;
}

/* Hero Section */
.hero {
  position: relative;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  background: linear-gradient(135deg, #0a0a0a, #111);
  overflow: hidden;
}

.overlay {
  position: absolute;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at center, rgba(255,255,255,0.05), transparent 70%);
  pointer-events: none;
}

.hero-content {
  position: relative;
  max-width: 900px;
  padding: 0 20px;
  z-index: 2;
}

.hero h1 {
  font-size: 3rem;
  font-weight: 700;
  background: linear-gradient(90deg, #fff, #999);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.2rem;
  color: #bbb;
  margin-bottom: 40px;
}

/* CTA Buttons */
.cta-buttons {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.btn {
  padding: 12px 28px;
  font-size: 1rem;
  font-weight: 600;
  border-radius: 30px;
  text-decoration: none;
  transition: all 0.3s ease;
}

.btn.primary {
  background: #00c896;
  color: #0a0a0a;
  box-shadow: 0 4px 15px rgba(0,200,150,0.4);
}

.btn.primary:hover {
  background: #00e0ac;
  box-shadow: 0 6px 20px rgba(0,200,150,0.6);
}

.btn.secondary {
  border: 2px solid #f5f5f5;
  color: #f5f5f5;
}

.btn.secondary:hover {
  background: #f5f5f5;
  color: #0a0a0a;
}

