<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
  <title>Maksat Zhaksybaev — Full-Stack Developer & API Architect</title>
  <meta name="description" content="Full-Stack Developer. From concept to production — architecture, frontend, backend and deployment in one ongoing partnership.">
  <meta name="theme-color" content="#141414">
  <meta property="og:title" content="Maksat Zhaksybaev — Full-Stack Developer & API Architect">
  <meta property="og:description" content="Building modern, scalable web applications and clean backend architectures.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <style>
    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

    :root {
      --surface-1: #141414;
      --surface-2: #1a1a1a;
      --surface-3: #222222;
      --surface-card: #1c1c1c;
      --text-primary: #ececec;
      --text-secondary: #a0a0a0;
      --text-tertiary: #666666;
      --accent: #c8ff00;
      --accent-dim: rgba(200, 255, 0, 0.08);
      --border: rgba(255,255,255,0.06);
      --border-hover: rgba(255,255,255,0.12);
      --font: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, sans-serif;
      --ease: cubic-bezier(0.16, 1, 0.3, 1);
      --radius: 20px;
      --container: 1200px;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: var(--font);
      background: var(--surface-1);
      color: var(--text-primary);
      line-height: 1.6;
      overflow-x: hidden;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
    }

    ::selection { background: var(--accent); color: #000; }
    a { color: inherit; text-decoration: none; }
    ul { list-style: none; }

    .container { max-width: var(--container); margin: 0 auto; padding: 0 clamp(20px, 4vw, 48px); }

    /* ========== LOADING SCREEN ========== */
    .loading-overlay {
      position: fixed;
      inset: 0;
      background: var(--surface-1);
      z-index: 9999;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: opacity 0.6s ease 0.2s, visibility 0.6s ease 0.2s;
    }
    .loading-overlay.done { opacity: 0; visibility: hidden; pointer-events: none; }

    .loading-name {
      font-size: clamp(1.5rem, 4vw, 2.5rem);
      font-weight: 700;
      letter-spacing: -0.5px;
      overflow: hidden;
    }

    .loading-name span {
      display: inline-block;
      opacity: 0;
      transform: translateY(100%);
      animation: letterUp 0.5s var(--ease) forwards;
    }

    @keyframes letterUp {
      to { opacity: 1; transform: translateY(0); }
    }

    /* ========== GRAIN OVERLAY ========== */
    .grain {
      position: fixed;
      inset: 0;
      z-index: 500;
      pointer-events: none;
      opacity: 0.035;
      mix-blend-mode: overlay;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.7' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
    }

    /* ========== NAV ========== */
    .nav {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 900;
      padding: 0 clamp(20px, 4vw, 48px);
      height: 72px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      transition: background 0.4s ease, backdrop-filter 0.4s ease;
    }

    .nav.scrolled {
      background: rgba(20, 20, 20, 0.8);
      backdrop-filter: blur(24px);
      -webkit-backdrop-filter: blur(24px);
      border-bottom: 1px solid var(--border);
    }

    .nav-name {
      font-weight: 700;
      font-size: 0.95rem;
      letter-spacing: -0.3px;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .nav-name .full { transition: opacity 0.3s ease; }

    .nav-links {
      display: flex;
      gap: 2rem;
      align-items: center;
    }

    .nav-links a {
      font-size: 0.875rem;
      font-weight: 500;
      color: var(--text-secondary);
      transition: color 0.25s ease;
      position: relative;
      overflow: hidden;
    }

    .nav-links a span {
      display: block;
      transition: transform 0.3s var(--ease);
    }

    .nav-links a:hover span { transform: translateY(-100%); }

    .nav-links a::after {
      content: attr(data-text);
      position: absolute;
      top: 100%;
      left: 0;
      color: var(--text-primary);
      transition: top 0.3s var(--ease);
    }

    .nav-links a:hover::after { top: 0; }
    .nav-links a:hover { color: var(--text-primary); }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      padding: 0.6rem 1.4rem;
      border-radius: 100px;
      font-family: var(--font);
      font-size: 0.875rem;
      font-weight: 600;
      border: none;
      transition: all 0.3s var(--ease);
      position: relative;
      overflow: hidden;
    }

    .btn-solid {
      background: var(--text-primary);
      color: var(--surface-1);
    }

    .btn-solid:hover {
      background: var(--accent);
      color: #000;
      transform: translateY(-1px);
      box-shadow: 0 8px 32px rgba(200, 255, 0, 0.15);
    }

    .btn-outline {
      background: transparent;
      color: var(--text-primary);
      border: 1px solid var(--border-hover);
    }

    .btn-outline:hover {
      border-color: var(--accent);
      background: var(--accent-dim);
    }

    /* Mobile nav */
    .nav-toggle {
      display: none;
      background: none;
      border: none;
      color: var(--text-primary);
      font-size: 1.2rem;
      padding: 8px;
      cursor: pointer;
    }

    .mobile-bar {
      display: none;
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      z-index: 900;
      background: rgba(20, 20, 20, 0.9);
      backdrop-filter: blur(24px);
      -webkit-backdrop-filter: blur(24px);
      border-top: 1px solid var(--border);
      padding: 12px 20px;
      padding-bottom: calc(12px + env(safe-area-inset-bottom));
    }

    .mobile-bar-inner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 8px;
    }

    .mobile-bar a {
      font-size: 0.8rem;
      font-weight: 500;
      color: var(--text-secondary);
      padding: 8px 12px;
      border-radius: 8px;
      transition: all 0.2s ease;
    }

    .mobile-bar a:hover { color: var(--text-primary); background: var(--surface-3); }

    /* ========== HERO ========== */
    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 120px 0 80px;
    }

    .hero-eyebrow {
      font-size: 0.8rem;
      font-weight: 600;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      color: var(--text-tertiary);
      margin-bottom: 2rem;
    }

    .hero-eyebrow span { color: var(--text-secondary); }

    .hero-heading {
      font-size: clamp(2.8rem, 7vw, 5.5rem);
      font-weight: 800;
      line-height: 1.08;
      letter-spacing: -2.5px;
      margin-bottom: 1.5rem;
      max-width: 900px;
    }

    .word-clip {
      display: inline-block;
      overflow: hidden;
      vertical-align: bottom;
    }

    .word-inner {
      display: inline-block;
      transform: translateY(115%);
      animation: wordReveal 0.8s var(--ease) forwards;
    }

    .hero-heading .em {
      color: var(--accent);
      font-style: normal;
    }

    @keyframes wordReveal {
      to { transform: translateY(0); }
    }

    .hero-sub {
      font-size: clamp(1rem, 2vw, 1.2rem);
      color: var(--text-secondary);
      max-width: 580px;
      line-height: 1.7;
      margin-bottom: 2.5rem;
      overflow: hidden;
    }

    .hero-sub .word-inner { animation-delay: 0.6s; }

    .hero-actions {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      opacity: 0;
      animation: fadeIn 0.6s ease 1s forwards;
    }

    @keyframes fadeIn { to { opacity: 1; } }

    /* ========== PROOF BAR ========== */
    .proof-bar {
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
      padding: 18px 0;
      overflow: hidden;
    }

    .proof-track {
      display: flex;
      gap: 3rem;
      animation: scroll-left 35s linear infinite;
      width: max-content;
    }

    .proof-item {
      font-size: 0.85rem;
      font-weight: 500;
      color: var(--text-tertiary);
      white-space: nowrap;
      display: flex;
      align-items: center;
      gap: 1.5rem;
    }

    .proof-item::after {
      content: '';
      width: 4px;
      height: 4px;
      border-radius: 50%;
      background: var(--accent);
      flex-shrink: 0;
    }

    @keyframes scroll-left {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }

    /* ========== SECTION ========== */
    .section { padding: clamp(64px, 10vw, 120px) 0; }

    .section-label {
      font-size: 0.75rem;
      font-weight: 700;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--text-tertiary);
      margin-bottom: 3rem;
    }

    /* ========== PROJECT CARDS ========== */
    .work-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
    }

    .work-card {
      border-radius: var(--radius);
      overflow: hidden;
      transition: transform 0.5s var(--ease);
    }

    .work-card:hover { transform: translateY(-4px); }

    .work-img {
      aspect-ratio: 16 / 10;
      border-radius: var(--radius);
      overflow: hidden;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 3rem;
      transition: all 0.5s var(--ease);
    }

    .work-img[data-palette="lime"]    { background: linear-gradient(135deg, #1a2e05, #0d1a03); }
    .work-img[data-palette="violet"]  { background: linear-gradient(135deg, #1f0a3c, #120524); }
    .work-img[data-palette="blue"]    { background: linear-gradient(135deg, #0a1628, #051020); }
    .work-img[data-palette="orange"]  { background: linear-gradient(135deg, #2a1505, #1a0e03); }
    .work-img[data-palette="teal"]    { background: linear-gradient(135deg, #0a2820, #051a15); }
    .work-img[data-palette="rose"]    { background: linear-gradient(135deg, #2a0a1a, #1a0512); }

    .work-img .icon-display {
      font-size: 4rem;
      opacity: 0.3;
      transition: all 0.5s var(--ease);
    }

    .work-card:hover .icon-display { opacity: 0.6; transform: scale(1.1); }

    .work-img .view-label {
      position: absolute;
      inset: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      opacity: 0;
      transition: opacity 0.4s ease;
      font-size: 0.9rem;
      font-weight: 600;
      background: rgba(0,0,0,0.4);
      backdrop-filter: blur(4px);
      color: var(--accent);
    }

    .work-card:hover .view-label { opacity: 1; }

    .work-body { padding: 1.25rem 0.25rem; }

    .work-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.4rem;
      margin-bottom: 0.75rem;
    }

    .tag {
      font-size: 0.7rem;
      font-weight: 600;
      letter-spacing: 0.5px;
      padding: 4px 10px;
      border-radius: 100px;
      background: var(--surface-3);
      color: var(--text-secondary);
    }

    .work-title {
      font-size: 1.15rem;
      font-weight: 700;
      line-height: 1.4;
      letter-spacing: -0.3px;
    }

    .work-title-suffix {
      color: var(--text-tertiary);
      font-weight: 400;
    }

    /* ========== HOW I WORK / PRINCIPLES STACK ========== */
    .principles { padding: clamp(64px, 10vw, 120px) 0; }

    .principles-header {
      display: flex;
      align-items: center;
      gap: 1rem;
      margin-bottom: 3rem;
    }

    .principles-label {
      font-size: 0.75rem;
      font-weight: 700;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--text-tertiary);
    }

    .principles-num {
      font-size: 0.75rem;
      font-weight: 700;
      color: var(--accent);
      font-variant-numeric: tabular-nums;
    }

    .principle-card {
      background: var(--surface-card);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: clamp(2rem, 5vw, 3.5rem);
      margin-bottom: 1.5rem;
      transition: all 0.4s var(--ease);
    }

    .principle-card:hover {
      border-color: var(--border-hover);
      transform: translateY(-2px);
    }

    .principle-title {
      font-size: clamp(1.4rem, 3vw, 2rem);
      font-weight: 800;
      letter-spacing: -1px;
      line-height: 1.3;
      margin-bottom: 1rem;
    }

    .principle-body {
      font-size: 1rem;
      color: var(--text-secondary);
      line-height: 1.7;
      max-width: 700px;
    }

    /* ========== EXPERIENCE ========== */
    .exp-list { display: flex; flex-direction: column; gap: 0; }

    .exp-item {
      display: grid;
      grid-template-columns: 200px 1fr;
      gap: 2rem;
      padding: 2rem 0;
      border-bottom: 1px solid var(--border);
      transition: all 0.3s ease;
    }

    .exp-item:first-child { border-top: 1px solid var(--border); }

    .exp-item:hover { background: var(--accent-dim); margin: 0 -24px; padding: 2rem 24px; border-radius: 12px; }

    .exp-date {
      font-size: 0.8rem;
      font-weight: 600;
      color: var(--text-tertiary);
      letter-spacing: 0.5px;
      padding-top: 4px;
    }

    .exp-content h3 {
      font-size: 1.2rem;
      font-weight: 700;
      letter-spacing: -0.3px;
      margin-bottom: 0.2rem;
    }

    .exp-role {
      font-size: 0.9rem;
      color: var(--text-secondary);
      margin-bottom: 1rem;
    }

    .exp-bullets { display: flex; flex-direction: column; gap: 0.4rem; }

    .exp-bullets li {
      font-size: 0.88rem;
      color: var(--text-secondary);
      line-height: 1.6;
      padding-left: 1rem;
      position: relative;
    }

    .exp-bullets li::before {
      content: '›';
      position: absolute;
      left: 0;
      color: var(--accent);
      font-weight: 700;
    }

    /* ========== SKILLS ========== */
    .skills-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-bottom: 2rem;
    }

    .skill-chip {
      font-size: 0.85rem;
      font-weight: 500;
      padding: 0.5rem 1.1rem;
      border-radius: 100px;
      border: 1px solid var(--border);
      background: var(--surface-2);
      color: var(--text-secondary);
      transition: all 0.3s ease;
    }

    .skill-chip:hover {
      border-color: var(--accent);
      color: var(--accent);
      background: var(--accent-dim);
      transform: translateY(-2px);
    }

    .skill-group-title {
      font-size: 0.7rem;
      font-weight: 700;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--text-tertiary);
      margin-bottom: 0.75rem;
      margin-top: 1.5rem;
    }

    .skill-group-title:first-child { margin-top: 0; }

    /* ========== CTA ========== */
    .cta-section {
      padding: clamp(80px, 12vw, 160px) 0;
      text-align: center;
    }

    .cta-heading {
      font-size: clamp(2.5rem, 6vw, 4.5rem);
      font-weight: 800;
      letter-spacing: -2px;
      line-height: 1.1;
      margin-bottom: 1.5rem;
    }

    .cta-heading .em { color: var(--accent); font-style: normal; }

    .cta-sub {
      font-size: 1.1rem;
      color: var(--text-secondary);
      max-width: 480px;
      margin: 0 auto 2.5rem;
      line-height: 1.7;
    }

    .cta-actions {
      display: flex;
      justify-content: center;
      gap: 1rem;
      flex-wrap: wrap;
      margin-bottom: 3rem;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 1rem;
    }

    .social-link {
      width: 48px;
      height: 48px;
      border-radius: 50%;
      border: 1px solid var(--border);
      display: flex;
      align-items: center;
      justify-content: center;
      color: var(--text-tertiary);
      font-size: 1rem;
      transition: all 0.3s ease;
    }

    .social-link:hover {
      border-color: var(--accent);
      color: var(--accent);
      transform: translateY(-3px);
      box-shadow: 0 8px 24px rgba(200, 255, 0, 0.1);
    }

    /* ========== FOOTER ========== */
    .footer {
      padding: 2rem 0;
      border-top: 1px solid var(--border);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .footer-text { font-size: 0.8rem; color: var(--text-tertiary); }
    .footer-text a { color: var(--text-secondary); transition: color 0.2s ease; }
    .footer-text a:hover { color: var(--accent); }

    .footer-right {
      display: flex;
      gap: 1.5rem;
    }

    .footer-right a {
      font-size: 0.8rem;
      color: var(--text-tertiary);
      transition: color 0.2s ease;
    }

    .footer-right a:hover { color: var(--text-primary); }

    /* ========== SCROLL REVEAL ========== */
    .sr {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s var(--ease), transform 0.7s var(--ease);
    }

    .sr.visible { opacity: 1; transform: translateY(0); }
    .sr-slow { transition-duration: 1s; }
    .sr-d1 { transition-delay: 0.1s; }
    .sr-d2 { transition-delay: 0.2s; }
    .sr-d3 { transition-delay: 0.3s; }

    /* ========== RESPONSIVE ========== */
    @media (max-width: 768px) {
      .nav-links { display: none; }
      .nav-toggle { display: block; }
      .mobile-bar { display: block; }

      body { padding-bottom: 72px; }

      .hero { min-height: calc(100vh - 72px); padding: 100px 0 60px; }
      .hero-heading { letter-spacing: -1.5px; }

      .work-grid { grid-template-columns: 1fr; }

      .exp-item {
        grid-template-columns: 1fr;
        gap: 0.5rem;
      }

      .footer { flex-direction: column; gap: 1rem; text-align: center; }
      .hero-actions { flex-direction: column; }
      .hero-actions .btn { width: 100%; justify-content: center; }

      .cta-actions { flex-direction: column; align-items: center; }
    }

    /* Mobile menu overlay */
    .mobile-overlay {
      position: fixed;
      inset: 0;
      z-index: 950;
      background: rgba(20, 20, 20, 0.97);
      backdrop-filter: blur(30px);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 2rem;
      opacity: 0;
      visibility: hidden;
      transition: all 0.4s var(--ease);
    }

    .mobile-overlay.open { opacity: 1; visibility: visible; }

    .mobile-overlay a {
      font-size: 1.8rem;
      font-weight: 700;
      color: var(--text-secondary);
      transition: color 0.2s ease;
    }

    .mobile-overlay a:hover { color: var(--accent); }
  </style>
</head>
<body>
  <!-- Loading -->
  <div class="loading-overlay" id="loader">
    <div class="loading-name" id="loadingName"></div>
  </div>

  <!-- Grain -->
  <div class="grain"></div>

  <!-- Nav -->
  <nav class="nav" id="nav">
    <a href="#" class="nav-name">
      <span>M</span><span class="full">aksat Zhaksybaev</span>
    </a>
    <div class="nav-links">
      <a href="#work" data-text="Work"><span>Work</span></a>
      <a href="#about" data-text="About"><span>About</span></a>
      <a href="#experience" data-text="Experience"><span>Experience</span></a>
      <a href="#skills" data-text="Skills"><span>Skills</span></a>
      <a href="#contact" class="btn btn-solid">Contact <i class="fa-solid fa-arrow-right" style="font-size:0.75rem"></i></a>
    </div>
    <button class="nav-toggle" id="navToggle" aria-label="Open menu"><i class="fa-solid fa-bars"></i></button>
  </nav>

  <!-- Mobile overlay -->
  <div class="mobile-overlay" id="mobileOverlay">
    <a href="#" onclick="closeMobile()">Home</a>
    <a href="#work" onclick="closeMobile()">Work</a>
    <a href="#about" onclick="closeMobile()">About</a>
    <a href="#experience" onclick="closeMobile()">Experience</a>
    <a href="#skills" onclick="closeMobile()">Skills</a>
    <a href="#contact" onclick="closeMobile()">Contact</a>
  </div>

  <!-- Mobile bar -->
  <div class="mobile-bar">
    <div class="mobile-bar-inner">
      <a href="#work">Work</a>
      <a href="#about">About</a>
      <a href="#experience">Exp</a>
      <a href="#skills">Skills</a>
      <a href="#contact" class="btn btn-solid" style="padding:6px 16px;font-size:0.8rem">Contact <i class="fa-solid fa-arrow-right" style="font-size:0.65rem"></i></a>
    </div>
  </div>

  <main id="main-content">
    <!-- Hero -->
    <section class="hero">
      <div class="container">
        <p class="hero-eyebrow">
          <span>Full-Stack Developer</span> · API Architect
        </p>
        <h1 class="hero-heading" id="heroHeading"></h1>
        <p class="hero-sub" id="heroSub"></p>
        <div class="hero-actions">
          <a href="#contact" class="btn btn-solid">Get in touch <i class="fa-solid fa-arrow-right" style="font-size:0.75rem"></i></a>
          <a href="#work" class="btn btn-outline">View my work <i class="fa-solid fa-arrow-down" style="font-size:0.75rem"></i></a>
        </div>
      </div>
    </section>

    <!-- Proof bar -->
    <div class="proof-bar" aria-hidden="true">
      <div class="proof-track">
        <div class="proof-item">3+ Years of Experience</div>
        <div class="proof-item">Next.js · React · TypeScript</div>
        <div class="proof-item">FastAPI · Node.js · Python</div>
        <div class="proof-item">150+ Automated Tests Shipped</div>
        <div class="proof-item">AI-Powered Applications</div>
        <div class="proof-item">Scalable Backend Architectures</div>
        <div class="proof-item">3+ Years of Experience</div>
        <div class="proof-item">Next.js · React · TypeScript</div>
        <div class="proof-item">FastAPI · Node.js · Python</div>
        <div class="proof-item">150+ Automated Tests Shipped</div>
        <div class="proof-item">AI-Powered Applications</div>
        <div class="proof-item">Scalable Backend Architectures</div>
      </div>
    </div>

    <!-- Selected Work -->
    <section class="section" id="work">
      <div class="container">
        <p class="section-label sr">Selected Work</p>
        <div class="work-grid">

          <div class="sr sr-slow">
            <a href="https://github.com/themaksat/UniWork" target="_blank" rel="noopener" class="work-card">
              <div class="work-img" data-palette="lime">
                <i class="fa-solid fa-graduation-cap icon-display"></i>
                <div class="view-label">View on GitHub →</div>
              </div>
              <div class="work-body">
                <div class="work-tags">
                  <span class="tag">TypeScript</span>
                  <span class="tag">Full-Stack</span>
                  <span class="tag">Next.js</span>
                </div>
                <h3 class="work-title">University workspace platform for students & educators<span class="work-title-suffix"> — modern learning tools in one place.</span></h3>
              </div>
            </a>
          </div>

          <div class="sr sr-slow sr-d1">
            <a href="https://github.com/themaksat/rewindos" target="_blank" rel="noopener" class="work-card">
              <div class="work-img" data-palette="violet">
                <i class="fa-solid fa-clock-rotate-left icon-display"></i>
                <div class="view-label">View on GitHub →</div>
              </div>
              <div class="work-body">
                <div class="work-tags">
                  <span class="tag">TypeScript</span>
                  <span class="tag">SQLite</span>
                  <span class="tag">AI Agents</span>
                  <span class="tag">DevTools</span>
                </div>
                <h3 class="work-title">Git for your entire computer session<span class="work-title-suffix"> — time-travel execution engine & instant rollback for developers.</span></h3>
              </div>
            </a>
          </div>

          <div class="sr sr-slow">
            <a href="https://github.com/themaksat/agentguard" target="_blank" rel="noopener" class="work-card">
              <div class="work-img" data-palette="blue">
                <i class="fa-solid fa-shield-halved icon-display"></i>
                <div class="view-label">View on GitHub →</div>
              </div>
              <div class="work-body">
                <div class="work-tags">
                  <span class="tag">Python</span>
                  <span class="tag">Security</span>
                  <span class="tag">AI Safety</span>
                </div>
                <h3 class="work-title">Security toolkit for AI agent systems<span class="work-title-suffix"> — safe, controlled execution in production.</span></h3>
              </div>
            </a>
          </div>

          <div class="sr sr-slow sr-d1">
            <a href="https://github.com/themaksat/DigitalMarketplace_" target="_blank" rel="noopener" class="work-card">
              <div class="work-img" data-palette="orange">
                <i class="fa-solid fa-store icon-display"></i>
                <div class="view-label">View on GitHub →</div>
              </div>
              <div class="work-body">
                <div class="work-tags">
                  <span class="tag">TypeScript</span>
                  <span class="tag">E-Commerce</span>
                  <span class="tag">Payments</span>
                </div>
                <h3 class="work-title">Full-featured digital marketplace<span class="work-title-suffix"> — payments, user accounts & admin dashboard.</span></h3>
              </div>
            </a>
          </div>

          <div class="sr sr-slow">
            <a href="https://github.com/themaksat/THE_FINANCE_BOT" target="_blank" rel="noopener" class="work-card">
              <div class="work-img" data-palette="teal">
                <i class="fa-solid fa-chart-line icon-display"></i>
                <div class="view-label">View on GitHub →</div>
              </div>
              <div class="work-body">
                <div class="work-tags">
                  <span class="tag">Python</span>
                  <span class="tag">Automation</span>
                  <span class="tag">Finance</span>
                </div>
                <h3 class="work-title">Financial assistant bot<span class="work-title-suffix"> — budget tracking & intelligent recommendations.</span></h3>
              </div>
            </a>
          </div>

          <div class="sr sr-slow sr-d1">
            <a href="https://github.com/themaksat/collaborative-todo" target="_blank" rel="noopener" class="work-card">
              <div class="work-img" data-palette="rose">
                <i class="fa-solid fa-users icon-display"></i>
                <div class="view-label">View on GitHub →</div>
              </div>
              <div class="work-body">
                <div class="work-tags">
                  <span class="tag">TypeScript</span>
                  <span class="tag">Real-time</span>
                  <span class="tag">Collaboration</span>
                </div>
                <h3 class="work-title">Real-time collaborative task manager<span class="work-title-suffix"> — live sync & intelligent prioritization.</span></h3>
              </div>
            </a>
          </div>

        </div>
      </div>
    </section>

    <!-- How I Work -->
    <section class="principles" id="about">
      <div class="container">
        <div class="principles-header sr">
          <p class="principles-label">How I work</p>
        </div>

        <div class="principle-card sr">
          <h3 class="principle-title">I start with the business, not the deliverables.</h3>
          <p class="principle-body">I get under the skin of your goals, your users, and what success looks like before deciding what needs to be built. Architecture, tech stack, and implementation follow purpose — not the other way around.</p>
        </div>

        <div class="principle-card sr">
          <h3 class="principle-title">You'll always know what's happening and why.</h3>
          <p class="principle-body">Structured updates and regular check-ins — no surprises, just clear progress. From sprint planning to deployment, I keep communication transparent and async-friendly.</p>
        </div>

        <div class="principle-card sr">
          <h3 class="principle-title">I build for scale, not just for launch.</h3>
          <p class="principle-body">Clean architecture, comprehensive testing (150+ automated tests on my last project), CI/CD pipelines, and documentation that makes handoff seamless. Your codebase should be an asset, not a liability.</p>
        </div>

        <div class="principle-card sr">
          <h3 class="principle-title">Full-stack means full ownership.</h3>
          <p class="principle-body">Frontend, backend, databases, DevOps, AI integrations — I handle the entire stack so you don't need to coordinate between five different specialists. One person, one vision, shipped end-to-end.</p>
        </div>
      </div>
    </section>

    <!-- Experience -->
    <section class="section" id="experience">
      <div class="container">
        <p class="section-label sr">Experience</p>
        <div class="exp-list">

          <div class="exp-item sr">
            <div class="exp-date">Jun 2026 — Present</div>
            <div class="exp-content">
              <h3>Mentorme</h3>
              <p class="exp-role">Full-Stack Developer · Taraz</p>
              <ul class="exp-bullets">
                <li>Architected end-to-end AI study workspace with Next.js 15, FastAPI, and MongoDB</li>
                <li>Built responsive UI — Notion-style editor, seekable audio player, Apple-inspired design system</li>
                <li>Developed async multimodal ingestion engine (PDFs, YouTube, OpenAI Whisper)</li>
                <li>Implemented RAG tutoring system with FSRS spaced repetition algorithm</li>
                <li>Achieved 100% test pass rate across 150+ automated tests (Pytest + Playwright)</li>
              </ul>
            </div>
          </div>

          <div class="exp-item sr">
            <div class="exp-date">Feb 2025 — Present</div>
            <div class="exp-content">
              <h3>Freelance</h3>
              <p class="exp-role">Full-Stack Developer</p>
              <ul class="exp-bullets">
                <li>Full-cycle web apps: TypeScript, React, Next.js, Node.js, Express, FastAPI</li>
                <li>REST/GraphQL APIs with JWT, OAuth authentication systems</li>
                <li>Docker & GitHub Actions CI/CD, deployed on VPS / Vercel / Railway</li>
                <li>Built Telegram bots & AI assistants with multilingual support</li>
              </ul>
            </div>
          </div>

          <div class="exp-item sr">
            <div class="exp-date">Jul 2024 — Feb 2025</div>
            <div class="exp-content">
              <h3>Daniar</h3>
              <p class="exp-role">Frontend Developer</p>
              <ul class="exp-bullets">
                <li>Corporate web interfaces with React, Next.js, TypeScript</li>
                <li>Responsive design with Tailwind CSS, Core Web Vitals optimization</li>
                <li>UI/UX collaboration with Figma, component design systems</li>
              </ul>
            </div>
          </div>

          <div class="exp-item sr">
            <div class="exp-date">Jan 2023 — Jun 2024</div>
            <div class="exp-content">
              <h3>MetaStudy</h3>
              <p class="exp-role">Frontend Developer</p>
              <ul class="exp-bullets">
                <li>Educational platform UI with React.js, TypeScript, Tailwind CSS</li>
                <li>REST & GraphQL API integration, state management with Zustand</li>
                <li>Jest & Playwright testing — reduced production bugs by 30%</li>
              </ul>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- Skills -->
    <section class="section" id="skills">
      <div class="container">
        <p class="section-label sr">Tech Stack</p>

        <div class="sr">
          <p class="skill-group-title">Frontend</p>
          <div class="skills-row">
            <span class="skill-chip">TypeScript</span>
            <span class="skill-chip">React</span>
            <span class="skill-chip">Next.js</span>
            <span class="skill-chip">Vue 3</span>
            <span class="skill-chip">Tailwind CSS</span>
            <span class="skill-chip">JavaScript</span>
            <span class="skill-chip">HTML5</span>
            <span class="skill-chip">CSS3</span>
          </div>
        </div>

        <div class="sr">
          <p class="skill-group-title">Backend</p>
          <div class="skills-row">
            <span class="skill-chip">Node.js</span>
            <span class="skill-chip">Express</span>
            <span class="skill-chip">FastAPI</span>
            <span class="skill-chip">Python</span>
            <span class="skill-chip">REST APIs</span>
            <span class="skill-chip">GraphQL</span>
            <span class="skill-chip">JWT / OAuth</span>
          </div>
        </div>

        <div class="sr">
          <p class="skill-group-title">Databases</p>
          <div class="skills-row">
            <span class="skill-chip">PostgreSQL</span>
            <span class="skill-chip">MongoDB</span>
            <span class="skill-chip">MySQL</span>
            <span class="skill-chip">SQLite</span>
            <span class="skill-chip">Drizzle ORM</span>
            <span class="skill-chip">Prisma</span>
          </div>
        </div>

        <div class="sr">
          <p class="skill-group-title">DevOps & Tools</p>
          <div class="skills-row">
            <span class="skill-chip">Docker</span>
            <span class="skill-chip">GitHub Actions</span>
            <span class="skill-chip">Vercel</span>
            <span class="skill-chip">Linux</span>
            <span class="skill-chip">Git</span>
            <span class="skill-chip">Figma</span>
            <span class="skill-chip">n8n</span>
          </div>
        </div>

        <div class="sr">
          <p class="skill-group-title">AI & Testing</p>
          <div class="skills-row">
            <span class="skill-chip">OpenAI API</span>
            <span class="skill-chip">LLM Orchestration</span>
            <span class="skill-chip">RAG Systems</span>
            <span class="skill-chip">Whisper</span>
            <span class="skill-chip">Pytest</span>
            <span class="skill-chip">Playwright</span>
            <span class="skill-chip">Jest</span>
          </div>
        </div>

      </div>
    </section>

    <!-- Contact CTA -->
    <section class="cta-section" id="contact">
      <div class="container">
        <h2 class="cta-heading sr">Let's build<br>something <em class="em">great.</em></h2>
        <p class="cta-sub sr sr-d1">I'm open to new opportunities, freelance projects, or collaborations. Let's talk about what we can create together.</p>
        <div class="cta-actions sr sr-d2">
          <a href="mailto:maksatzaksybaev0@gmail.com" class="btn btn-solid">
            <i class="fa-solid fa-envelope"></i> Say hello
          </a>
          <a href="https://github.com/themaksat" target="_blank" rel="noopener" class="btn btn-outline">
            <i class="fa-brands fa-github"></i> GitHub
          </a>
        </div>
        <div class="social-links sr sr-d3">
          <a href="https://github.com/themaksat" target="_blank" rel="noopener" class="social-link" aria-label="GitHub"><i class="fa-brands fa-github"></i></a>
          <a href="https://linkedin.com/in/maksat-zhaksybaev" target="_blank" rel="noopener" class="social-link" aria-label="LinkedIn"><i class="fa-brands fa-linkedin-in"></i></a>
          <a href="https://x.com/Maksatxz" target="_blank" rel="noopener" class="social-link" aria-label="X"><i class="fa-brands fa-x-twitter"></i></a>
          <a href="mailto:maksatzaksybaev0@gmail.com" class="social-link" aria-label="Email"><i class="fa-solid fa-envelope"></i></a>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div class="footer">
          <p class="footer-text">© 2026 <a href="#">Maksat Zhaksybaev</a>. Built with care.</p>
          <div class="footer-right">
            <a href="https://github.com/themaksat" target="_blank" rel="noopener">GitHub</a>
            <a href="https://linkedin.com/in/maksat-zhaksybaev" target="_blank" rel="noopener">LinkedIn</a>
            <a href="https://x.com/Maksatxz" target="_blank" rel="noopener">X</a>
          </div>
        </div>
      </div>
    </footer>
  </main>

  <script>
    /* ========== LOADING SCREEN ========== */
    const name = 'maksat zhaksybaev';
    const loadingEl = document.getElementById('loadingName');
    name.split('').forEach((ch, i) => {
      const span = document.createElement('span');
      span.textContent = ch === ' ' ? '\u00A0' : ch;
      span.style.animationDelay = `${i * 40 + 200}ms`;
      loadingEl.appendChild(span);
    });
    setTimeout(() => document.getElementById('loader').classList.add('done'), 1800);

    /* ========== HERO TEXT REVEAL ========== */
    function buildWordReveal(el, text, baseDelay) {
      const words = text.split(' ');
      words.forEach((word, i) => {
        const clip = document.createElement('span');
        clip.className = 'word-clip';
        const inner = document.createElement('span');
        inner.className = 'word-inner';
        inner.textContent = word;
        inner.style.animationDelay = `${baseDelay + i * 60}ms`;
        clip.appendChild(inner);
        el.appendChild(clip);
        if (i < words.length - 1) el.appendChild(document.createTextNode(' '));
      });
    }

    const heading = document.getElementById('heroHeading');
    const lines = ['I build scalable', 'web apps, not just', 'ship them.'];
    lines.forEach((line, li) => {
      const lineSpan = document.createElement('span');
      lineSpan.style.display = 'block';
      const words = line.split(' ');
      words.forEach((word, wi) => {
        const clip = document.createElement('span');
        clip.className = 'word-clip';
        const inner = document.createElement('span');
        inner.className = 'word-inner';
        if (word === 'scalable') {
          const em = document.createElement('em');
          em.className = 'em';
          em.textContent = word;
          inner.appendChild(em);
        } else {
          inner.textContent = word;
        }
        inner.style.animationDelay = `${400 + li * 200 + wi * 70}ms`;
        clip.appendChild(inner);
        lineSpan.appendChild(clip);
        if (wi < words.length - 1) lineSpan.appendChild(document.createTextNode(' '));
      });
      heading.appendChild(lineSpan);
    });

    buildWordReveal(
      document.getElementById('heroSub'),
      'From concept to production — architecture, frontend, backend and deployment in one ongoing partnership.',
      800
    );

    /* ========== NAV SCROLL ========== */
    const nav = document.getElementById('nav');
    window.addEventListener('scroll', () => {
      nav.classList.toggle('scrolled', window.scrollY > 60);
    });

    /* ========== MOBILE MENU ========== */
    const toggle = document.getElementById('navToggle');
    const overlay = document.getElementById('mobileOverlay');
    let menuOpen = false;

    toggle.addEventListener('click', () => {
      menuOpen = !menuOpen;
      overlay.classList.toggle('open', menuOpen);
      toggle.innerHTML = menuOpen ? '<i class="fa-solid fa-xmark"></i>' : '<i class="fa-solid fa-bars"></i>';
      document.body.style.overflow = menuOpen ? 'hidden' : '';
    });

    function closeMobile() {
      menuOpen = false;
      overlay.classList.remove('open');
      toggle.innerHTML = '<i class="fa-solid fa-bars"></i>';
      document.body.style.overflow = '';
    }

    /* ========== SCROLL REVEAL ========== */
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          e.target.classList.add('visible');
          observer.unobserve(e.target);
        }
      });
    }, { threshold: 0.1, rootMargin: '0px 0px -40px 0px' });

    document.querySelectorAll('.sr').forEach(el => observer.observe(el));

    /* ========== SMOOTH SCROLL ========== */
    document.querySelectorAll('a[href^="#"]').forEach(a => {
      a.addEventListener('click', e => {
        e.preventDefault();
        const target = document.querySelector(a.getAttribute('href'));
        if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
      });
    });
  </script>
</body>
</html>
