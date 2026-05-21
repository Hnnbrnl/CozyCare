<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CozyCare — Virtual STR Management</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --cream: #FAF7F2;
    --warm-white: #FFFDF9;
    --sand: #EDE8DF;
    --teal: #1A6B5A;
    --teal-light: #2A8A74;
    --teal-pale: #E8F4F1;
    --charcoal: #1C1C1A;
    --gray: #6B6860;
    --gray-light: #9B9890;
    --border: #E0DAD0;
    --accent: #C17B3A;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--cream);
    color: var(--charcoal);
    font-size: 16px;
    line-height: 1.7;
  }

  /* NAV */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    background: rgba(250, 247, 242, 0.95);
    backdrop-filter: blur(8px);
    border-bottom: 1px solid var(--border);
    padding: 0 5%;
    display: flex; align-items: center; justify-content: space-between;
    height: 64px;
  }
  .nav-logo {
    font-family: 'Playfair Display', serif;
    font-size: 22px; font-weight: 600;
    color: var(--teal);
    letter-spacing: -0.3px;
  }
  .nav-logo span { color: var(--accent); }
  .nav-links { display: flex; align-items: center; gap: 32px; }
  .nav-links a {
    font-size: 14px; font-weight: 400; color: var(--gray);
    text-decoration: none; letter-spacing: 0.01em;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--charcoal); }
  .nav-cta {
    background: var(--teal) !important;
    color: #fff !important;
    padding: 8px 20px;
    border-radius: 100px;
    font-weight: 500 !important;
    font-size: 14px !important;
    transition: background 0.2s !important;
  }
  .nav-cta:hover { background: var(--teal-light) !important; }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: flex; flex-direction: column; justify-content: center;
    padding: 100px 5% 80px;
    position: relative; overflow: hidden;
  }
  .hero-bg {
    position: absolute; inset: 0; z-index: 0;
    background: var(--cream);
  }
  .hero-bg-circle {
    position: absolute;
    width: 600px; height: 600px;
    border-radius: 50%;
    background: var(--teal-pale);
    right: -100px; top: -100px;
    opacity: 0.5;
  }
  .hero-bg-dots {
    position: absolute; bottom: 60px; left: 5%;
    width: 200px; height: 200px;
    background-image: radial-gradient(circle, var(--border) 1.5px, transparent 1.5px);
    background-size: 20px 20px;
    opacity: 0.6;
  }
  .hero-inner {
    position: relative; z-index: 1;
    max-width: 780px;
  }
  .hero-eyebrow {
    display: inline-flex; align-items: center; gap: 8px;
    font-size: 12px; font-weight: 500; letter-spacing: 0.12em;
    text-transform: uppercase; color: var(--teal);
    background: var(--teal-pale);
    border: 1px solid rgba(26, 107, 90, 0.2);
    padding: 5px 14px; border-radius: 100px;
    margin-bottom: 28px;
    opacity: 0; animation: fadeUp 0.6s 0.1s forwards;
  }
  .hero-eyebrow::before {
    content: ''; width: 6px; height: 6px;
    background: var(--teal); border-radius: 50%;
  }
  .hero-headline {
    font-family: 'Playfair Display', serif;
    font-size: clamp(38px, 5.5vw, 66px);
    font-weight: 600; line-height: 1.12;
    letter-spacing: -1.5px;
    color: var(--charcoal);
    margin-bottom: 24px;
    opacity: 0; animation: fadeUp 0.6s 0.25s forwards;
  }
  .hero-headline em {
    font-style: italic; color: var(--teal);
  }
  .hero-sub {
    font-size: 18px; font-weight: 300; color: var(--gray);
    max-width: 580px; line-height: 1.7;
    margin-bottom: 40px;
    opacity: 0; animation: fadeUp 0.6s 0.4s forwards;
  }
  .hero-actions {
    display: flex; align-items: center; gap: 16px; flex-wrap: wrap;
    opacity: 0; animation: fadeUp 0.6s 0.55s forwards;
  }
  .btn-primary {
    background: var(--teal);
    color: #fff; border: none;
    padding: 14px 28px; border-radius: 100px;
    font-family: 'DM Sans', sans-serif;
    font-size: 15px; font-weight: 500;
    cursor: pointer; text-decoration: none;
    display: inline-flex; align-items: center; gap: 8px;
    transition: background 0.2s, transform 0.15s;
  }
  .btn-primary:hover { background: var(--teal-light); transform: translateY(-1px); }
  .btn-secondary {
    color: var(--charcoal); font-size: 15px; font-weight: 400;
    text-decoration: none; display: inline-flex; align-items: center; gap: 6px;
    border-bottom: 1px solid var(--border);
    padding-bottom: 2px;
    transition: border-color 0.2s, color 0.2s;
  }
  .btn-secondary:hover { color: var(--teal); border-color: var(--teal); }
  .hero-trust {
    margin-top: 56px; display: flex; align-items: center; gap: 24px; flex-wrap: wrap;
    opacity: 0; animation: fadeUp 0.6s 0.7s forwards;
  }
  .trust-item {
    display: flex; align-items: center; gap: 8px;
    font-size: 13px; color: var(--gray);
  }
  .trust-dot { width: 5px; height: 5px; background: var(--teal); border-radius: 50%; }

  /* TRUST BAR */
  .trust-bar {
    background: var(--teal);
    padding: 28px 5%;
    display: flex; align-items: center; justify-content: center;
    gap: 40px; flex-wrap: wrap;
  }
  .trust-stat { text-align: center; }
  .trust-stat-num {
    font-family: 'Playfair Display', serif;
    font-size: 30px; font-weight: 600; color: #fff;
    display: block; line-height: 1;
  }
  .trust-stat-label {
    font-size: 12px; color: rgba(255,255,255,0.7);
    letter-spacing: 0.06em; text-transform: uppercase;
    margin-top: 4px; display: block;
  }
  .trust-divider { width: 1px; height: 40px; background: rgba(255,255,255,0.2); }

  /* SECTIONS SHARED */
  section { padding: 100px 5%; }
  .section-eyebrow {
    font-size: 11px; font-weight: 500; letter-spacing: 0.14em;
    text-transform: uppercase; color: var(--teal);
    margin-bottom: 14px; display: block;
  }
  .section-headline {
    font-family: 'Playfair Display', serif;
    font-size: clamp(28px, 3.5vw, 42px);
    font-weight: 600; line-height: 1.2;
    letter-spacing: -0.8px; color: var(--charcoal);
    margin-bottom: 16px;
  }
  .section-sub {
    font-size: 17px; font-weight: 300;
    color: var(--gray); max-width: 540px; line-height: 1.7;
  }
  .section-header { margin-bottom: 56px; }

  /* WHO IT'S FOR */
  .audiences { background: var(--warm-white); }
  .audience-grid {
    display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 2px; border: 1px solid var(--border); border-radius: 16px; overflow: hidden;
  }
  .audience-card {
    background: var(--warm-white);
    padding: 36px 32px;
    border-right: 1px solid var(--border);
    transition: background 0.2s;
  }
  .audience-card:last-child { border-right: none; }
  .audience-card:hover { background: var(--teal-pale); }
  .audience-icon {
    width: 44px; height: 44px; border-radius: 12px;
    background: var(--teal-pale); border: 1px solid rgba(26,107,90,0.15);
    display: flex; align-items: center; justify-content: center;
    font-size: 20px; margin-bottom: 20px;
  }
  .audience-title {
    font-family: 'Playfair Display', serif;
    font-size: 19px; font-weight: 600;
    color: var(--charcoal); margin-bottom: 10px;
  }
  .audience-desc { font-size: 14px; color: var(--gray); line-height: 1.65; }

  /* HOW IT WORKS */
  .how { background: var(--cream); }
  .steps { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 0; position: relative; }
  .steps::before {
    content: '';
    position: absolute; top: 28px; left: 10%; right: 10%;
    height: 1px; background: var(--border); z-index: 0;
  }
  .step { text-align: center; padding: 0 24px; position: relative; z-index: 1; }
  .step-num {
    width: 56px; height: 56px; border-radius: 50%;
    background: var(--warm-white);
    border: 2px solid var(--teal);
    display: flex; align-items: center; justify-content: center;
    font-family: 'Playfair Display', serif;
    font-size: 20px; font-weight: 600; color: var(--teal);
    margin: 0 auto 24px;
  }
  .step-title {
    font-size: 16px; font-weight: 500; color: var(--charcoal);
    margin-bottom: 10px;
  }
  .step-desc { font-size: 14px; color: var(--gray); line-height: 1.65; }

  /* SERVICES */
  .services { background: var(--charcoal); }
  .services .section-eyebrow { color: rgba(255,255,255,0.5); }
  .services .section-headline { color: #fff; }
  .services .section-sub { color: rgba(255,255,255,0.5); }
  .services-grid {
    display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1px;
    background: rgba(255,255,255,0.08); border-radius: 16px; overflow: hidden;
  }
  .service-card {
    background: var(--charcoal); padding: 32px 28px;
    border: 1px solid rgba(255,255,255,0.06);
    transition: background 0.2s;
  }
  .service-card:hover { background: rgba(255,255,255,0.04); }
  .service-icon {
    font-size: 26px; margin-bottom: 16px; display: block;
  }
  .service-name {
    font-size: 15px; font-weight: 500; color: #fff;
    margin-bottom: 8px;
  }
  .service-desc { font-size: 13px; color: rgba(255,255,255,0.45); line-height: 1.6; }

  /* TESTIMONIAL */
  .testimonial-section { background: var(--warm-white); }
  .testimonial-card {
    background: var(--cream); border: 1px solid var(--border);
    border-radius: 20px; padding: 48px 52px;
    max-width: 760px; margin: 0 auto;
    position: relative;
  }
  .quote-mark {
    font-family: 'Playfair Display', serif;
    font-size: 100px; line-height: 0.7;
    color: var(--teal); opacity: 0.15;
    position: absolute; top: 32px; left: 40px;
  }
  .quote-text {
    font-family: 'Playfair Display', serif;
    font-size: clamp(18px, 2.5vw, 24px);
    font-weight: 400; font-style: italic;
    color: var(--charcoal); line-height: 1.6;
    margin-bottom: 28px; position: relative;
  }
  .quote-author { font-size: 14px; color: var(--gray); }
  .quote-author strong { color: var(--charcoal); font-weight: 500; }

  /* PRICING */
  .pricing { background: var(--cream); }
  .pricing-cards {
    display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 20px; max-width: 900px;
  }
  .pricing-card {
    background: var(--warm-white); border: 1px solid var(--border);
    border-radius: 20px; padding: 36px 32px;
    transition: transform 0.2s;
  }
  .pricing-card:hover { transform: translateY(-4px); }
  .pricing-card.featured {
    background: var(--teal); border-color: var(--teal);
  }
  .pricing-badge {
    font-size: 11px; font-weight: 500; letter-spacing: 0.1em;
    text-transform: uppercase; background: rgba(255,255,255,0.2);
    color: #fff; padding: 4px 12px; border-radius: 100px;
    display: inline-block; margin-bottom: 20px;
  }
  .pricing-name {
    font-size: 13px; font-weight: 500; letter-spacing: 0.08em;
    text-transform: uppercase; color: var(--gray); margin-bottom: 8px;
  }
  .pricing-card.featured .pricing-name { color: rgba(255,255,255,0.7); }
  .pricing-price {
    font-family: 'Playfair Display', serif;
    font-size: 42px; font-weight: 600; color: var(--charcoal);
    line-height: 1; margin-bottom: 4px;
  }
  .pricing-card.featured .pricing-price { color: #fff; }
  .pricing-period { font-size: 13px; color: var(--gray); margin-bottom: 24px; }
  .pricing-card.featured .pricing-period { color: rgba(255,255,255,0.6); }
  .pricing-features { list-style: none; margin-bottom: 32px; }
  .pricing-features li {
    font-size: 14px; color: var(--gray);
    padding: 8px 0; border-bottom: 1px solid var(--border);
    display: flex; align-items: center; gap: 10px;
  }
  .pricing-card.featured .pricing-features li { color: rgba(255,255,255,0.8); border-color: rgba(255,255,255,0.15); }
  .pricing-features li::before {
    content: '✓'; color: var(--teal); font-weight: 500; font-size: 13px;
  }
  .pricing-card.featured .pricing-features li::before { color: rgba(255,255,255,0.9); }
  .btn-outline {
    display: block; text-align: center;
    border: 1px solid var(--border); border-radius: 100px;
    padding: 12px 24px; font-size: 14px; font-weight: 500;
    color: var(--charcoal); text-decoration: none;
    transition: background 0.2s, border-color 0.2s;
  }
  .btn-outline:hover { background: var(--sand); border-color: var(--gray-light); }
  .btn-white {
    display: block; text-align: center;
    background: #fff; border-radius: 100px;
    padding: 12px 24px; font-size: 14px; font-weight: 500;
    color: var(--teal); text-decoration: none;
    transition: background 0.2s;
  }
  .btn-white:hover { background: var(--cream); }

  /* CTA SECTION */
  .cta-section {
    background: var(--teal-pale);
    border-top: 1px solid rgba(26,107,90,0.15);
    border-bottom: 1px solid rgba(26,107,90,0.15);
    text-align: center; padding: 100px 5%;
  }
  .cta-section .section-headline { margin-bottom: 16px; }
  .cta-section .section-sub { margin: 0 auto 40px; text-align: center; }
  .cta-actions { display: flex; align-items: center; justify-content: center; gap: 16px; flex-wrap: wrap; }
  .btn-whatsapp {
    background: #25D366; color: #fff; border: none;
    padding: 14px 28px; border-radius: 100px;
    font-family: 'DM Sans', sans-serif;
    font-size: 15px; font-weight: 500;
    cursor: pointer; text-decoration: none;
    display: inline-flex; align-items: center; gap: 8px;
    transition: background 0.2s, transform 0.15s;
  }
  .btn-whatsapp:hover { background: #20be5a; transform: translateY(-1px); }
  .cta-note { font-size: 13px; color: var(--gray); margin-top: 20px; }

  /* FOOTER */
  footer {
    background: var(--charcoal); color: rgba(255,255,255,0.5);
    padding: 48px 5%;
    display: flex; align-items: center; justify-content: space-between;
    flex-wrap: wrap; gap: 16px;
  }
  .footer-logo {
    font-family: 'Playfair Display', serif;
    font-size: 20px; font-weight: 600; color: #fff;
  }
  .footer-logo span { color: var(--accent); }
  .footer-tagline { font-size: 13px; margin-top: 4px; }
  .footer-links { display: flex; gap: 24px; }
  .footer-links a { font-size: 13px; color: rgba(255,255,255,0.4); text-decoration: none; transition: color 0.2s; }
  .footer-links a:hover { color: rgba(255,255,255,0.8); }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .reveal {
    opacity: 0; transform: translateY(24px);
    transition: opacity 0.6s, transform 0.6s;
  }
  .reveal.visible { opacity: 1; transform: none; }

  /* CONTACT FORM */
  .contact { background: var(--warm-white); }
  .form-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; max-width: 640px; }
  .form-grid .full { grid-column: 1 / -1; }
  .form-group { display: flex; flex-direction: column; gap: 6px; }
  .form-group label { font-size: 13px; font-weight: 500; color: var(--charcoal); }
  .form-group input, .form-group select, .form-group textarea {
    background: var(--cream); border: 1px solid var(--border);
    border-radius: 10px; padding: 12px 16px;
    font-family: 'DM Sans', sans-serif; font-size: 14px; color: var(--charcoal);
    outline: none; transition: border-color 0.2s;
    -webkit-appearance: none;
  }
  .form-group input:focus, .form-group select:focus, .form-group textarea:focus {
    border-color: var(--teal);
  }
  .form-group textarea { resize: vertical; min-height: 100px; }
  .form-submit {
    margin-top: 8px; background: var(--teal); color: #fff; border: none;
    padding: 14px 36px; border-radius: 100px;
    font-family: 'DM Sans', sans-serif; font-size: 15px; font-weight: 500;
    cursor: pointer; transition: background 0.2s, transform 0.15s;
  }
  .form-submit:hover { background: var(--teal-light); transform: translateY(-1px); }

  /* CALENDLY SECTION */
  .calendly-section { background: var(--cream); padding: 100px 5%; }
  .calendly-section .section-header { margin-bottom: 40px; }
  .calendly-wrap {
    border: 1px solid var(--border); border-radius: 20px;
    overflow: hidden; max-width: 860px;
    background: var(--warm-white);
  }
  .calendly-inline-widget { min-width: 100%; height: 700px; }

  /* OR DIVIDER */
  .or-divider {
    display: flex; align-items: center; gap: 16px;
    max-width: 640px; margin: 40px 0 32px;
    color: var(--gray-light); font-size: 13px;
  }
  .or-divider::before, .or-divider::after {
    content: ''; flex: 1; height: 1px; background: var(--border);
  }

  @media (max-width: 600px) {
    .nav-links { display: none; }
    .form-grid { grid-template-columns: 1fr; }
    .steps::before { display: none; }
    .trust-divider { display: none; }
    .calendly-inline-widget { height: 580px; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">Cozy<span>Care</span></div>
  <div class="nav-links">
    <a href="#services">Services</a>
    <a href="#how">How it works</a>
    <a href="#pricing">Pricing</a>
    <a href="#book">Book a call</a>
    <a href="#contact" class="nav-cta">Get started</a>
  </div>
</nav>

<!-- HERO -->
<section class="hero" id="home">
  <div class="hero-bg">
    <div class="hero-bg-circle"></div>
    <div class="hero-bg-dots"></div>
  </div>
  <div class="hero-inner">
    <div class="hero-eyebrow">Virtual STR Management · Philippines & Worldwide</div>
    <h1 class="hero-headline">
      Why are you still managing<br>
      your rental alone when you<br>
      could be <em>fully booked</em>?
    </h1>
    <p class="hero-sub">
      CozyCare is your dedicated virtual co-host — handling guest communications, cleaning coordination, listing optimization, and maintenance follow-ups so your Airbnb runs smoothly whether you're across town or across the world.
    </p>
    <div class="hero-actions">
      <a href="#book" class="btn-primary">Book a free discovery call →</a>
      <a href="#contact" class="btn-secondary">Send us your details ↓</a>
    </div>
    <div class="hero-trust">
      <div class="trust-item"><div class="trust-dot"></div>No lock-in contracts</div>
      <div class="trust-item"><div class="trust-dot"></div>Transparent fees</div>
      <div class="trust-item"><div class="trust-dot"></div>24/7 guest support</div>
      <div class="trust-item"><div class="trust-dot"></div>Remote-friendly by design</div>
    </div>
  </div>
</section>

<!-- TRUST BAR -->
<div class="trust-bar">
  <div class="trust-stat">
    <span class="trust-stat-num">4.9★</span>
    <span class="trust-stat-label">Average guest rating</span>
  </div>
  <div class="trust-divider"></div>
  <div class="trust-stat">
    <span class="trust-stat-num">78%+</span>
    <span class="trust-stat-label">Avg. occupancy rate</span>
  </div>
  <div class="trust-divider"></div>
  <div class="trust-stat">
    <span class="trust-stat-num">&lt;1 hr</span>
    <span class="trust-stat-label">Guest response time</span>
  </div>
  <div class="trust-divider"></div>
  <div class="trust-stat">
    <span class="trust-stat-num">100%</span>
    <span class="trust-stat-label">Remote capable</span>
  </div>
</div>

<!-- WHO IT'S FOR -->
<section class="audiences" id="about">
  <div class="section-header reveal">
    <span class="section-eyebrow">Who it's for</span>
    <h2 class="section-headline">Built for owners who can't —<br>or don't want to — do it all.</h2>
    <p class="section-sub">Whether you're managing from abroad or just want your time back, CozyCare was made for you.</p>
  </div>
  <div class="audience-grid reveal">
    <div class="audience-card">
      <div class="audience-icon">✈️</div>
      <div class="audience-title">OFWs abroad</div>
      <p class="audience-desc">You bought your condo as a safety net. Now it's sitting empty — or you're managing guests at 2am from another timezone. There's a better way.</p>
    </div>
    <div class="audience-card">
      <div class="audience-icon">🌏</div>
      <div class="audience-title">Expats & foreign investors</div>
      <p class="audience-desc">You invested in Philippine property but navigating local operations, regulations, and platforms from overseas is overwhelming. We handle the ground reality.</p>
    </div>
    <div class="audience-card">
      <div class="audience-icon">🏠</div>
      <div class="audience-title">Local PH owners (1–5 units)</div>
      <p class="audience-desc">You have a property that earns — but managing guest messages, coordinating cleaners, and staying on top of reviews is a second job you didn't sign up for.</p>
    </div>
  </div>
</section>

<!-- HOW IT WORKS -->
<section class="how" id="how">
  <div class="section-header reveal">
    <span class="section-eyebrow">How it works</span>
    <h2 class="section-headline">Up and running in under 2 weeks.</h2>
    <p class="section-sub">A simple, remote-friendly process — no site visit required to get started.</p>
  </div>
  <div class="steps reveal">
    <div class="step">
      <div class="step-num">1</div>
      <div class="step-title">Tell us about your property</div>
      <p class="step-desc">Fill in a short form with your property details. We'll review it and send you a free earnings estimate within 24 hours.</p>
    </div>
    <div class="step">
      <div class="step-num">2</div>
      <div class="step-title">We set everything up</div>
      <p class="step-desc">Listing creation, pricing strategy, platform optimization, and guest communication templates — ready to take bookings in 7–10 days.</p>
    </div>
    <div class="step">
      <div class="step-num">3</div>
      <div class="step-title">We manage, you earn</div>
      <p class="step-desc">We handle guests, coordinate cleaning crews, track maintenance, and send you monthly performance reports — from anywhere in the world.</p>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section class="services" id="services">
  <div class="section-header reveal">
    <span class="section-eyebrow">What's included</span>
    <h2 class="section-headline">Everything your rental needs.<br>Managed virtually.</h2>
    <p class="section-sub">CozyCare is a full virtual co-host service — no task is too small, no hour is off-limits.</p>
  </div>
  <div class="services-grid reveal">
    <div class="service-card">
      <span class="service-icon">💬</span>
      <div class="service-name">Guest communications</div>
      <p class="service-desc">24/7 inquiry responses, pre-arrival messaging, check-in instructions, and post-stay review requests — handled professionally and promptly.</p>
    </div>
    <div class="service-card">
      <span class="service-icon">🧹</span>
      <div class="service-name">Cleaning coordination</div>
      <p class="service-desc">We schedule, brief, and quality-check your cleaning crew between every stay so your property is always guest-ready.</p>
    </div>
    <div class="service-card">
      <span class="service-icon">🔧</span>
      <div class="service-name">Maintenance follow-ups</div>
      <p class="service-desc">When something breaks or needs attention, we coordinate with local technicians or vendors so nothing slips through the cracks.</p>
    </div>
    <div class="service-card">
      <span class="service-icon">📈</span>
      <div class="service-name">Listing optimization</div>
      <p class="service-desc">SEO-tuned titles and descriptions, strategic photo ordering, and platform-specific copy to maximize your visibility and conversion rate.</p>
    </div>
    <div class="service-card">
      <span class="service-icon">💰</span>
      <div class="service-name">Dynamic pricing strategy</div>
      <p class="service-desc">We adjust your nightly rates based on local demand, seasonality, and competitor pricing — so you're never leaving money on the table.</p>
    </div>
    <div class="service-card">
      <span class="service-icon">📊</span>
      <div class="service-name">Monthly owner reports</div>
      <p class="service-desc">Clear monthly summaries of bookings, revenue, occupancy rate, guest feedback, and upcoming calendar — sent directly to your inbox.</p>
    </div>
  </div>
</section>

<!-- TESTIMONIAL -->
<section class="testimonial-section">
  <div class="section-header reveal" style="text-align:center;">
    <span class="section-eyebrow">What owners say</span>
    <h2 class="section-headline">Real results, real owners.</h2>
  </div>
  <div class="testimonial-card reveal">
    <div class="quote-mark">"</div>
    <p class="quote-text">
      "I'm based in Dubai and had no way to manage my BGC condo properly. CozyCare took over everything — guest messages, the cleaning schedule, even a broken aircon unit. My occupancy went from 40% to over 75% in the first two months. I don't have to think about it anymore."
    </p>
    <div class="quote-author">
      <strong>Maria Santos</strong> · OFW based in Dubai, property in BGC, Manila
    </div>
  </div>
</section>

<!-- PRICING -->
<section class="pricing" id="pricing">
  <div class="section-header reveal">
    <span class="section-eyebrow">Pricing</span>
    <h2 class="section-headline">Simple, transparent fees.<br>No surprises.</h2>
    <p class="section-sub">Pick the plan that fits your level of involvement. All plans include a free property assessment to get started.</p>
  </div>
  <div class="pricing-cards reveal">
    <div class="pricing-card">
      <div class="pricing-name">Essential</div>
      <div class="pricing-price">15%</div>
      <div class="pricing-period">of monthly rental revenue</div>
      <ul class="pricing-features">
        <li>Guest communications (24/7)</li>
        <li>Listing optimization</li>
        <li>Cleaning coordination</li>
        <li>Monthly reports</li>
        <li>Review management</li>
      </ul>
      <a href="#contact" class="btn-outline">Get started</a>
    </div>
    <div class="pricing-card featured">
      <div class="pricing-badge">Most popular</div>
      <div class="pricing-name">Full co-host</div>
      <div class="pricing-price">20%</div>
      <div class="pricing-period">of monthly rental revenue</div>
      <ul class="pricing-features">
        <li>Everything in Essential</li>
        <li>Dynamic pricing strategy</li>
        <li>Maintenance coordination</li>
        <li>Multi-platform listing</li>
        <li>Priority owner support</li>
      </ul>
      <a href="#contact" class="btn-white">Get started</a>
    </div>
    <div class="pricing-card">
      <div class="pricing-name">Custom</div>
      <div class="pricing-price">Let's talk</div>
      <div class="pricing-period">for 3+ properties</div>
      <ul class="pricing-features">
        <li>Everything in Full co-host</li>
        <li>Dedicated account manager</li>
        <li>Custom reporting dashboard</li>
        <li>Portfolio-level strategy</li>
        <li>Negotiated rate</li>
      </ul>
      <a href="#contact" class="btn-outline">Contact us</a>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section">
  <div class="reveal">
    <span class="section-eyebrow" style="display:block;text-align:center;">Ready to start?</span>
    <h2 class="section-headline" style="text-align:center;">Stop losing bookings.<br>Start earning more.</h2>
    <p class="section-sub" style="text-align:center;">Get a free property assessment and earnings estimate. No commitment, no pressure — just honest advice on what your property could earn with the right management.</p>
    <div class="cta-actions">
      <a href="#book" class="btn-primary">Book my free discovery call →</a>
      <a href="https://wa.me/639913445533" target="_blank" class="btn-whatsapp">💬 Message on WhatsApp</a>
    </div>
    <p class="cta-note">No lock-in contracts · Cancel anytime with 30 days notice</p>
  </div>
</section>

<!-- CALENDLY BOOKING -->
<section class="calendly-section" id="book">
  <div class="section-header reveal">
    <span class="section-eyebrow">Book a call</span>
    <h2 class="section-headline">Schedule a free discovery call.</h2>
    <p class="section-sub">Pick a time that works for you — wherever you are in the world. The call is 20 minutes, no-obligation, and 100% free.</p>
  </div>
  <div class="calendly-wrap reveal">
    <div class="calendly-inline-widget" data-url="https://calendly.com/hadgbernal/30min?hide_gdpr_banner=1&primary_color=1a6b5a"></div>
  </div>
</section>

<!-- CONTACT FORM -->
<section class="contact" id="contact">
  <div class="section-header reveal">
    <span class="section-eyebrow">Get started</span>
    <h2 class="section-headline">Or tell us about your property.</h2>
    <p class="section-sub">Prefer to write in first? Fill in the form below and we'll get back to you within 24 hours with a free earnings estimate.</p>
  </div>
  <div class="or-divider reveal">Prefer the form instead?</div>
  <div class="reveal">
    <form class="form-grid" action="https://formspree.io/f/hadgbernal@gmail.com" method="POST" onsubmit="handleSubmit(event)">
      <input type="hidden" name="_replyto" value="hadgbernal@gmail.com">
      <input type="hidden" name="_subject" value="New CozyCare property enquiry">
      <div class="form-group">
        <label for="fname">Your name</label>
        <input type="text" id="fname" name="name" placeholder="e.g. Maria Santos" required>
      </div>
      <div class="form-group">
        <label for="email">Email address</label>
        <input type="email" id="email" name="email" placeholder="you@example.com" required>
      </div>
      <div class="form-group">
        <label for="location">Property location</label>
        <input type="text" id="location" name="property_location" placeholder="e.g. BGC, Taguig / Cebu City">
      </div>
      <div class="form-group">
        <label for="units">Number of units</label>
        <select id="units" name="units">
          <option>1 unit</option>
          <option>2 units</option>
          <option>3–5 units</option>
          <option>5+ units</option>
        </select>
      </div>
      <div class="form-group">
        <label for="status">Current status</label>
        <select id="status" name="current_status">
          <option>Not yet listed</option>
          <option>Listed but low occupancy</option>
          <option>Currently managed by me</option>
          <option>Looking to switch managers</option>
        </select>
      </div>
      <div class="form-group">
        <label for="where">Where are you based?</label>
        <input type="text" id="where" name="based_in" placeholder="e.g. Manila / Dubai / Canada">
      </div>
      <div class="form-group full">
        <label for="message">Anything else you'd like us to know?</label>
        <textarea id="message" name="message" placeholder="Tell us about your property, your goals, or any questions you have..."></textarea>
      </div>
      <div class="full">
        <button type="submit" class="form-submit">Send my assessment request →</button>
      </div>
    </form>
    <div id="form-success" style="display:none; margin-top:24px; padding:20px 24px; background:var(--teal-pale); border:1px solid rgba(26,107,90,0.2); border-radius:12px; color:var(--teal); font-size:15px;">
      ✓ Thank you! We'll review your property details and get back to you within 24 hours.
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div>
    <div class="footer-logo">Cozy<span>Care</span></div>
    <div class="footer-tagline">Virtual STR management · Philippines & worldwide</div>
  </div>
  <div class="footer-links">
    <a href="#services">Services</a>
    <a href="#pricing">Pricing</a>
    <a href="#how">How it works</a>
    <a href="#contact">Contact</a>
  </div>
  <div style="font-size:13px;">© 2025 CozyCare. All rights reserved.</div>
</footer>

<script src="https://assets.calendly.com/assets/external/widget.js" async></script>
<script>
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((e, i) => {
      if (e.isIntersecting) {
        setTimeout(() => e.target.classList.add('visible'), i * 80);
        observer.unobserve(e.target);
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(el => observer.observe(el));

  function handleSubmit(e) {
    e.preventDefault();
    const form = e.target;
    const data = new FormData(form);
    fetch(form.action, {
      method: 'POST',
      body: data,
      headers: { 'Accept': 'application/json' }
    }).then(res => {
      if (res.ok) {
        form.style.display = 'none';
        document.querySelector('.or-divider').style.display = 'none';
        document.getElementById('form-success').style.display = 'block';
      } else {
        alert('Something went wrong. Please email us directly at hadgbernal@gmail.com');
      }
    }).catch(() => {
      alert('Something went wrong. Please email us directly at hadgbernal@gmail.com');
    });
  }
</script>
</body>
</html>
