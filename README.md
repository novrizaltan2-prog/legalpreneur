<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LegalPreneur — Advokat & Konsultan Hukum Digital</title>
<meta name="description" content="LegalPreneur oleh Novrizal, S.I.Kom., S.H., CPM — Advokat & Konsultan Hukum, Mediator, dan platform literasi hukum digital terpercaya.">

<!-- ═══ OPEN GRAPH (WhatsApp, Facebook, Telegram, dll) ═══ -->
<meta id="og-title"       property="og:title"       content="LegalPreneur — Advokat & Konsultan Hukum Digital">
<meta id="og-description" property="og:description" content="LegalPreneur oleh Novrizal, S.I.Kom., S.H., CPM — Advokat & Konsultan Hukum, Mediator, dan platform literasi hukum digital terpercaya.">
<meta id="og-image"       property="og:image"       content="https://novrizaltan2-prog.github.io/legalpreneur/og-default.png">
<meta id="og-image-w"     property="og:image:width"  content="1200">
<meta id="og-image-h"     property="og:image:height" content="630">
<meta id="og-url"         property="og:url"          content="">
<meta                     property="og:type"          content="article">
<meta                     property="og:site_name"     content="LegalPreneur">
<meta                     property="og:locale"        content="id_ID">
<!-- ═══ TWITTER / X CARD ═══ -->
<meta id="tw-card"        name="twitter:card"        content="summary_large_image">
<meta id="tw-title"       name="twitter:title"       content="LegalPreneur — Advokat & Konsultan Hukum Digital">
<meta id="tw-description" name="twitter:description" content="LegalPreneur oleh Novrizal, S.I.Kom., S.H., CPM — Advokat & Konsultan Hukum, Mediator, dan platform literasi hukum digital terpercaya.">
<meta id="tw-image"       name="twitter:image"       content="https://novrizaltan2-prog.github.io/legalpreneur/og-default.png">
<meta                     name="twitter:site"        content="@Novriz_Tan">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;0,900;1,400;1,600&family=Crimson+Pro:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400&family=DM+Mono:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">

<style>
:root {
  --ink: #0f0e0b;
  --ink-2: #2a2720;
  --ink-3: #5c5749;
  --cream: #f5f0e8;
  --cream-2: #ede6d6;
  --cream-3: #e0d6c2;
  --gold: #b8973a;
  --gold-light: #d4b05a;
  --gold-pale: #f0e4c0;
  --white: #fdfcf9;
  --border: rgba(184,151,58,0.25);
  --border-light: rgba(92,87,73,0.15);
  --shadow: 0 4px 24px rgba(15,14,11,0.08);
  --shadow-lg: 0 12px 48px rgba(15,14,11,0.14);
  --shadow-xl: 0 24px 80px rgba(15,14,11,0.18);
}

*, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  font-family: 'Crimson Pro', Georgia, serif;
  background: var(--cream);
  color: var(--ink);
  line-height: 1.6;
  overflow-x: hidden;
}

/* ══════════════════════════════════════
   ANNOUNCEMENT BAR
══════════════════════════════════════ */
.announce-bar {
  background: var(--ink);
  color: var(--gold-pale);
  text-align: center;
  padding: 0.55rem 1rem;
  font-family: 'DM Mono', monospace;
  font-size: clamp(0.55rem, 2.2vw, 0.72rem);
  letter-spacing: 0.08em;
  position: relative;
  overflow: hidden;
  white-space: nowrap;
}
.announce-text {
  display: inline-flex;
  align-items: center;
  gap: 0.25em;
  white-space: nowrap;
}
.announce-bar::before {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(90deg, transparent, rgba(184,151,58,0.08), transparent);
  animation: shimmer 3s ease-in-out infinite;
}
.announce-bar a {
  color: var(--gold);
  text-decoration: none;
  border-bottom: 1px solid var(--gold);
  transition: opacity 0.2s;
}
.announce-bar a:hover { opacity: 0.75; }
@keyframes shimmer { 0%,100% { opacity: 0; } 50% { opacity: 1; } }

/* ══════════════════════════════════════
   NAVIGATION
══════════════════════════════════════ */
nav {
  position: sticky;
  top: 0;
  z-index: 100;
  background: rgba(245,240,232,0.95);
  backdrop-filter: blur(20px) saturate(150%);
  border-bottom: 1px solid var(--border-light);
}

.nav-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 68px;
}

.nav-logo {
  display: flex;
  flex-direction: column;
  text-decoration: none;
  gap: 1px;
}
.nav-logo-main {
  font-family: 'Playfair Display', Georgia, serif;
  font-size: 1.35rem;
  font-weight: 700;
  color: var(--ink);
  letter-spacing: -0.02em;
  line-height: 1;
}
.nav-logo-main span {
  color: var(--gold);
}
.nav-logo-sub {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.18em;
  color: var(--ink-3);
  text-transform: uppercase;
}

.nav-menu {
  display: flex;
  align-items: center;
  gap: 0.25rem;
  list-style: none;
}
.nav-menu a {
  font-family: 'Crimson Pro', serif;
  font-size: 1rem;
  font-weight: 500;
  color: var(--ink-2);
  text-decoration: none;
  padding: 0.45rem 0.65rem;
  border-radius: 4px;
  transition: all 0.2s;
  letter-spacing: 0.01em;
  position: relative;
  white-space: nowrap;
}
.nav-menu a::after {
  content: '';
  position: absolute;
  bottom: 2px;
  left: 0.65rem;
  right: 0.65rem;
  height: 1px;
  background: var(--gold);
  transform: scaleX(0);
  transition: transform 0.25s cubic-bezier(.4,0,.2,1);
}
.nav-menu a:hover::after { transform: scaleX(1); }
.nav-menu a:hover { color: var(--ink); }

/* ── NAV DROPDOWN SUBMENU ── */
.nav-item-dropdown {
  position: relative;
}
.nav-submenu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: 6px;
  box-shadow: 0 8px 32px rgba(15,14,11,0.13);
  list-style: none;
  min-width: 160px;
  z-index: 300;
  padding: 0.35rem 0;
}
.nav-item-dropdown:hover .nav-submenu {
  display: block;
}
.nav-submenu li a {
  display: block;
  padding: 0.55rem 1.1rem;
  font-size: 0.92rem;
  color: var(--ink-2);
  border-bottom: 1px solid var(--border-light);
  border-radius: 0;
  white-space: nowrap;
}
.nav-submenu li:last-child a { border-bottom: none; }
.nav-submenu li a:hover { background: var(--cream-2); color: var(--gold); }

@media (max-width: 860px) {
  .nav-item-dropdown:hover .nav-submenu { display: none; }
  .nav-submenu {
    display: block !important;
    position: static;
    box-shadow: none;
    border: none;
    border-radius: 0;
    background: var(--cream-2);
    padding: 0;
  }
  .nav-submenu li a {
    padding: 0.65rem 2.5rem;
    font-size: 0.88rem;
    border-bottom: 1px solid var(--border-light);
  }
}

.nav-cta {
  background: var(--ink) !important;
  color: var(--gold-pale) !important;
  padding: 0.55rem 1.35rem !important;
  border-radius: 4px !important;
  font-weight: 600 !important;
  font-size: 0.9rem !important;
  letter-spacing: 0.04em !important;
  transition: all 0.2s !important;
}
.nav-cta:hover {
  background: var(--gold) !important;
  color: var(--ink) !important;
}
.nav-cta::after { display: none !important; }

.hamburger {
  display: none;
  flex-direction: column;
  gap: 5px;
  background: none;
  border: none;
  cursor: pointer;
  padding: 4px;
}
.hamburger span {
  display: block;
  width: 22px;
  height: 1.5px;
  background: var(--ink);
  transition: all 0.3s;
}
.hamburger.open span:nth-child(1) { transform: translateY(6.5px) rotate(45deg); }
.hamburger.open span:nth-child(2) { opacity: 0; transform: scaleX(0); }
.hamburger.open span:nth-child(3) { transform: translateY(-6.5px) rotate(-45deg); }

@media (max-width: 860px) {
  .hamburger { display: flex; }
  .nav-inner { padding: 0 1.25rem; height: 60px; }
  .nav-logo-main { font-size: 1.15rem; }
  .nav-logo-sub { font-size: 0.52rem; letter-spacing: 0.1em; }
  .nav-menu {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    right: 0;
    background: var(--white);
    flex-direction: column;
    padding: 0.5rem 0 1rem;
    gap: 0;
    border-bottom: 2px solid var(--border);
    box-shadow: 0 8px 32px rgba(15,14,11,0.12);
    z-index: 200;
  }
  .nav-menu.open { display: flex; }
  .nav-menu li { width: 100%; }
  .nav-menu a {
    padding: 0.85rem 1.5rem;
    width: 100%;
    border-bottom: 1px solid var(--border-light);
    border-radius: 0;
    font-size: 1rem;
    display: block;
    white-space: normal;
  }
  .nav-menu a::after { display: none; }
  .nav-menu li:last-child a {
    border-bottom: none;
    margin: 0.75rem 1.25rem 0;
    width: calc(100% - 2.5rem);
    border-radius: 6px;
    text-align: center;
    padding: 0.75rem 1rem;
  }
}

/* ══════════════════════════════════════
   HERO
══════════════════════════════════════ */
.hero {
  min-height: 92vh;
  display: grid;
  grid-template-columns: 1fr 1fr;
  position: relative;
  overflow: hidden;
}

.hero-left {
  background: var(--ink);
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  padding: 5rem 4rem 5rem 5rem;
  position: relative;
  overflow: hidden;
}

.hero-left::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background:
    radial-gradient(ellipse 60% 40% at 10% 80%, rgba(184,151,58,0.12) 0%, transparent 60%),
    radial-gradient(ellipse 40% 60% at 90% 20%, rgba(184,151,58,0.06) 0%, transparent 50%);
  pointer-events: none;
}

.hero-eyebrow {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 2rem;
}
.hero-eyebrow-line {
  width: 40px;
  height: 1px;
  background: var(--gold);
}
.hero-eyebrow-text {
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  letter-spacing: 0.2em;
  color: var(--gold);
  text-transform: uppercase;
}

.hero-title {
  font-family: 'Playfair Display', Georgia, serif;
  font-size: clamp(2.8rem, 5vw, 4.5rem);
  font-weight: 900;
  line-height: 1.05;
  letter-spacing: -0.03em;
  color: var(--white);
  margin-bottom: 0.5rem;
}
.hero-title em {
  font-style: italic;
  color: var(--gold);
}

.hero-subtitle {
  font-family: 'Playfair Display', Georgia, serif;
  font-size: clamp(1.1rem, 1.8vw, 1.5rem);
  font-weight: 400;
  font-style: italic;
  color: rgba(245,240,232,0.65);
  margin-bottom: 2rem;
  line-height: 1.4;
}

.hero-desc {
  font-size: 1.05rem;
  color: rgba(245,240,232,0.75);
  line-height: 1.75;
  max-width: 480px;
  margin-bottom: 2.5rem;
  font-weight: 300;
}

.hero-cred {
  display: flex;
  align-items: center;
  gap: 1rem;
  padding: 1rem 1.25rem;
  border: 1px solid rgba(184,151,58,0.3);
  border-radius: 4px;
  background: rgba(184,151,58,0.06);
  margin-bottom: 2rem;
  max-width: 440px;
}
.hero-cred-icon {
  font-size: 2rem;
  flex-shrink: 0;
}
.hero-cred-text {
  font-family: 'DM Mono', monospace;
  font-size: 0.7rem;
  letter-spacing: 0.05em;
  color: rgba(245,240,232,0.7);
  line-height: 1.6;
}
.hero-cred-name {
  color: var(--gold);
  font-weight: 500;
  font-size: 0.8rem;
}

.hero-actions {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.btn-primary {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: var(--gold);
  color: var(--ink);
  text-decoration: none;
  font-family: 'Crimson Pro', serif;
  font-size: 1rem;
  font-weight: 600;
  letter-spacing: 0.03em;
  padding: 0.85rem 1.75rem;
  border-radius: 3px;
  transition: all 0.25s;
  border: 1.5px solid var(--gold);
}
.btn-primary:hover {
  background: var(--gold-light);
  transform: translateY(-2px);
  box-shadow: 0 8px 24px rgba(184,151,58,0.35);
}

.btn-outline {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: transparent;
  color: var(--cream);
  text-decoration: none;
  font-family: 'Crimson Pro', serif;
  font-size: 1rem;
  font-weight: 500;
  letter-spacing: 0.03em;
  padding: 0.85rem 1.75rem;
  border-radius: 3px;
  border: 1.5px solid rgba(245,240,232,0.35);
  transition: all 0.25s;
}
.btn-outline:hover {
  border-color: var(--gold);
  color: var(--gold);
}

.hero-right {
  position: relative;
  background: var(--cream-2);
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 5rem 4rem;
  overflow: hidden;
}

.hero-right::before {
  content: '"';
  position: absolute;
  top: -2rem;
  right: 2rem;
  font-family: 'Playfair Display', serif;
  font-size: 20rem;
  font-weight: 900;
  color: rgba(184,151,58,0.08);
  line-height: 1;
  pointer-events: none;
  user-select: none;
}

.hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: var(--white);
  border: 1px solid var(--border);
  border-radius: 2px;
  padding: 0.5rem 0.85rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.12em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 2.5rem;
  width: fit-content;
}
.badge-dot {
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background: #22c55e;
  animation: pulse 2s ease-in-out infinite;
}
@keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.4; } }

.hero-stat-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1px;
  background: var(--border-light);
  border: 1px solid var(--border-light);
  border-radius: 6px;
  overflow: hidden;
  margin-bottom: 2.5rem;
}
.hero-stat {
  background: var(--white);
  padding: 1.5rem 1.25rem;
  display: flex;
  flex-direction: column;
  gap: 0.25rem;
}
.hero-stat-num {
  font-family: 'Playfair Display', serif;
  font-size: 2.2rem;
  font-weight: 700;
  color: var(--ink);
  line-height: 1;
  letter-spacing: -0.03em;
}
.hero-stat-label {
  font-size: 0.85rem;
  color: var(--ink-3);
  font-weight: 300;
}

.hero-services-quick {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}
.hero-service-item {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  font-size: 1rem;
  color: var(--ink-2);
  padding: 0.6rem 0;
  border-bottom: 1px solid var(--border-light);
  transition: color 0.2s;
  text-decoration: none;
}
.hero-service-item:last-child { border-bottom: none; }
.hero-service-item:hover { color: var(--gold); }
.hero-service-item:hover .service-arrow { transform: translateX(4px); }
.service-icon {
  font-size: 1.1rem;
  width: 28px;
  text-align: center;
  flex-shrink: 0;
}
.service-text { flex: 1; font-weight: 500; }
.service-arrow {
  color: var(--gold);
  font-size: 0.9rem;
  transition: transform 0.2s;
}

@media (max-width: 900px) {
  .hero {
    grid-template-columns: 1fr;
    min-height: auto;
  }
  .hero-left {
    padding: 3rem 1.5rem 2.5rem;
    order: 1;
  }
  .hero-title {
    font-size: clamp(2rem, 8vw, 3rem);
    margin-bottom: 0.75rem;
  }
  .hero-subtitle { font-size: 1rem; margin-bottom: 1rem; }
  .hero-desc { font-size: 0.97rem; margin-bottom: 1.5rem; max-width: 100%; }
  .hero-cred { padding: 0.85rem 1rem; margin-bottom: 1.5rem; max-width: 100%; }
  .hero-cred-icon { font-size: 1.6rem; }
  .hero-cred-text { font-size: 0.68rem; }
  .hero-actions { gap: 0.75rem; }
  .btn-primary, .btn-outline { padding: 0.75rem 1.35rem; font-size: 0.95rem; }

  .hero-right {
    padding: 2rem 1.5rem 2.5rem;
    order: 2;
  }
  .hero-right::before { font-size: 6rem; }
  .hero-badge { margin-bottom: 1.5rem; }
  .hero-stat-grid { margin-bottom: 1.5rem; }
  .hero-stat { padding: 1rem; }
  .hero-stat-num { font-size: 1.75rem; }
  .hero-stat-label { font-size: 0.78rem; }
}

/* ══════════════════════════════════════
   DIVIDER
══════════════════════════════════════ */
.section-divider {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}
.divider-line { flex: 1; height: 1px; background: var(--border-light); }
.divider-ornament {
  font-family: 'Playfair Display', serif;
  font-size: 1.2rem;
  color: var(--gold);
  letter-spacing: 0.5em;
}

/* ══════════════════════════════════════
   SECTION BASE
══════════════════════════════════════ */
section { padding: 5rem 0; }

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.section-tag {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  letter-spacing: 0.18em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 1rem;
}
.section-tag::before {
  content: '';
  display: inline-block;
  width: 24px;
  height: 1px;
  background: var(--gold);
}

.section-title {
  font-family: 'Playfair Display', Georgia, serif;
  font-size: clamp(2rem, 3.5vw, 3rem);
  font-weight: 700;
  letter-spacing: -0.03em;
  color: var(--ink);
  line-height: 1.15;
  margin-bottom: 1rem;
}
.section-title em {
  font-style: italic;
  color: var(--gold);
}

.section-lead {
  font-size: 1.15rem;
  color: var(--ink-3);
  line-height: 1.75;
  font-weight: 300;
  max-width: 680px;
}

/* ══════════════════════════════════════
   TENTANG PENDIRI
══════════════════════════════════════ */
.about-section {
  background: var(--white);
  border-top: 1px solid var(--border-light);
  border-bottom: 1px solid var(--border-light);
}

.about-grid {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 5rem;
  align-items: start;
}

.about-profile {
  position: sticky;
  top: 100px;
}

.profile-card {
  background: var(--cream);
  border: 1px solid var(--border);
  border-radius: 8px;
  overflow: hidden;
}
.profile-header {
  background: var(--ink);
  padding: 2rem;
  text-align: center;
}
.profile-initial {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  background: var(--gold);
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  font-weight: 700;
  color: var(--ink);
  margin: 0 auto 1rem;
  border: 3px solid rgba(184,151,58,0.4);
}
.profile-name {
  font-family: 'Playfair Display', serif;
  font-size: 1.1rem;
  font-weight: 700;
  color: var(--white);
  margin-bottom: 0.3rem;
}
.profile-title {
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.1em;
  color: var(--gold);
  text-transform: uppercase;
  line-height: 1.6;
}
.profile-body { padding: 1.5rem; }
.profile-cert {
  display: flex;
  flex-direction: column;
  gap: 0.6rem;
}
.cert-item {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  font-size: 0.88rem;
  color: var(--ink-2);
  padding: 0.5rem 0.75rem;
  background: var(--white);
  border-radius: 4px;
  border-left: 2px solid var(--gold);
}
.cert-item .icon { font-size: 0.9rem; flex-shrink: 0; }

.social-links {
  display: flex;
  justify-content: center;
  gap: 0.75rem;
  padding: 1rem 1.5rem 1.5rem;
  flex-wrap: wrap;
}
.social-link {
  display: flex;
  align-items: center;
  gap: 0.4rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.08em;
  color: var(--ink-3);
  text-decoration: none;
  padding: 0.4rem 0.7rem;
  border: 1px solid var(--border-light);
  border-radius: 3px;
  transition: all 0.2s;
}
.social-link:hover {
  border-color: var(--gold);
  color: var(--gold);
}

.about-content {}
.about-intro {
  font-size: 1.2rem;
  line-height: 1.8;
  color: var(--ink-2);
  margin-bottom: 2.5rem;
  font-weight: 300;
}
.about-intro strong {
  font-weight: 600;
  color: var(--ink);
}

.visi-misi-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem;
  margin-bottom: 2.5rem;
}
.vm-card {
  background: var(--cream);
  border: 1px solid var(--border-light);
  border-radius: 6px;
  padding: 1.75rem;
}
.vm-card-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.18em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 0.75rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}
.vm-card-label::after {
  content: '';
  flex: 1;
  height: 1px;
  background: var(--border);
}
.vm-card-text {
  font-size: 1rem;
  color: var(--ink-2);
  line-height: 1.7;
  font-weight: 300;
}

@media (max-width: 860px) {
  .about-grid { grid-template-columns: 1fr; gap: 2rem; }
  .about-profile { position: static; }
  .visi-misi-grid { grid-template-columns: 1fr; gap: 1rem; }
  .about-intro { font-size: 1.05rem; margin-bottom: 1.5rem; }
  .profile-card { max-width: 420px; margin: 0 auto; }
}

/* ══════════════════════════════════════
   LAYANAN
══════════════════════════════════════ */
.services-section {
  background: var(--cream-2);
}

.services-intro {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: end;
  margin-bottom: 4rem;
}
@media (max-width: 768px) {
  .services-intro { grid-template-columns: 1fr; gap: 1rem; margin-bottom: 2rem; }
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1px;
  background: var(--border-light);
  border: 1px solid var(--border-light);
  border-radius: 8px;
  overflow: hidden;
}

@media (max-width: 900px) { .services-grid { grid-template-columns: 1fr 1fr; } }
@media (max-width: 540px) { .services-grid { grid-template-columns: 1fr; } }

.service-card {
  background: var(--white);
  padding: 2.25rem 2rem;
  transition: all 0.3s;
  cursor: default;
  position: relative;
  overflow: hidden;
}
.service-card::before {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 2px;
  background: var(--gold);
  transform: scaleX(0);
  transition: transform 0.3s;
}
.service-card:hover { background: var(--cream); }
.service-card:hover::before { transform: scaleX(1); }
.service-card:hover .service-card-num { color: var(--gold); }

.service-card-num {
  font-family: 'Playfair Display', serif;
  font-size: 3rem;
  font-weight: 900;
  color: rgba(15,14,11,0.06);
  line-height: 1;
  margin-bottom: 1rem;
  transition: color 0.3s;
}
.service-card-icon {
  font-size: 1.6rem;
  margin-bottom: 0.85rem;
}
.service-card-title {
  font-family: 'Playfair Display', serif;
  font-size: 1.2rem;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 0.6rem;
  line-height: 1.3;
}
.service-card-desc {
  font-size: 0.97rem;
  color: var(--ink-3);
  line-height: 1.7;
  font-weight: 300;
}

/* ══════════════════════════════════════
   KONTEN / PRODUK
══════════════════════════════════════ */
.content-section { background: var(--white); }

.content-tabs {
  display: flex;
  gap: 0;
  border-bottom: 1px solid var(--border-light);
  margin-bottom: 3rem;
}
.tab-btn {
  font-family: 'Crimson Pro', serif;
  font-size: 1rem;
  font-weight: 500;
  color: var(--ink-3);
  background: none;
  border: none;
  border-bottom: 2px solid transparent;
  padding: 0.85rem 1.5rem;
  cursor: pointer;
  transition: all 0.2s;
  margin-bottom: -1px;
  letter-spacing: 0.01em;
}
.tab-btn:hover { color: var(--ink); }
.tab-btn.active {
  color: var(--ink);
  border-bottom-color: var(--gold);
  font-weight: 600;
}

.tab-panel { display: none; }
.tab-panel.active { display: block; }

.content-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.5rem;
}

.content-card {
  background: var(--cream);
  border: 1px solid var(--border-light);
  border-radius: 6px;
  padding: 1.75rem;
  transition: all 0.25s;
  text-decoration: none;
  color: inherit;
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}
.content-card:hover {
  border-color: var(--gold);
  transform: translateY(-3px);
  box-shadow: var(--shadow);
}
.content-card-icon { font-size: 1.75rem; }
.content-card-tag {
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.15em;
  color: var(--gold);
  text-transform: uppercase;
}
.content-card-title {
  font-family: 'Playfair Display', serif;
  font-size: 1.1rem;
  font-weight: 700;
  color: var(--ink);
  line-height: 1.35;
}
.content-card-desc {
  font-size: 0.95rem;
  color: var(--ink-3);
  line-height: 1.65;
  font-weight: 300;
  flex: 1;
}
.content-card-link {
  font-size: 0.88rem;
  color: var(--gold);
  font-weight: 500;
  display: flex;
  align-items: center;
  gap: 0.3rem;
  margin-top: 0.5rem;
}

/* ══════════════════════════════════════
   KONSULTASI CTA
══════════════════════════════════════ */
.consult-section {
  background: var(--ink);
  position: relative;
  overflow: hidden;
}
.consult-section::before {
  content: '';
  position: absolute;
  inset: 0;
  background:
    radial-gradient(ellipse 50% 60% at 0% 100%, rgba(184,151,58,0.1) 0%, transparent 55%),
    radial-gradient(ellipse 40% 50% at 100% 0%, rgba(184,151,58,0.07) 0%, transparent 50%);
  pointer-events: none;
}

.consult-inner {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 4rem;
  align-items: center;
  position: relative;
}
@media (max-width: 768px) {
  .consult-inner { grid-template-columns: 1fr; gap: 2rem; }
}

.consult-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  letter-spacing: 0.2em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 1rem;
}

.consult-title {
  font-family: 'Playfair Display', serif;
  font-size: clamp(1.8rem, 3vw, 2.8rem);
  font-weight: 700;
  color: var(--white);
  line-height: 1.15;
  letter-spacing: -0.02em;
  margin-bottom: 1rem;
}
.consult-title em {
  font-style: italic;
  color: var(--gold);
}

.consult-desc {
  font-size: 1.05rem;
  color: rgba(245,240,232,0.65);
  line-height: 1.75;
  font-weight: 300;
  max-width: 520px;
}

.consult-form {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(184,151,58,0.25);
  border-radius: 8px;
  padding: 2rem;
  width: 320px;
  flex-shrink: 0;
}
@media (max-width: 768px) { .consult-form { width: 100%; } }

.form-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.12em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 0.5rem;
  display: block;
}
.form-input {
  width: 100%;
  background: rgba(245,240,232,0.06);
  border: 1px solid rgba(184,151,58,0.25);
  border-radius: 4px;
  padding: 0.75rem 1rem;
  font-family: 'Crimson Pro', serif;
  font-size: 1rem;
  color: var(--white);
  margin-bottom: 1rem;
  transition: border-color 0.2s;
  outline: none;
}
.form-input::placeholder { color: rgba(245,240,232,0.35); }
.form-input:focus { border-color: var(--gold); }
textarea.form-input { resize: vertical; min-height: 100px; }
.form-submit {
  width: 100%;
  background: var(--gold);
  color: var(--ink);
  border: none;
  border-radius: 4px;
  padding: 0.85rem;
  font-family: 'Crimson Pro', serif;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.03em;
  cursor: pointer;
  transition: all 0.2s;
}
.form-submit:hover {
  background: var(--gold-light);
  transform: translateY(-1px);
}
.form-note {
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.06em;
  color: rgba(245,240,232,0.4);
  text-align: center;
  margin-top: 0.75rem;
  line-height: 1.6;
}

/* ══════════════════════════════════════
   FOOTER
══════════════════════════════════════ */
footer {
  background: var(--ink-2);
  border-top: 1px solid rgba(184,151,58,0.2);
  padding: 3.5rem 0 2rem;
}

.footer-grid {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr 1fr;
  gap: 3rem;
  margin-bottom: 3rem;
}
@media (max-width: 900px) { .footer-grid { grid-template-columns: 1fr 1fr; gap: 2rem; } }
@media (max-width: 560px) { .footer-grid { grid-template-columns: 1fr; gap: 2rem; } }

.footer-brand .logo-text {
  font-family: 'Playfair Display', serif;
  font-size: 1.4rem;
  font-weight: 700;
  color: var(--white);
  letter-spacing: -0.02em;
  margin-bottom: 0.25rem;
}
.footer-brand .logo-text span { color: var(--gold); }
.footer-brand .logo-sub {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.15em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 1.25rem;
  display: block;
}
.footer-brand p {
  font-size: 0.95rem;
  color: rgba(245,240,232,0.5);
  line-height: 1.7;
  font-weight: 300;
  max-width: 280px;
}

.footer-col-title {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.15em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 1.25rem;
}
.footer-links {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 0.6rem;
}
.footer-links a {
  font-size: 0.95rem;
  color: rgba(245,240,232,0.55);
  text-decoration: none;
  transition: color 0.2s;
  display: flex;
  align-items: center;
  gap: 0.4rem;
}
.footer-links a:hover { color: var(--gold-pale); }
.footer-links a::before {
  content: '—';
  color: var(--gold);
  opacity: 0.4;
  font-size: 0.7rem;
}

.footer-bottom {
  border-top: 1px solid rgba(245,240,232,0.08);
  padding-top: 1.75rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 1rem;
}
.footer-copy {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.06em;
  color: rgba(245,240,232,0.35);
}
.footer-copy a {
  color: var(--gold);
  text-decoration: none;
}
.footer-bottom-links {
  display: flex;
  gap: 1.5rem;
  list-style: none;
}
.footer-bottom-links a {
  font-family: 'DM Mono', monospace;
  font-size: 0.63rem;
  letter-spacing: 0.08em;
  color: rgba(245,240,232,0.35);
  text-decoration: none;
  transition: color 0.2s;
}
.footer-bottom-links a:hover { color: var(--gold); }

/* ══════════════════════════════════════
   ANIMATIONS
══════════════════════════════════════ */
.fade-up {
  opacity: 0;
  transform: translateY(24px);
  transition: opacity 0.65s cubic-bezier(.2,.8,.2,1), transform 0.65s cubic-bezier(.2,.8,.2,1);
}
.fade-up.visible {
  opacity: 1;
  transform: translateY(0);
}
/* ══════════════════════════════════════
   MOBILE-FIRST OVERHAUL — ≤ 600px
══════════════════════════════════════ */
@media (max-width: 600px) {

  /* --- General --- */
  section { padding: 3rem 0; }
  .container { padding: 0 1.25rem; }

  /* --- Announce bar handled by clamp() above --- */

  /* --- Section typography --- */
  .section-title { font-size: clamp(1.6rem, 6vw, 2.2rem); }
  .section-lead { font-size: 1rem; }
  .section-tag { font-size: 0.62rem; }

  /* --- Hero left --- */
  .hero-left { padding: 2.5rem 1.25rem 2rem; }
  .hero-eyebrow { margin-bottom: 1.25rem; }
  .hero-title {
    font-size: clamp(1.9rem, 7.5vw, 2.6rem);
    margin-bottom: 0.6rem;
    letter-spacing: -0.02em;
  }
  .hero-subtitle { font-size: 0.95rem; margin-bottom: 0.85rem; }
  .hero-desc { font-size: 0.93rem; line-height: 1.65; margin-bottom: 1.25rem; }
  .hero-cred {
    padding: 0.75rem 0.9rem;
    gap: 0.75rem;
    margin-bottom: 1.25rem;
  }
  .hero-cred-icon { font-size: 1.4rem; }
  .hero-cred-name { font-size: 0.72rem; }
  .hero-cred-text { font-size: 0.63rem; line-height: 1.55; }
  .hero-actions { flex-direction: column; gap: 0.6rem; }
  .btn-primary, .btn-outline {
    width: 100%;
    justify-content: center;
    padding: 0.85rem 1.25rem;
    font-size: 1rem;
  }

  /* --- Hero right --- */
  .hero-right { padding: 1.75rem 1.25rem 2.25rem; }
  .hero-badge { font-size: 0.6rem; margin-bottom: 1.25rem; }
  .hero-stat-grid {
    grid-template-columns: 1fr 1fr;
    margin-bottom: 1.25rem;
  }
  .hero-stat { padding: 0.9rem 0.75rem; }
  .hero-stat-num { font-size: 1.6rem; }
  .hero-stat-label { font-size: 0.74rem; line-height: 1.3; }
  .hero-services-quick { gap: 0; }
  .hero-service-item {
    font-size: 0.93rem;
    padding: 0.7rem 0;
    gap: 0.6rem;
  }
  .service-icon { width: 22px; font-size: 1rem; }

  /* --- About section --- */
  .about-section { }
  .profile-card { border-radius: 10px; }
  .profile-header { padding: 1.5rem 1.25rem; }
  .profile-initial { width: 64px; height: 64px; font-size: 1.6rem; }
  .profile-name { font-size: 0.95rem; }
  .profile-title { font-size: 0.56rem; }
  .profile-body { padding: 1.1rem; }
  .cert-item { font-size: 0.82rem; padding: 0.4rem 0.6rem; }
  .social-links {
    padding: 0.75rem 1rem 1.25rem;
    gap: 0.5rem;
  }
  .social-link { font-size: 0.6rem; padding: 0.35rem 0.6rem; }

  .about-intro { font-size: 1rem; line-height: 1.7; }
  .vm-card { padding: 1.25rem; }
  .vm-card-text { font-size: 0.93rem; }

  /* --- Services section --- */
  .service-card { padding: 1.5rem 1.25rem; }
  .service-card-num { font-size: 2rem; margin-bottom: 0.5rem; }
  .service-card-icon { font-size: 1.35rem; margin-bottom: 0.6rem; }
  .service-card-title { font-size: 1.05rem; margin-bottom: 0.4rem; }
  .service-card-desc { font-size: 0.88rem; line-height: 1.6; }

  /* --- Consult section --- */
  .consult-section { }
  .consult-title { font-size: clamp(1.5rem, 6vw, 2rem); }
  .consult-desc { font-size: 0.95rem; }
  .consult-form { padding: 1.5rem 1.25rem; width: 100%; }
  .form-input { font-size: 0.95rem; padding: 0.65rem 0.85rem; }
  .form-label { font-size: 0.6rem; }
  .form-submit { font-size: 0.95rem; }
  .form-note { font-size: 0.58rem; }

  /* --- Footer --- */
  footer { padding: 2.5rem 0 1.5rem; }
  .footer-brand p { max-width: 100%; font-size: 0.88rem; }
  .footer-col-title { font-size: 0.6rem; margin-bottom: 0.85rem; }
  .footer-links a { font-size: 0.88rem; }
  .footer-bottom {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.75rem;
  }
  .footer-bottom-links { gap: 1rem; flex-wrap: wrap; }
  .footer-copy, .footer-bottom-links a { font-size: 0.6rem; }
}

/* ── Visitor Notice responsive ── */
#lp-visitor-notice {
  margin: 2rem 1.25rem;
  padding: 2rem 1.5rem;
}
@media (min-width: 600px) {
  #lp-visitor-notice {
    margin: 3rem auto;
    padding: 2rem 2.5rem;
  }
}

/* ── Portal header write button responsive ── */
.lp-portal-meta {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  flex-wrap: wrap;
}
@media (max-width: 600px) {
  .lp-portal-meta { flex-direction: column; align-items: flex-start; gap: 0.5rem; }
  #lp-write-btn-wrap { width: 100%; }
  #lp-write-btn-wrap .lp-write-btn { width: 100%; justify-content: center; }
}

/* ── Extra: ensure all images are responsive ── */
img { max-width: 100%; height: auto; }

/* ── Overflow guard for all pages ── */
#page-konten, #page-affiliate, #page-digital, #page-dashboard {
  overflow-x: hidden;
}


</style>
</head>
<body>

<!-- ANNOUNCEMENT BAR -->
<div class="announce-bar">
  <span class="announce-text">⚖️ &nbsp;Konsultasi Hukum Gratis &nbsp;-&nbsp; <a href="#konsultasi">Ajukan Pertanyaan Anda</a></span>
</div>

<!-- NAVIGATION -->
<nav>
  <div class="nav-inner">
    <a href="#" class="nav-logo">
      <span class="nav-logo-main">Legal<span>Preneur</span></span>
      <span class="nav-logo-sub">Advokat - Mediator Non Hakim - Konsultan Hukum</span>
    </a>
    <button class="hamburger" id="hamburger-btn" onclick="(function(btn){var menu=btn.closest('nav').querySelector('.nav-menu');menu.classList.toggle('open');btn.classList.toggle('open');})(this)" aria-label="Menu">
      <span></span><span></span><span></span>
    </button>
    <ul class="nav-menu">
      <li><a href="#" onclick="closeMenu();showPage('home');return false;">Beranda</a></li>
      <li><a href="#" onclick="closeMenu();showPage('home');setTimeout(()=>document.getElementById('tentang').scrollIntoView({behavior:'smooth'}),50);return false;">Tentang</a></li>
      <li><a href="#" onclick="closeMenu();showPage('home');setTimeout(()=>document.getElementById('layanan').scrollIntoView({behavior:'smooth'}),50);return false;">Layanan</a></li>
      <li><a href="#" onclick="closeMenu();showPage('konten');return false;">Konten</a></li>
      <li><a href="#" onclick="closeMenu();showPage('affiliate');return false;">Produk Rekomendasi</a></li>
      <li><a href="#" onclick="closeMenu();showPage('digital');return false;">Produk Digital</a></li>
      <li><a href="#" onclick="closeMenu();showPage('home');setTimeout(()=>document.getElementById('konsultasi').scrollIntoView({behavior:'smooth'}),50);return false;" class="nav-cta">Hubungi Kami</a></li>
      <li id="nav-dashboard-li" style="display:none;"><a href="#" onclick="closeMenu();showPage('dashboard');return false;" style="color:var(--gold)!important;">🔐 Dashboard</a></li>
    </ul>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="hero-left">
    <h1 class="hero-title">
      Hukum yang<br><em>Mudah Dipahami</em>,<br>Advokasi yang<br>Berintegritas
    </h1>

    <p class="hero-subtitle">Platform hukum & literasi digital terpercaya</p>

    <p class="hero-desc">
      LegalPreneur hadir untuk menjembatani masyarakat, profesional, dan korporasi dalam mengakses solusi hukum yang praktis, transparan, dan berdampak nyata.
    </p>

    <div class="hero-cred">
      <div class="hero-cred-icon">⚖️</div>
      <div class="hero-cred-text">
        <div class="hero-cred-name">Novrizal, S.I.Kom., S.H., CPM</div>
        Advokat & Konsultan Hukum · Mediator Non Hakim<br>
        Business Owner NovrizDigital · Affiliate Marketer · Penulis
      </div>
    </div>

    <div class="hero-actions">
      <a href="#konsultasi" class="btn-primary">Konsultasi Gratis →</a>
      <a href="#layanan" class="btn-outline">Lihat Layanan</a>
    </div>
  </div>

  <div class="hero-right">
    <div class="hero-badge">
      <div class="badge-dot"></div>
      Tersedia untuk Konsultasi
    </div>

    <div class="hero-stat-grid">
      <div class="hero-stat">
        <div class="hero-stat-num">5+</div>
        <div class="hero-stat-label">Tahun Pengalaman Hukum</div>
      </div>
      <div class="hero-stat">
        <div class="hero-stat-num">100+</div>
        <div class="hero-stat-label">Klien Terlayani</div>
      </div>
      <div class="hero-stat">
        <div class="hero-stat-num">10+</div>
        <div class="hero-stat-label">Karya Literasi</div>
      </div>
      <div class="hero-stat">
        <div class="hero-stat-num">100+</div>
        <div class="hero-stat-label">Mediasi/Non Litigasi</div>
      </div>
    </div>

    <div class="hero-services-quick">
      <a href="#layanan" class="hero-service-item">
        <span class="service-icon">⚖️</span>
        <span class="service-text">Konsultasi Hukum Online</span>
        <span class="service-arrow">→</span>
      </a>
      <a href="#layanan" class="hero-service-item">
        <span class="service-icon">📑</span>
        <span class="service-text">Penyusunan Kontrak & Dokumen Legal</span>
        <span class="service-arrow">→</span>
      </a>
      <a href="#layanan" class="hero-service-item">
        <span class="service-icon">🔍</span>
        <span class="service-text">Verifikasi Legalitas Penyedia Layanan</span>
        <span class="service-arrow">→</span>
      </a>
      <a href="#konten" class="hero-service-item">
        <span class="service-icon">📚</span>
        <span class="service-text">E-Book & Literasi Hukum Digital</span>
        <span class="service-arrow">→</span>
      </a>
      <a href="#produk" class="hero-service-item">
        <span class="service-icon">🛍️</span>
        <span class="service-text">Produk Rekomendasi Pilihan</span>
        <span class="service-arrow">→</span>
      </a>
    </div>
  </div>
</div>

<!-- TENTANG PENDIRI -->
<section class="about-section" id="tentang">
  <div class="container">
    <div class="about-grid">
      <!-- Profil -->
      <div class="about-profile">
        <div class="profile-card fade-up">
          <div class="profile-header">
            <div class="profile-photo" style="width:120px;height:120px;border-radius:50%;overflow:hidden;margin:0 auto 1rem;border:3px solid rgba(184,151,58,0.5);box-shadow:0 4px 16px rgba(0,0,0,0.3);">
              <img src="data:image/jpeg;base64,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7qNUDVlnOt2cuXHj9V55c1uWfTDq00azturz8um67mV6zdlhdqOU7+e6zTkzcuim7rz10zVzbluoXPrw9Pn0y0dSgwQ2Zt40auVbLtjinLUTu3iuu+3OodTB0sblqonctRmaeBv5QVbstS7PG76XkyyBMIEwgTCBJCGhDBDYkwbiycoSJkWkhAAUAADAAQ0CaFCcZYRmiAwQ2RbAAAGIYIYHN6XOOXfnsms9lUa9KuftxbLqqrMZf1Zefg355eXRpq3kvyGsylqv59MOfRRvK006M0tJXJg2RmsNkY7zvo148rsujBvPQojdy6a4xe8Zq9dGOma7Lr6c5LTzc2yh6NQ6OPu89zs83cd6jTmuc81zpd/E7HIqzVRKyPb872TrAWAMQwQwUZogMEMENA0DaCTQSaaNoGIpgAAAwQAJojGSlimEUwQwTAABiYAAAHO6PEMO7DvtxLTllt6/H7mNRnGSOo0GayGqzLhp7c153H1c9m945RiZDpjTZXZy6zk6t882a6jTVXCaacejJLrot0ZufLJdMdGzPrxuvNfmxrPfRPpjpcpaIy6ZWTWm4qjRbGxJ02SM2vDgVZ69Gs3257tZovcJfSEWMQSSCREJCQAxDQhghgADaByiyTi0YOgAAAAAAQISFCBKkAAAAMAGmAAAh+e7nnTVO6sppJri6OKya9Jny9nLhd/yPqjmE5GezTnKeP3sK8hbqemJOWnl0p1QnrFOS5zXOtvN4rdGizWs96beVsxkabLc7y9CquXZSW3NFd8cdMt50bnbdk4Vnr+ZTpLqOhykdleiXJx+xw620WV2XXYNOs2121Z33NXL6dywBDBDABDEDAAEAAADaYSiyTiz/8QAAv/aAAwDAQACAAMAAAAhlM4484wg0wA08888888888888088888oAwww088888888888oAMM88U4AAVwUKAhBBcAEIAQwwwwwwAQwAAAAAAAAAAAAAAAAAAAQwwww8888844EBAAr9899NNNdw88oAAAAAAAEMMcMMMM888888888888IAAAAAAAAAAAA8cpAAz/AMccdccYTKAFPPPPPPPPPPMMMIEMMMMMMMMMMMPPPPPDDDDDDDOAENfPfHrwQQQRXPKNJigAAAADggggggggggggiggggggggggAikMMMMMIDDPAAMcTyof/ADzzAAChL64447777774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" alt="Novrizal" style="width:100%;height:100%;object-fit:cover;object-position:center top;">
            </div>
            <div class="profile-name">Novrizal, S.I.Kom., S.H., CPM</div>
            <div class="profile-title">Pendiri LegalPreneur</div>
          </div>
          <div class="profile-body">
            <div class="profile-cert">
              <div class="cert-item"><span class="icon">🏅</span>CPM – Certified Professional Mediator</div>
              <div class="cert-item"><span class="icon">🤝</span>Mediator Non Hakim</div>
              <div class="cert-item"><span class="icon">🏢</span>Business Owner NovrizDigital</div>
              <div class="cert-item"><span class="icon">🛍️</span>Affiliate Marketer</div>
              <div class="cert-item"><span class="icon">✍️</span>Penulis & Content Creator</div>
            </div>
          </div>
          <div class="social-links">
            <a href="https://web.facebook.com/novriz.digital" target="_blank" class="social-link">📘 Facebook</a>
            <a href="https://www.instagram.com/novriz_dct/" target="_blank" class="social-link">📸 Instagram</a>
            <a href="https://www.tiktok.com/@novriz77?is_from_webapp=1&sender_device=pc" target="_blank" class="social-link">🎵 TikTok</a>
            <a href="https://www.threads.com/@novriz_dct" target="_blank" class="social-link">🧵 Threads</a>
            <a href="https://x.com/Novriz_Tan" target="_blank" class="social-link">𝕏 Twitter</a>
          </div>
        </div>
      </div>

      <!-- Konten -->
      <div class="about-content">
        <div class="section-tag fade-up">Tentang Kami</div>
        <h2 class="section-title fade-up">Selamat Datang di <em>LegalPreneur</em></h2>

        <p class="about-intro fade-up">
          LegalPreneur dibangun oleh <strong>Novrizal, S.I.Kom., S.H., CPM</strong> — seorang Advokat & Konsultan Hukum yang menggabungkan pengalaman hukum, latar belakang ilmu komunikasi, dan sertifikasi profesional untuk menghadirkan solusi hukum yang tepat sasaran dan advokasi yang berintegritas.
        </p>

        <p class="section-lead fade-up" style="margin-bottom: 2.5rem;">
          Platform ini lahir dari keyakinan bahwa <em>setiap orang berhak memahami hukum</em> — bukan sekadar mereka yang mampu menyewa pengacara mahal. Pengetahuan hukum yang aksesibel adalah fondasi masyarakat yang berdaya.
        </p>

        <div class="visi-misi-grid">
          <div class="vm-card fade-up">
            <div class="vm-card-label">Visi</div>
            <p class="vm-card-text">Menjadi platform hukum, literasi, dan gaya hidup digital terpercaya yang menjembatani masyarakat, profesional, dan korporasi dalam satu ekosistem yang modern dan berdampak.</p>
          </div>
          <div class="vm-card fade-up">
            <div class="vm-card-label">Misi</div>
            <p class="vm-card-text">Memberikan solusi hukum yang praktis dan berintegritas, mendorong literasi hukum yang aksesibel, serta berbagi pengetahuan bermakna melalui karya tulis dan inovasi digital.</p>
          </div>
        </div>

        <div class="section-lead fade-up" style="font-size: 1rem; padding: 1.5rem; background: var(--cream-2); border-left: 3px solid var(--gold); border-radius: 0 4px 4px 0;">
          💡 <strong style="font-weight: 600;">Filosofi kami:</strong> Hukum bukan tembok penghalang — melainkan jembatan menuju keadilan. LegalPreneur hadir untuk membangun jembatan itu, satu konsultasi dalam satu waktu.
        </div>
      </div>
    </div>
  </div>
</section>

<!-- LAYANAN -->
<section class="services-section" id="layanan">
  <div class="container">
    <div class="services-intro">
      <div>
        <div class="section-tag fade-up">Layanan Kami</div>
        <h2 class="section-title fade-up">Solusi Hukum <em>Lengkap</em> untuk Anda</h2>
      </div>
      <p class="section-lead fade-up">
        Dari konsultasi ringan hingga penanganan perkara kompleks — kami menghadirkan layanan hukum digital yang mudah diakses oleh siapa saja, kapan saja.
      </p>
    </div>

    <div class="services-grid fade-up">
      <div class="service-card">
        <div class="service-card-num">01</div>
        <div class="service-card-icon">⚖️</div>
        <h3 class="service-card-title">Konsultasi Hukum Online</h3>
        <p class="service-card-desc">Ruang terbuka bagi masyarakat yang membutuhkan panduan awal menghadapi permasalahan hukum. Dapatkan arahan yang jelas, praktis, dan berintegritas.</p>
      </div>
      <div class="service-card">
        <div class="service-card-num">02</div>
        <div class="service-card-icon">📑</div>
        <h3 class="service-card-title">Penyusunan Kontrak & Dokumen Legal</h3>
        <p class="service-card-desc">Kontrak bisnis, perjanjian kerja sama, dokumen perusahaan — disusun secara profesional sesuai kebutuhan bisnis maupun personal Anda.</p>
      </div>
      <div class="service-card">
        <div class="service-card-num">03</div>
        <div class="service-card-icon">🔍</div>
        <h3 class="service-card-title">Verifikasi Legalitas</h3>
        <p class="service-card-desc">Memastikan semua transaksi bisnis Anda aman dan sesuai regulasi. Verifikasi dokumen, izin usaha, dan aspek legal penyedia layanan.</p>
      </div>
      <div class="service-card">
        <div class="service-card-num">04</div>
        <div class="service-card-icon">🏛️</div>
        <h3 class="service-card-title">Edukasi Hukum Praktis</h3>
        <p class="service-card-desc">Workshop, artikel, dan materi edukasi hukum yang dirancang agar masyarakat lebih melek hukum dalam kehidupan digital sehari-hari.</p>
      </div>
      <div class="service-card">
        <div class="service-card-num">05</div>
        <div class="service-card-icon">🤝</div>
        <h3 class="service-card-title">Mediasi Non-Litigasi</h3>
        <p class="service-card-desc">Penyelesaian sengketa di luar pengadilan — lebih cepat, lebih hemat, dan lebih menjaga hubungan para pihak melalui proses mediasi profesional.</p>
      </div>
      <div class="service-card">
        <div class="service-card-num">06</div>
        <div class="service-card-icon">📩</div>
        <h3 class="service-card-title">Kolaborasi & Kemitraan</h3>
        <p class="service-card-desc">Terbuka untuk individu, komunitas, organisasi, maupun korporasi — dalam bidang advokasi, edukasi hukum, penerbitan, dan inisiatif digital.</p>
      </div>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════════════════════════
     KONTEN — PORTAL BERITA & ARTIKEL LEGALPRENEUR
══════════════════════════════════════════════════════════ -->
<section id="page-konten" style="display:none; background: var(--cream); min-height: 80vh;">

<!-- ── IKLAN BANNER ATAS ──────────────────────────────── -->
<div class="lp-ad-banner" id="ad-top">
  <span class="lp-ad-label">Iklan</span>
  <div class="lp-ad-content">
    <div class="lp-ad-logo">⚖️ LegalPreneur</div>
    <div class="lp-ad-text">
      <strong>Butuh Advokat Profesional?</strong> Konsultasikan <a href="#konsultasi" onclick="closeMenu();showPage('home');setTimeout(()=>document.getElementById('konsultasi').scrollIntoView({behavior:'smooth'}),80);return false;" style="color:var(--gold-pale);font-weight:600;text-decoration:underline;text-decoration-color:rgba(240,228,192,0.4);text-underline-offset:2px;transition:text-decoration-color 0.2s;" onmouseover="this.style.textDecorationColor='rgba(240,228,192,0.9)'" onmouseout="this.style.textDecorationColor='rgba(240,228,192,0.4)'">di sini</a>.
    </div>
    <a href="#konsultasi" onclick="closeMenu();showPage('home');setTimeout(()=>document.getElementById('konsultasi').scrollIntoView({behavior:'smooth'}),80);return false;" class="lp-ad-btn">Konsultasi Gratis →</a>
  </div>
</div>

<!-- ── PORTAL HEADER ─────────────────────────────────── -->
<div class="lp-portal-header">
  <div class="lp-portal-inner">
    <div class="lp-portal-brand">
      <span class="lp-portal-tag">PORTAL HUKUM & LITERASI</span>
      <h1 class="lp-portal-title">Berita & Artikel <em>LegalPreneur</em></h1>
      <p class="lp-portal-sub">Informasi hukum, literasi digital, dan analisis kebijakan terkini oleh Novrizal, S.I.Kom., S.H., CPM</p>
    </div>
    <div class="lp-portal-meta">
      <span id="lp-date-now" class="lp-date-live"></span>
      <!-- Info user login -->
      <div id="lp-user-status-bar" style="display:none; align-items:center; gap:0.5rem; font-family:'DM Mono',monospace; font-size:0.65rem; letter-spacing:0.08em; color:rgba(245,240,232,0.7);">
        <span id="lp-user-greeting"></span>
        <button onclick="lp_logout()" style="background:rgba(184,151,58,0.15); border:1px solid rgba(184,151,58,0.3); border-radius:4px; padding:0.3rem 0.65rem; font-family:'DM Mono',monospace; font-size:0.6rem; color:var(--gold); cursor:pointer; transition:all 0.2s;" onmouseover="this.style.background='rgba(184,151,58,0.3)'" onmouseout="this.style.background='rgba(184,151,58,0.15)'">🔒 Keluar</button>
      </div>
      <div id="lp-auth-btn-wrap" style="display:none;">
        <button onclick="lp_showAuthBox()" style="background:var(--gold); color:var(--ink); border:none; border-radius:5px; padding:0.5rem 1.1rem; font-family:'DM Mono',monospace; font-size:0.65rem; font-weight:700; letter-spacing:0.08em; cursor:pointer; transition:all 0.2s;" onmouseover="this.style.background='var(--gold-light)'" onmouseout="this.style.background='var(--gold)'">✍️ Daftar / Masuk</button>
      </div>
      <div id="lp-write-btn-wrap" style="display:none;">
        <button class="lp-write-btn" onclick="lp_openEditor(null)">✏️ &nbsp;Tulis Artikel Baru</button>
      </div>
    </div>
  </div>
</div>

<!-- ── AUTH BOX (Login / Daftar untuk menulis artikel) ─── -->
<div id="lp-visitor-notice" style="display:none;"></div>
<div id="lp-auth-box" style="display:none; max-width:480px; margin:2.5rem auto 0; padding:2rem 2.5rem; background:var(--white); border:1px solid var(--border); border-radius:12px; box-shadow:var(--shadow-lg);">
  <div style="text-align:center; margin-bottom:1.5rem;">
    <div style="font-size:2rem; margin-bottom:0.5rem;">✍️</div>
    <div style="font-family:'Playfair Display',serif; font-size:1.2rem; font-weight:700; color:var(--ink);">Daftar / Masuk untuk Menulis</div>
    <p style="color:var(--ink-3); font-size:0.88rem; line-height:1.6; margin-top:0.4rem;">Buat akun atau masuk untuk mengirimkan & mengelola artikel di portal LegalPreneur.</p>
  </div>
  <!-- Tab Switch -->
  <div style="display:flex; gap:0; border:1px solid var(--border-light); border-radius:8px; overflow:hidden; margin-bottom:1.25rem;">
    <button id="lp-auth-tab-login" onclick="lp_switchAuthTab('login')" style="flex:1; padding:0.6rem; font-family:'DM Mono',monospace; font-size:0.7rem; letter-spacing:0.08em; border:none; cursor:pointer; background:var(--ink); color:var(--gold-pale); transition:all 0.2s;">🔓 MASUK</button>
    <button id="lp-auth-tab-register" onclick="lp_switchAuthTab('register')" style="flex:1; padding:0.6rem; font-family:'DM Mono',monospace; font-size:0.7rem; letter-spacing:0.08em; border:none; cursor:pointer; background:var(--cream-2); color:var(--ink-3); transition:all 0.2s;">📝 DAFTAR</button>
  </div>
  <!-- Login Form -->
  <div id="lp-auth-login-form">
    <div style="margin-bottom:0.85rem;">
      <input type="email" id="lp-login-email" placeholder="Email Anda" style="width:100%; padding:0.7rem 1rem; background:var(--cream); border:1px solid var(--border-light); border-radius:6px; font-family:'Crimson Pro',serif; font-size:1rem; color:var(--ink); outline:none; box-sizing:border-box; transition:border-color 0.2s;" onfocus="this.style.borderColor='var(--gold)'" onblur="this.style.borderColor=''" onkeydown="if(event.key==='Enter')lp_doLogin()">
    </div>
    <div style="margin-bottom:1rem;">
      <input type="password" id="lp-login-pw" placeholder="Password" style="width:100%; padding:0.7rem 1rem; background:var(--cream); border:1px solid var(--border-light); border-radius:6px; font-family:'Crimson Pro',serif; font-size:1rem; color:var(--ink); outline:none; box-sizing:border-box; transition:border-color 0.2s;" onfocus="this.style.borderColor='var(--gold)'" onblur="this.style.borderColor=''" onkeydown="if(event.key==='Enter')lp_doLogin()">
    </div>
    <button onclick="lp_doLogin()" style="width:100%; padding:0.75rem; background:var(--ink); color:var(--gold-pale); border:none; border-radius:6px; font-family:'DM Mono',monospace; font-size:0.75rem; font-weight:700; letter-spacing:0.08em; cursor:pointer; transition:background 0.2s;" onmouseover="this.style.background='var(--gold)';this.style.color='var(--ink)'" onmouseout="this.style.background='var(--ink)';this.style.color='var(--gold-pale)'">🔓 MASUK</button>
    <div id="lp-login-err" style="display:none; color:#ef4444; font-family:'DM Mono',monospace; font-size:0.68rem; text-align:center; margin-top:0.65rem;"></div>
  </div>
  <!-- Register Form -->
  <div id="lp-auth-register-form" style="display:none;">
    <div style="margin-bottom:0.85rem;">
      <input type="text" id="lp-reg-name" placeholder="Nama Lengkap *" style="width:100%; padding:0.7rem 1rem; background:var(--cream); border:1px solid var(--border-light); border-radius:6px; font-family:'Crimson Pro',serif; font-size:1rem; color:var(--ink); outline:none; box-sizing:border-box; transition:border-color 0.2s;" onfocus="this.style.borderColor='var(--gold)'" onblur="this.style.borderColor=''">
    </div>
    <div style="margin-bottom:0.85rem;">
      <input type="email" id="lp-reg-email" placeholder="Email *" style="width:100%; padding:0.7rem 1rem; background:var(--cream); border:1px solid var(--border-light); border-radius:6px; font-family:'Crimson Pro',serif; font-size:1rem; color:var(--ink); outline:none; box-sizing:border-box; transition:border-color 0.2s;" onfocus="this.style.borderColor='var(--gold)'" onblur="this.style.borderColor=''">
    </div>
    <div style="margin-bottom:0.85rem;">
      <input type="password" id="lp-reg-pw" placeholder="Password (min. 6 karakter) *" style="width:100%; padding:0.7rem 1rem; background:var(--cream); border:1px solid var(--border-light); border-radius:6px; font-family:'Crimson Pro',serif; font-size:1rem; color:var(--ink); outline:none; box-sizing:border-box; transition:border-color 0.2s;" onfocus="this.style.borderColor='var(--gold)'" onblur="this.style.borderColor=''">
    </div>
    <div style="margin-bottom:1rem;">
      <input type="password" id="lp-reg-pw2" placeholder="Konfirmasi Password *" style="width:100%; padding:0.7rem 1rem; background:var(--cream); border:1px solid var(--border-light); border-radius:6px; font-family:'Crimson Pro',serif; font-size:1rem; color:var(--ink); outline:none; box-sizing:border-box; transition:border-color 0.2s;" onfocus="this.style.borderColor='var(--gold)'" onblur="this.style.borderColor=''" onkeydown="if(event.key==='Enter')lp_doRegister()">
    </div>
    <button onclick="lp_doRegister()" style="width:100%; padding:0.75rem; background:var(--gold); color:var(--ink); border:none; border-radius:6px; font-family:'DM Mono',monospace; font-size:0.75rem; font-weight:700; letter-spacing:0.08em; cursor:pointer; transition:background 0.2s;" onmouseover="this.style.background='var(--gold-light)'" onmouseout="this.style.background='var(--gold)'">📝 DAFTAR SEKARANG</button>
    <div id="lp-reg-err" style="display:none; font-family:'DM Mono',monospace; font-size:0.68rem; text-align:center; margin-top:0.65rem;"></div>
  </div>
</div>

<!-- ── BREAKING NEWS TICKER ────────────────── -->
<div class="lp-breaking-bar">
  <div class="lp-breaking-inner" id="lp-ticker-inner">
    <span><span class="lp-breaking-label">TERKINI</span><span class="lp-breaking-text">Portal Hukum & Literasi Digital LegalPreneur — Informasi hukum terpercaya oleh Novrizal, S.I.Kom., S.H., CPM</span></span>
    <span><span class="lp-breaking-label">INFO</span><span class="lp-breaking-text">Konsultasi hukum gratis: WhatsApp 0812-6219-5937 — Advokat, Mediator Bersertifikat</span></span>
    <span><span class="lp-breaking-label">TERKINI</span><span class="lp-breaking-text">Portal Hukum & Literasi Digital LegalPreneur — Informasi hukum terpercaya oleh Novrizal, S.I.Kom., S.H., CPM</span></span>
    <span><span class="lp-breaking-label">INFO</span><span class="lp-breaking-text">Konsultasi hukum gratis: WhatsApp 0812-6219-5937 — Advokat, Mediator Bersertifikat</span></span>
  </div>
</div>


<div class="lp-filter-bar">
  <div class="lp-portal-inner" style="display:flex; align-items:center; gap:0.5rem; flex-wrap:wrap;">
    <button class="lp-cat-btn active" onclick="lp_filterCat('semua', this)">📰 Semua</button>
    <button class="lp-cat-btn" onclick="lp_filterCat('hukum', this)">⚖️ Hukum</button>
    <button class="lp-cat-btn" onclick="lp_filterCat('mediasi', this)">🤝 Mediasi</button>
    <button class="lp-cat-btn" onclick="lp_filterCat('finansial', this)">💰 Finansial</button>
    <button class="lp-cat-btn" onclick="lp_filterCat('digital', this)">📱 Digital</button>
    <button class="lp-cat-btn" onclick="lp_filterCat('regulasi', this)">🏛️ Regulasi</button>
    <button class="lp-cat-btn" onclick="lp_filterCat('opini', this)">✍️ Opini</button>
  </div>
</div>

<!-- ── MAIN PORTAL BODY ───────────────────────────────── -->
<div class="lp-portal-inner lp-portal-body">

  <!-- GRID ARTIKEL -->
  <div class="lp-main-col">
    <!-- HEADLINE / FEATURED -->
    <div id="lp-featured-wrap"></div>
    <!-- ARTIKEL GRID -->
    <div id="lp-grid-wrap" class="lp-articles-grid"></div>
    <!-- EMPTY STATE -->
    <div id="lp-empty" style="display:none;" class="lp-empty-state">
      <div class="lp-empty-icon">📰</div>
      <div class="lp-empty-title">Belum Ada Artikel</div>
      <p class="lp-empty-desc">Jadilah yang pertama menulis berita atau artikel di portal ini.</p>
      <button class="lp-write-btn" onclick="lp_openEditor(null)" style="margin-top:1.25rem;">✏️ Tulis Artikel Pertama</button>
    </div>
  </div>

  <!-- SIDEBAR -->
  <aside class="lp-sidebar">

    <!-- IKLAN SIDEBAR -->
    <div class="lp-ad-sidebar">
      <div class="lp-ad-label">Iklan</div>
      <div class="lp-ad-side-inner">
        <div style="font-size:2rem; text-align:center; margin-bottom:0.75rem;">⚖️</div>
        <div style="font-family:'Playfair Display',serif; font-size:1rem; font-weight:700; color:var(--white); line-height:1.3; margin-bottom:0.5rem;">Konsultasi Hukum Gratis</div>
        <div style="font-size:0.82rem; color:rgba(245,240,232,0.65); line-height:1.6; margin-bottom:1rem;">Advokat & Mediator berpengalaman siap membantu permasalahan hukum Anda.</div>
        <a href="https://wa.me/6281262195937" target="_blank" class="lp-ad-side-btn">📱 Hubungi via WhatsApp</a>
        <div style="font-family:'DM Mono',monospace; font-size:0.6rem; letter-spacing:0.1em; color:rgba(245,240,232,0.3); text-align:center; margin-top:0.75rem;">0812-6219-5937</div>
      </div>
    </div>

    <!-- ARTIKEL TERBARU SIDEBAR -->
    <div class="lp-sidebar-box">
      <div class="lp-sidebar-title">📌 Artikel Terbaru</div>
      <ul id="lp-recent-list" class="lp-recent-list"></ul>
    </div>

    <!-- ── /FORM KIRIM ARTIKEL DIHAPUS ──────────────────────────── -->

    <!-- STATISTIK INSIGHT SIDEBAR -->
    <div class="lp-sidebar-box lp-insight-box">
      <div class="lp-sidebar-title">📊 Insight Konten</div>
      <div class="lp-insight-stats">
        <div class="lp-insight-stat">
          <div class="lp-insight-num" id="ins-total-art">0</div>
          <div class="lp-insight-label">Total Artikel</div>
        </div>
        <div class="lp-insight-stat">
          <div class="lp-insight-num" id="ins-total-reads">0</div>
          <div class="lp-insight-label">Total Pembaca</div>
        </div>
        <div class="lp-insight-stat">
          <div class="lp-insight-num" id="ins-today-reads">0</div>
          <div class="lp-insight-label">Baca Hari Ini</div>
        </div>
        <div class="lp-insight-stat">
          <div class="lp-insight-num" id="ins-avg-time">0m</div>
          <div class="lp-insight-label">Rata-rata Baca</div>
        </div>
      </div>
      <!-- Mini bar chart per kategori -->
      <div class="lp-insight-chart-label">Artikel per Kategori</div>
      <div id="lp-cat-chart" class="lp-cat-chart"></div>
      <!-- Grafik 7 hari pembaca -->
      <div class="lp-insight-chart-label" style="margin-top:1rem;">Pembaca 7 Hari Terakhir</div>
      <canvas id="lp-week-chart" height="80" style="width:100%;"></canvas>
    </div>

  </aside>
</div>

<!-- ── IKLAN BAWAH ────────────────────────────────────── -->
<div class="lp-ad-banner lp-ad-banner-bottom">
  <span class="lp-ad-label">Iklan</span>
  <div class="lp-ad-content">
    <div class="lp-ad-logo">📱 NovrizDigital</div>
    <div class="lp-ad-text">
      <strong>Produk Rekomendasi Pilihan</strong> — Kebutuhan produktivitas & gaya hidup. Kuratasi personal oleh Novrizal.
    </div>
    <a href="#" onclick="closeMenu();showPage('affiliate');return false;" class="lp-ad-btn" style="background:var(--gold); color:var(--ink); border-color:var(--gold);">Lihat Produk →</a>
  </div>
</div>

<div class="page-mini-footer">
  <button onclick="showPage('home')" class="mini-back-btn">← Kembali ke Beranda</button>
  <span>LegalPreneur · Novrizal, S.I.Kom., S.H., CPM</span>
  <a href="https://wa.me/6281262195937" target="_blank">WhatsApp: 0812-6219-5937</a>
</div>

</section>

<!-- ════════════════════════════════════════════════════════
     PAGE: DASHBOARD OWNER (TERSEMBUNYI — HANYA OWNER)
════════════════════════════════════════════════════════ -->
<section id="page-dashboard" style="display:none; background:var(--cream); min-height:80vh;">

<!-- Login Gate -->
<div id="dash-login-gate" style="display:flex; align-items:center; justify-content:center; min-height:80vh; padding:2rem;">
  <div class="dash-login-box">
    <div class="dash-login-logo">🔐</div>
    <div class="dash-login-title">Akses Terbatas</div>
    <div class="dash-login-sub">Halaman ini hanya untuk pemilik LegalPreneur.<br>Masukkan kata sandi untuk melanjutkan.</div>
    <input type="password" id="dash-pw-input" class="dash-pw-input" placeholder="Masukkan kata sandi…" onkeydown="if(event.key==='Enter')dashLogin()">
    <button class="dash-pw-btn" onclick="dashLogin()">🔓 Masuk Dashboard</button>
    <div id="dash-pw-err" style="display:none; color:#f87171; font-family:'DM Mono',monospace; font-size:0.68rem; margin-top:0.75rem; text-align:center;">❌ Kata sandi salah. Coba lagi.</div>
    <button onclick="showPage('home')" class="dash-back-link">← Kembali ke Beranda</button>
  </div>
</div>

<!-- Dashboard Content (hidden until login) -->
<div id="dash-content" style="display:none;">

  <!-- Header Dashboard -->
  <div class="dash-header">
    <div class="dash-header-inner">
      <div>
        <div class="dash-header-tag">🔐 OWNER DASHBOARD · RAHASIA</div>
        <h1 class="dash-header-title">Laporan Analitik <em>LegalPreneur</em></h1>
        <div class="dash-header-sub" id="dash-report-date"></div>
      </div>
      <div style="display:flex; gap:0.75rem; align-items:center; flex-wrap:wrap;">
        <button class="dash-export-btn" onclick="dashExportPDF()">📄 Export PDF</button>
        <button class="dash-logout-btn" onclick="dashLogout()">🔒 Kunci Dashboard</button>
      </div>
    </div>
  </div>

  <!-- Google Sheets Database Setup Banner -->
  <div id="dash-firebase-banner" class="dash-inner" style="padding-top:1.5rem; padding-bottom:0;">
    <div id="dash-firebase-card" style="background:linear-gradient(135deg,#0f2a1a,#1a3d28); border:1.5px solid rgba(34,197,94,0.4); border-radius:12px; padding:1.5rem 2rem; margin-bottom:0;">
      <div style="display:flex; align-items:flex-start; gap:1rem; flex-wrap:wrap;">
        <div style="flex:1; min-width:260px;">
          <div style="font-family:'DM Mono',monospace; font-size:0.62rem; letter-spacing:0.18em; color:#4ade80; text-transform:uppercase; margin-bottom:0.5rem;" id="dash-fb-status-label">📊 Status Google Sheets Database</div>
          <div style="font-family:'Playfair Display',serif; font-size:1.1rem; font-weight:700; color:#f5f0e8; margin-bottom:0.5rem;" id="dash-fb-status-title">Menghubungkan ke database...</div>
          <div style="font-size:0.88rem; color:rgba(245,240,232,0.6); line-height:1.6;" id="dash-fb-status-desc">Artikel tersimpan di browser (localStorage) + disinkron ke Google Sheets. Tidak hilang saat refresh.</div>
        </div>
        <div style="flex-shrink:0;">
          <div style="width:14px; height:14px; border-radius:50%; background:#f59e0b; animation:pulse 1.5s ease-in-out infinite;" id="dash-fb-dot"></div>
        </div>
      </div>
      <!-- Panduan setup Google Sheets — hanya muncul jika belum dikonfigurasi -->
      <div id="dash-fb-setup-guide" style="display:none; margin-top:1.25rem; border-top:1px solid rgba(34,197,94,0.2); padding-top:1.25rem;">
        <div style="font-family:'DM Mono',monospace; font-size:0.65rem; letter-spacing:0.12em; color:#4ade80; text-transform:uppercase; margin-bottom:0.85rem;">📋 Cara Setup Google Sheets Database (Gratis, 5 Menit)</div>
        <ol style="font-size:0.88rem; color:rgba(245,240,232,0.75); line-height:2.2; padding-left:1.25rem;">
          <li>Buka <a href="https://sheets.new" target="_blank" style="color:#4ade80;">sheets.new</a> (login akun Google) → beri nama: <strong style="color:#86efac;">LegalPreneur Articles</strong></li>
          <li>Klik menu <strong style="color:#86efac;">Extensions → Apps Script</strong></li>
          <li>Hapus semua kode yang ada, lalu paste kode Apps Script dari komentar di dalam file HTML ini (cari bagian <code style="background:rgba(34,197,94,0.15);padding:0.1rem 0.4rem;border-radius:3px;color:#86efac;">/* Paste kode ... */</code>)</li>
          <li>Klik <strong style="color:#86efac;">Deploy → New deployment</strong> → pilih type: <em>Web App</em></li>
          <li>Set <em>Execute as:</em> <strong>Me</strong> dan <em>Who has access:</em> <strong>Anyone</strong> → Deploy</li>
          <li>Copy URL deployment yang muncul (format: <code style="color:#86efac;">https://script.google.com/macros/s/.../exec</code>)</li>
          <li>Buka file HTML ini → cari <code style="background:rgba(34,197,94,0.15);padding:0.1rem 0.4rem;border-radius:3px;color:#86efac;">LP_SHEETS_URL</code> → tempel URL di situ → simpan</li>
          <li>Buka kembali website → artikel tersimpan permanen di Google Sheets ✅</li>
        </ol>
      </div>
    </div>
  </div>

  <!-- KPI Cards -->
  <div class="dash-inner">
    <div class="dash-kpi-grid">
      <div class="dash-kpi-card">
        <div class="dash-kpi-icon">👁️</div>
        <div class="dash-kpi-num" id="d-total-views">0</div>
        <div class="dash-kpi-label">Total Pengunjung</div>
        <div class="dash-kpi-trend positive" id="d-views-trend">+0% bulan ini</div>
      </div>
      <div class="dash-kpi-card">
        <div class="dash-kpi-icon">📰</div>
        <div class="dash-kpi-num" id="d-total-art">0</div>
        <div class="dash-kpi-label">Total Artikel</div>
        <div class="dash-kpi-trend positive" id="d-art-trend">Terakhir dipublikasi</div>
      </div>
      <div class="dash-kpi-card">
        <div class="dash-kpi-icon">📖</div>
        <div class="dash-kpi-num" id="d-total-reads">0</div>
        <div class="dash-kpi-label">Artikel Dibaca</div>
        <div class="dash-kpi-trend" id="d-reads-trend">Total sesi baca</div>
      </div>
      <div class="dash-kpi-card">
        <div class="dash-kpi-icon">⏱️</div>
        <div class="dash-kpi-num" id="d-avg-time">0m</div>
        <div class="dash-kpi-label">Rata-rata Waktu Baca</div>
        <div class="dash-kpi-trend">Per sesi pembaca</div>
      </div>
      <div class="dash-kpi-card">
        <div class="dash-kpi-icon">📲</div>
        <div class="dash-kpi-num" id="d-share-count">0</div>
        <div class="dash-kpi-label">Artikel Dibagikan</div>
        <div class="dash-kpi-trend">WhatsApp, FB, X</div>
      </div>
      <div class="dash-kpi-card">
        <div class="dash-kpi-icon">💬</div>
        <div class="dash-kpi-num" id="d-consult-count">0</div>
        <div class="dash-kpi-label">Permintaan Konsultasi</div>
        <div class="dash-kpi-trend">Via form & WA</div>
      </div>
    </div>

    <!-- Chart Row -->
    <div class="dash-chart-row">
      <!-- Grafik 30 hari -->
      <div class="dash-chart-card" style="flex:2;">
        <div class="dash-chart-title">📈 Trafik Pengunjung — 30 Hari Terakhir</div>
        <canvas id="d-traffic-chart" height="180"></canvas>
      </div>
      <!-- Distribusi kategori -->
      <div class="dash-chart-card" style="flex:1;">
        <div class="dash-chart-title">🗂️ Artikel per Kategori</div>
        <canvas id="d-cat-pie" height="180"></canvas>
      </div>
    </div>

    <!-- Artikel populer & endors info -->
    <div class="dash-chart-row">
      <!-- Top artikel -->
      <div class="dash-chart-card" style="flex:1.5;">
        <div class="dash-chart-title">🔥 Artikel Paling Banyak Dibaca</div>
        <div id="d-top-articles" class="d-top-list"></div>
      </div>
      <!-- Info endors untuk owner -->
      <div class="dash-chart-card" style="flex:1; background:var(--ink);">
        <div class="dash-chart-title" style="color:var(--gold);">📣 Potensi Pendapatan Iklan</div>
        <div class="dash-ad-potential">
          <div class="dap-row">
            <span class="dap-label">Estimasi pengunjung/bulan</span>
            <span class="dap-val" id="dap-monthly">—</span>
          </div>
          <div class="dap-row">
            <span class="dap-label">Potensi iklan banner (CPM)</span>
            <span class="dap-val" id="dap-banner">—</span>
          </div>
          <div class="dap-row">
            <span class="dap-label">Potensi artikel sponsored</span>
            <span class="dap-val" id="dap-sponsored">—</span>
          </div>
          <div class="dap-row">
            <span class="dap-label">Potensi in-read ads</span>
            <span class="dap-val" id="dap-inread">—</span>
          </div>
          <div class="dap-total-row">
            <span>Total Potensi / Bulan</span>
            <span id="dap-total" style="color:var(--gold); font-size:1.2rem; font-weight:700;">—</span>
          </div>
          <a href="https://wa.me/6281262195937?text=Halo%2C+saya+mau+info+paket+iklan+LegalPreneur" target="_blank" class="dap-contact-btn">📱 Buka Negosiasi via WA</a>
        </div>
      </div>
    </div>

    <!-- Tabel riwayat artikel -->
    <div class="dash-chart-card" style="margin-bottom:2rem;">
      <div class="dash-chart-title">📋 Riwayat Semua Artikel</div>
      <div style="overflow-x:auto;">
        <table class="d-article-table" id="d-article-table">
          <thead>
            <tr>
              <th>#</th>
              <th>Judul</th>
              <th>Kategori</th>
              <th>Penulis</th>
              <th>Tanggal</th>
              <th>Est. Pembaca</th>
              <th>Baca (mnt)</th>
            </tr>
          </thead>
          <tbody id="d-article-tbody"></tbody>
        </table>
      </div>
    </div>

    <!-- Footer dashboard -->
    <div class="dash-footer-note">
      🔒 Data ini bersifat rahasia dan hanya tersedia untuk pemilik LegalPreneur. Pengunjung website tidak dapat mengakses halaman ini.
    </div>

  </div><!-- /dash-inner -->

  <div class="page-mini-footer" style="margin-top:0;">
    <button onclick="dashLogout();showPage('home')" class="mini-back-btn">← Kembali ke Beranda</button>
    <span>LegalPreneur Owner Dashboard · Confidential</span>
    <span style="color:var(--gold);" id="dash-last-update"></span>
  </div>

</div><!-- /dash-content -->
</section>

<!-- ════════════════════════════════════════════════════════
     MODAL: BACA ARTIKEL LENGKAP
════════════════════════════════════════════════════════ -->
<div id="lp-read-modal" class="lp-modal-overlay" style="display:none;" onclick="if(event.target===this)lp_closeRead()">
  <div class="lp-modal-box lp-read-box">
    <button class="lp-modal-close" onclick="lp_closeRead()">✕</button>

    <!-- Iklan atas modal baca -->
    <div class="lp-read-ad">
      <span class="lp-ad-label">Iklan</span>
      <span style="font-family:'DM Mono',monospace; font-size:0.68rem; color:var(--ink-3);">⚖️ Konsultasi Hukum Gratis — <a href="https://wa.me/6281262195937" target="_blank" style="color:var(--gold);">WhatsApp: 0812-6219-5937</a></span>
    </div>

    <div id="lp-read-content"></div>

    <!-- Share & Iklan bawah artikel -->
    <div class="lp-read-footer">

      <!-- ── BAGIKAN ARTIKEL ── -->
      <div class="lp-share-section">
        <div class="lp-share-section-label">Bagikan Artikel Ini</div>
        <div class="lp-share-row">
          <!-- WhatsApp -->
          <button class="lp-share-btn lp-share-btn-wa" onclick="lp_shareWA()" title="Bagikan ke WhatsApp">
            <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:-2px;margin-right:4px;"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/><path d="M12 0C5.373 0 0 5.373 0 12c0 2.127.558 4.126 1.533 5.857L0 24l6.335-1.521A11.945 11.945 0 0012 24c6.627 0 12-5.373 12-12S18.627 0 12 0zm0 21.818a9.818 9.818 0 01-5.015-1.378l-.36-.214-3.726.894.939-3.63-.234-.373A9.818 9.818 0 1112 21.818z"/></svg>
            WhatsApp
          </button>
          <!-- Facebook -->
          <button class="lp-share-btn lp-share-btn-fb" onclick="lp_shareFB()" title="Bagikan ke Facebook">
            <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:-2px;margin-right:4px;"><path d="M24 12.073C24 5.405 18.627 0 12 0S0 5.405 0 12.073c0 6.031 4.438 11.031 10.125 11.927v-8.437H7.078v-3.49h3.047V9.42c0-3.025 1.791-4.697 4.533-4.697 1.312 0 2.686.235 2.686.235v2.97h-1.514c-1.491 0-1.956.93-1.956 1.874v2.25h3.328l-.532 3.49h-2.796v8.437C19.562 23.104 24 18.104 24 12.073z"/></svg>
            Facebook
          </button>
          <!-- Threads -->
          <button class="lp-share-btn lp-share-btn-threads" onclick="lp_shareThreads()" title="Bagikan ke Threads">
            <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:-2px;margin-right:4px;"><path d="M12.186 24h-.007c-3.581-.024-6.334-1.205-8.184-3.509C2.35 18.44 1.5 15.586 1.472 12.01v-.017c.03-3.579.879-6.43 2.525-8.482C5.845 1.205 8.6.024 12.18 0h.014c2.746.02 5.043.725 6.826 2.098 1.677 1.29 2.858 3.13 3.509 5.467l-2.04.569c-1.104-3.96-3.898-5.984-8.304-6.015-2.91.022-5.11.936-6.54 2.717C4.307 6.504 3.616 8.914 3.589 12c.027 3.086.718 5.496 2.057 7.164 1.43 1.783 3.631 2.698 6.54 2.717 2.623-.02 4.358-.631 5.8-2.045 1.647-1.613 1.618-3.593 1.09-4.798-.31-.71-.873-1.3-1.634-1.75-.192 1.352-.622 2.446-1.284 3.272-.886 1.102-2.14 1.704-3.73 1.79-1.202.065-2.361-.218-3.259-.801-1.063-.689-1.685-1.74-1.752-2.964-.065-1.19.408-2.285 1.33-3.082.88-.76 2.119-1.207 3.583-1.291a13.853 13.853 0 012.581.124v-.57c0-.065-.004-.127-.01-.188-.076-.96-.62-1.667-1.55-1.94-.695-.2-1.417-.193-2.048.019-.661.223-1.089.702-1.272 1.421l-2-.529c.29-1.108.914-1.957 1.857-2.523.882-.529 1.953-.792 3.18-.792.307 0 .62.02.935.06 1.822.24 3.09 1.31 3.43 2.872.08.36.12.734.12 1.117v.782c.4.206.768.44 1.093.703 1.163.935 1.944 2.219 2.282 3.728.557 2.463-.101 5.023-1.824 6.841C18.199 22.968 15.665 24 12.186 24z"/></svg>
            Threads
          </button>
          <!-- X / Twitter -->
          <button class="lp-share-btn lp-share-btn-x" onclick="lp_shareX()" title="Bagikan ke X/Twitter">
            <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:-2px;margin-right:4px;"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-4.714-6.231-5.401 6.231H2.748l7.73-8.835L1.254 2.25H8.08l4.26 5.632zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
            X / Twitter
          </button>
          <!-- Salin Link -->
          <button class="lp-share-btn lp-share-btn-copy" onclick="lp_shareCopy()" id="lp-copy-btn" title="Salin tautan artikel">
            🔗 Salin Link
          </button>
        </div>
      </div>

      <!-- ── SLOT IKLAN BAWAH ARTIKEL ── -->
      <div class="lp-read-ad-grid">

        <!-- Slot Shopee Affiliate -->
        <div class="lp-inread-ad lp-inread-ad-shopee">
          <div class="lp-inread-ad-label">
            <svg width="11" height="11" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 14.5v-9l6 4.5-6 4.5z"/></svg>
            Iklan · Shopee Affiliate
          </div>
          <div class="lp-inread-ad-body">
            <div class="lp-inread-ad-icon">🛒</div>
            <div class="lp-inread-ad-text-wrap">
              <div class="lp-inread-ad-title">Produk Pilihan di Shopee</div>
              <div class="lp-inread-ad-desc">Temukan produk berkualitas pilihan LegalPreneur — dari kebutuhan sehari-hari hingga produktivitas.</div>
            </div>
            <a href="#" onclick="showPage('affiliate');document.getElementById('lp-read-modal').style.display='none';document.body.style.overflow='';return false;" class="lp-inread-ad-cta">
              🛍️ Lihat Katalog
            </a>
          </div>
        </div>

        <!-- Slot Lynk.id / Produk Digital -->
        <div class="lp-inread-ad lp-inread-ad-lynk">
          <div class="lp-inread-ad-label">
            <svg width="11" height="11" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 14.5v-9l6 4.5-6 4.5z"/></svg>
            Iklan · Produk Digital
          </div>
          <div class="lp-inread-ad-body">
            <div class="lp-inread-ad-icon">📚</div>
            <div class="lp-inread-ad-text-wrap">
              <div class="lp-inread-ad-title">E-Book & Produk Digital Hukum</div>
              <div class="lp-inread-ad-desc">Belajar hukum, bermain game, dan siap CPNS/ASN bersama LegalPreneur — dapatkan akses sekarang!</div>
            </div>
            <a href="#" onclick="showPage('digital');document.getElementById('lp-read-modal').style.display='none';document.body.style.overflow='';return false;" class="lp-inread-ad-cta">
              📖 Lihat Produk
            </a>
          </div>
        </div>

      </div><!-- /lp-read-ad-grid -->

    </div><!-- /lp-read-footer -->
  </div>
</div>

<!-- ════════════════════════════════════════════════════════
     MODAL: EDITOR ARTIKEL
════════════════════════════════════════════════════════ -->
<div id="lp-editor-modal" class="lp-modal-overlay" style="display:none;" onclick="if(event.target===this)lp_confirmClose()">
  <div class="lp-modal-box lp-editor-box">
    <div class="lp-editor-header">
      <div>
        <div style="font-family:'DM Mono',monospace; font-size:0.65rem; letter-spacing:0.15em; color:var(--gold); text-transform:uppercase; margin-bottom:0.25rem;" id="lp-editor-mode-label">✏️ Tulis Artikel Baru</div>
        <div style="font-family:'Playfair Display',serif; font-size:1.15rem; font-weight:700; color:var(--white);">Ruang Redaksi LegalPreneur</div>
      </div>
      <button class="lp-modal-close" onclick="lp_confirmClose()" style="color:var(--white);">✕</button>
    </div>

    <div class="lp-editor-body">
      <!-- Template Pilih -->
      <div class="lp-field-group" id="lp-template-section">
        <label class="lp-field-label">📋 Template Artikel Cepat <span style="color:var(--ink-3); font-weight:400;">(opsional — klik untuk pakai)</span></label>
        <div class="lp-template-grid" id="lp-template-grid"></div>
      </div>

      <!-- Judul -->
      <div class="lp-field-group">
        <label class="lp-field-label" for="lp-ed-title">📰 Judul Artikel / Berita <span class="lp-required">*</span></label>
        <input type="text" id="lp-ed-title" class="lp-field-input" placeholder="Tulis judul yang menarik dan informatif..." maxlength="150">
        <div class="lp-field-hint">Judul yang baik: jelas, padat, dan mengandung kata kunci utama.</div>
      </div>

      <!-- Penulis -->
      <div class="lp-field-group">
        <label class="lp-field-label" for="lp-ed-author">✍️ Nama Penulis</label>
        <input type="text" id="lp-ed-author" class="lp-field-input" placeholder="Novrizal, S.I.Kom., S.H., CPM" value="Novrizal, S.I.Kom., S.H., CPM">
      </div>
      <!-- Kategori disembunyikan, default 'umum' agar sistem tetap berjalan -->
      <input type="hidden" id="lp-ed-cat" value="umum">

      <!-- Ringkasan -->
      <div class="lp-field-group">
        <label class="lp-field-label" for="lp-ed-summary">📝 Ringkasan / Lead Berita <span class="lp-required">*</span></label>
        <textarea id="lp-ed-summary" class="lp-field-input lp-field-textarea" rows="3" placeholder="Tulis 1–2 kalimat pembuka yang merangkum isi artikel. Ini tampil di halaman daftar artikel." maxlength="300"></textarea>
        <div class="lp-field-hint"><span id="lp-summary-count">0</span>/300 karakter</div>
      </div>

      <!-- Foto / Gambar -->
      <div class="lp-field-group">
        <label class="lp-field-label">🖼️ Foto / Gambar Berita</label>
        <div class="lp-img-upload-area" id="lp-img-drop" onclick="document.getElementById('lp-ed-img').click()">
          <input type="file" id="lp-ed-img" accept="image/*" style="display:none;" onchange="lp_handleImg(this)">
          <div id="lp-img-preview-wrap">
            <div class="lp-img-placeholder" id="lp-img-placeholder">
              <span style="font-size:2rem;">📷</span>
              <span>Klik untuk unggah foto, atau tempel URL gambar di bawah</span>
            </div>
            <img id="lp-img-preview" style="display:none; max-width:100%; max-height:220px; border-radius:6px; object-fit:cover; width:100%;" alt="preview">
          </div>
        </div>
        <div style="display:flex; gap:0.5rem; margin-top:0.5rem;">
          <input type="text" id="lp-ed-imgurl" class="lp-field-input" placeholder="Atau tempel URL gambar: https://..." style="font-size:0.85rem;" oninput="lp_previewUrl(this.value)">
          <button type="button" class="lp-btn-sm" onclick="lp_clearImg()">✕ Hapus</button>
        </div>
        <div style="margin-top:0.5rem;">
          <input type="text" id="lp-ed-imgcaption" class="lp-field-input" placeholder="Keterangan foto / caption (opsional)" style="font-size:0.85rem;">
        </div>
        <div class="lp-field-hint">Format: JPG, PNG, WEBP. Ukuran ideal: 1200×630px (rasio 16:9).</div>
      </div>

      <!-- Isi Artikel -->
      <div class="lp-field-group">
        <label class="lp-field-label">📄 Isi Artikel / Berita <span class="lp-required">*</span></label>

        <!-- TOOLBAR ROW 1: Font & Ukuran -->
        <div class="lp-editor-toolbar lp-toolbar-row1">
          <!-- Font Family -->
          <select class="lp-tb-select" title="Jenis Font" onchange="lp_setFont(this.value)">
            <option value="">— Font —</option>
            <option value="Crimson Pro, Georgia, serif">Crimson Pro (Serif)</option>
            <option value="Playfair Display, Georgia, serif">Playfair Display</option>
            <option value="Georgia, serif">Georgia</option>
            <option value="Arial, sans-serif">Arial</option>
            <option value="Helvetica, Arial, sans-serif">Helvetica</option>
            <option value="Verdana, sans-serif">Verdana</option>
            <option value="Tahoma, sans-serif">Tahoma</option>
            <option value="Times New Roman, serif">Times New Roman</option>
            <option value="DM Mono, monospace">DM Mono (Monospace)</option>
            <option value="Courier New, monospace">Courier New</option>
          </select>

          <!-- Font Size -->
          <select class="lp-tb-select lp-tb-select-sm" title="Ukuran Font" onchange="lp_setFontSize(this.value)">
            <option value="">— Ukuran —</option>
            <option value="1">Kecil (8pt)</option>
            <option value="2">Kecil (10pt)</option>
            <option value="3">Normal (12pt)</option>
            <option value="4">Sedang (14pt)</option>
            <option value="5">Besar (18pt)</option>
            <option value="6">Lebih Besar (24pt)</option>
            <option value="7">Terbesar (36pt)</option>
          </select>

          <div class="lp-tb-sep"></div>

          <!-- Heading blocks -->
          <button type="button" class="lp-tb-btn" onclick="lp_fmtBlock('h1')" title="Judul H1">H1</button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmtBlock('h2')" title="Judul H2">H2</button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmtBlock('h3')" title="Sub-judul H3">H3</button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmtBlock('p')" title="Paragraf Normal">¶</button>

          <div class="lp-tb-sep"></div>

          <!-- Warna Teks -->
          <div class="lp-tb-color-wrap" title="Warna Teks (klik untuk pilih warna bebas)">
            <span class="lp-tb-color-label" id="lp-txt-color-label" style="text-decoration:underline; text-decoration-color:#fdfcf9; text-decoration-thickness:3px;">A</span>
            <input type="color" id="lp-txt-color" class="lp-tb-colorpick" value="#0f0e0b"
              onchange="lp_setColor(this.value); lp_updateColorLabel('lp-txt-color-label', this.value);" title="Warna Teks">
          </div>

          <!-- Warna Sorot -->
          <div class="lp-tb-color-wrap" title="Warna Sorot / Highlight (klik untuk pilih)">
            <span class="lp-tb-color-label" id="lp-bg-color-label" style="background:#f0e4c0; color:#0f0e0b; border-bottom:3px solid #f0e4c0;">Aa</span>
            <input type="color" id="lp-bg-color" class="lp-tb-colorpick" value="#f0e4c0"
              onchange="lp_setHighlight(this.value); lp_updateBgLabel('lp-bg-color-label', this.value);" title="Sorot Teks">
          </div>

          <div class="lp-tb-sep"></div>

          <!-- Preset warna teks cepat -->
          <span style="font-family:'DM Mono',monospace; font-size:0.55rem; letter-spacing:0.08em; color:rgba(245,240,232,0.45); align-self:center; white-space:nowrap;">Warna:</span>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetColor('#0f0e0b')" title="Hitam (default)" style="background:#0f0e0b; color:#fff; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetColor('#b8973a')" title="Emas" style="background:#b8973a; color:#0f0e0b; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetColor('#dc3545')" title="Merah" style="background:#dc3545; color:#fff; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetColor('#1877F2')" title="Biru" style="background:#1877F2; color:#fff; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetColor('#22c55e')" title="Hijau" style="background:#22c55e; color:#0f0e0b; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetColor('#a855f7')" title="Ungu" style="background:#a855f7; color:#fff; min-width:20px; padding:0.28rem 0.35rem;">A</button>

          <div class="lp-tb-sep"></div>

          <!-- Preset sorot/highlight cepat -->
          <span style="font-family:'DM Mono',monospace; font-size:0.55rem; letter-spacing:0.08em; color:rgba(245,240,232,0.45); align-self:center; white-space:nowrap;">Sorot:</span>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetHighlight('transparent')" title="Hapus sorot" style="background:transparent; color:rgba(245,240,232,0.6); border-style:dashed; min-width:20px; padding:0.28rem 0.35rem;">∅</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetHighlight('#f0e4c0')" title="Sorot emas pucat" style="background:#f0e4c0; color:#0f0e0b; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetHighlight('#fef9c3')" title="Sorot kuning" style="background:#fef9c3; color:#0f0e0b; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetHighlight('#bbf7d0')" title="Sorot hijau muda" style="background:#bbf7d0; color:#0f0e0b; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetHighlight('#bfdbfe')" title="Sorot biru muda" style="background:#bfdbfe; color:#0f0e0b; min-width:20px; padding:0.28rem 0.35rem;">A</button>
          <button type="button" class="lp-tb-btn lp-color-preset" onclick="lp_applyPresetHighlight('#fce7f3')" title="Sorot merah muda" style="background:#fce7f3; color:#0f0e0b; min-width:20px; padding:0.28rem 0.35rem;">A</button>
        </div>

        <!-- TOOLBAR ROW 2: Format & Alignment -->
        <div class="lp-editor-toolbar lp-toolbar-row2">
          <!-- Undo / Redo -->
          <button type="button" class="lp-tb-btn" id="lp-undo-btn" onclick="lp_undo()" title="Batalkan (Ctrl+Z)" style="font-size:1rem; padding:0.18rem 0.5rem;">↩</button>
          <button type="button" class="lp-tb-btn" id="lp-redo-btn" onclick="lp_redo()" title="Ulangi (Ctrl+Y)" style="font-size:1rem; padding:0.18rem 0.5rem;">↪</button>

          <div class="lp-tb-sep"></div>

          <!-- Style teks -->
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('bold')" title="Tebal (Ctrl+B)"><b>B</b></button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('italic')" title="Miring (Ctrl+I)"><i>I</i></button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('underline')" title="Garis Bawah (Ctrl+U)"><u>U</u></button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('strikeThrough')" title="Coret"><s>S</s></button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('superscript')" title="Superscript">x²</button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('subscript')" title="Subscript">x₂</button>

          <div class="lp-tb-sep"></div>

          <!-- Alignment -->
          <button type="button" class="lp-tb-btn lp-tb-align" onclick="lp_fmt('justifyLeft')" title="Rata Kiri">⬅</button>
          <button type="button" class="lp-tb-btn lp-tb-align" onclick="lp_fmt('justifyCenter')" title="Rata Tengah">≡</button>
          <button type="button" class="lp-tb-btn lp-tb-align" onclick="lp_fmt('justifyRight')" title="Rata Kanan">➡</button>
          <button type="button" class="lp-tb-btn lp-tb-align" onclick="lp_fmt('justifyFull')" title="Rata Kiri-Kanan (Justify)">&#8213;</button>

          <div class="lp-tb-sep"></div>

          <!-- List & Indentation -->
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('insertUnorderedList')" title="Bullet List">• —</button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('insertOrderedList')" title="Numbered List">1.</button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('outdent')" title="Kurangi Indentasi">⇤</button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('indent')" title="Tambah Indentasi">⇥</button>

          <div class="lp-tb-sep"></div>

          <!-- Blok & Lainnya -->
          <button type="button" class="lp-tb-btn" onclick="lp_fmtBlock('blockquote')" title="Kutipan">❝</button>
          <button type="button" class="lp-tb-btn" onclick="lp_insertHR()" title="Garis Horizontal">—</button>
          <button type="button" class="lp-tb-btn" onclick="lp_insertLink()" title="Sisipkan Tautan">🔗</button>
          <button type="button" class="lp-tb-btn" onclick="lp_insertShopeeAd()" title="Sisipkan Slot Iklan Shopee" style="color:#EE4D2D; border-color:rgba(238,77,45,0.3);">🛒</button>
          <button type="button" class="lp-tb-btn" onclick="lp_insertLynkAd()" title="Sisipkan Slot Iklan Lynk.id / Produk Digital" style="color:#6366f1; border-color:rgba(99,102,241,0.3);">📚</button>
          <button type="button" class="lp-tb-btn" onclick="lp_fmt('removeFormat')" title="Hapus Semua Format" style="color:#f87171;">✕</button>
        </div>

        <div id="lp-ed-body" class="lp-editor-area" contenteditable="true" spellcheck="true"></div>
        <div class="lp-field-hint">Gunakan toolbar di atas untuk memformat teks. <kbd style="font-family:'DM Mono',monospace;font-size:0.58rem;background:rgba(245,240,232,0.1);border:1px solid rgba(184,151,58,0.25);border-radius:3px;padding:0.1rem 0.3rem;color:var(--gold-pale);">Ctrl+Z</kbd> Undo &nbsp;·&nbsp; <kbd style="font-family:'DM Mono',monospace;font-size:0.58rem;background:rgba(245,240,232,0.1);border:1px solid rgba(184,151,58,0.25);border-radius:3px;padding:0.1rem 0.3rem;color:var(--gold-pale);">Ctrl+Y</kbd> Redo &nbsp;·&nbsp; Draft tersimpan otomatis setiap 30 detik.</div>
      </div>

      <!-- Tags -->
      <div class="lp-field-group">
        <label class="lp-field-label" for="lp-ed-tags">🏷️ Tag / Kata Kunci</label>
        <input type="text" id="lp-ed-tags" class="lp-field-input" placeholder="hukum, mediasi, kontrak (pisahkan dengan koma)">
        <div class="lp-field-hint">Tag membantu pembaca menemukan artikel terkait.</div>
      </div>

      <!-- Auto-save status -->
      <div id="lp-autosave-status" style="font-family:'DM Mono',monospace; font-size:0.62rem; letter-spacing:0.08em; color:var(--ink-3); text-align:right; margin-top:-0.5rem;"></div>

      <!-- Action buttons -->
      <div class="lp-editor-actions">
        <button type="button" class="lp-btn-ghost" onclick="lp_saveDraft()">💾 Simpan ke Draf</button>
        <button type="button" class="lp-btn-ghost" onclick="lp_clearDraftAndForm()" style="color:rgba(248,113,113,0.7); border-color:rgba(248,113,113,0.2);">🗑️ Hapus Draft</button>
        <button type="button" class="lp-btn-ghost" onclick="lp_previewArticle()">👁️ Preview</button>
        <button type="button" id="lp-ed-delete-btn" class="lp-btn-ghost" onclick="lp_deleteFromEditor()" style="display:none; color:rgba(248,113,113,0.9); border-color:rgba(248,113,113,0.35);">🗑️ Hapus Artikel</button>
        <button type="button" class="lp-btn-publish" onclick="lp_publishArticle()">🚀 Terbitkan Artikel</button>
      </div>
      <div id="lp-editor-msg" style="display:none; margin-top:0.75rem; padding:0.75rem 1rem; border-radius:6px; font-family:'DM Mono',monospace; font-size:0.72rem; letter-spacing:0.05em; text-align:center;"></div>
    </div>
  </div>
</div>

<!-- STYLES KONTEN PORTAL -->
<style>
/* ── PORTAL LAYOUT ───────────────────────── */
.lp-portal-inner {
  max-width: 1180px;
  margin: 0 auto;
  padding: 0 2rem;
}
.lp-portal-header {
  background: linear-gradient(135deg, #0f0e0b 0%, #1a1816 55%, #0d0c09 100%);
  padding: 2.5rem 0 2rem;
  border-bottom: 3px solid var(--gold);
  position: relative;
  overflow: hidden;
}
.lp-portal-header::before {
  content: '';
  position: absolute;
  inset: 0;
  background:
    radial-gradient(ellipse 55% 70% at 0% 100%, rgba(184,151,58,0.13) 0%, transparent 55%),
    radial-gradient(ellipse 35% 50% at 100% 0%, rgba(184,151,58,0.07) 0%, transparent 50%);
  pointer-events: none;
}
.lp-portal-header::after {
  content: '§';
  position: absolute;
  right: 3rem;
  top: -1.5rem;
  font-family: 'Playfair Display', serif;
  font-size: 14rem;
  font-weight: 900;
  color: rgba(184,151,58,0.04);
  line-height: 1;
  pointer-events: none;
  user-select: none;
}
.lp-portal-inner.lp-portal-body {
  display: grid;
  grid-template-columns: 1fr 300px;
  gap: 2.5rem;
  padding-top: 2.5rem;
  padding-bottom: 3rem;
  align-items: start;
}
.lp-portal-brand { flex: 1; }
.lp-portal-tag {
  display: inline-block;
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.2em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 0.5rem;
  background: rgba(184,151,58,0.12);
  padding: 0.25rem 0.65rem;
  border-radius: 2px;
}
.lp-portal-header .lp-portal-inner {
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  gap: 1.5rem;
  flex-wrap: wrap;
}
.lp-portal-title {
  font-family: 'Playfair Display', serif;
  font-size: clamp(1.6rem, 4vw, 2.4rem);
  font-weight: 900;
  color: var(--white);
  line-height: 1.1;
  letter-spacing: -0.02em;
  margin-bottom: 0.4rem;
}
.lp-portal-title em { color: var(--gold); font-style: italic; }
.lp-portal-sub {
  font-size: 0.92rem;
  color: rgba(245,240,232,0.55);
  font-weight: 300;
  white-space: nowrap;
}
.lp-portal-meta {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  gap: 0.65rem;
  flex-shrink: 0;
}
.lp-date-live {
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.1em;
  color: rgba(245,240,232,0.4);
}

/* ── FILTER BAR ──────────────────────────── */
.lp-filter-bar {
  background: var(--ink-2);
  border-bottom: 1px solid rgba(184,151,58,0.2);
  padding: 0;
  overflow-x: auto;
}
.lp-filter-bar .lp-portal-inner {
  display: flex;
  gap: 0;
  padding-top: 0;
  padding-bottom: 0;
}
.lp-cat-btn {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.1em;
  color: rgba(245,240,232,0.5);
  background: none;
  border: none;
  border-bottom: 2.5px solid transparent;
  padding: 0.85rem 1.1rem;
  cursor: pointer;
  transition: all 0.2s;
  white-space: nowrap;
  text-transform: uppercase;
}
.lp-cat-btn:hover { color: var(--gold-pale); }
.lp-cat-btn.active { color: var(--gold); border-bottom-color: var(--gold); }

/* ── WRITE BUTTON ────────────────────────── */
.lp-write-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  background: var(--gold);
  color: var(--ink);
  border: none;
  border-radius: 4px;
  padding: 0.6rem 1.25rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  font-weight: 600;
  letter-spacing: 0.06em;
  cursor: pointer;
  transition: all 0.2s;
  white-space: nowrap;
}
.lp-write-btn:hover { background: var(--gold-light); transform: translateY(-1px); }

/* ── FEATURED ARTICLE ────────────────────── */
.lp-featured-card {
  position: relative;
  border-radius: 8px;
  overflow: hidden;
  margin-bottom: 2rem;
  background: var(--ink);
  min-height: 340px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  cursor: pointer;
  transition: transform 0.25s;
}
.lp-featured-card:hover { transform: translateY(-2px); }
.lp-featured-img {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  opacity: 0.45;
}
.lp-featured-no-img {
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, var(--ink) 0%, #2a2720 50%, rgba(184,151,58,0.15) 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 5rem;
  opacity: 0.15;
}
.lp-featured-overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(to top, rgba(15,14,11,0.95) 0%, rgba(15,14,11,0.4) 60%, transparent 100%);
}
.lp-featured-body {
  position: relative;
  padding: 1.75rem 2rem;
}
.lp-featured-badge {
  display: inline-block;
  font-family: 'DM Mono', monospace;
  font-size: 0.58rem;
  letter-spacing: 0.18em;
  color: var(--gold);
  background: rgba(184,151,58,0.2);
  border: 1px solid rgba(184,151,58,0.4);
  padding: 0.2rem 0.6rem;
  border-radius: 2px;
  text-transform: uppercase;
  margin-bottom: 0.65rem;
}
.lp-featured-title {
  font-family: 'Playfair Display', serif;
  font-size: clamp(1.3rem, 3vw, 1.9rem);
  font-weight: 700;
  color: var(--white);
  line-height: 1.25;
  margin-bottom: 0.6rem;
  letter-spacing: -0.01em;
}
.lp-featured-summary {
  font-size: 0.97rem;
  color: rgba(245,240,232,0.65);
  line-height: 1.6;
  font-weight: 300;
  max-width: 600px;
  margin-bottom: 1rem;
}
.lp-featured-meta {
  display: flex;
  align-items: center;
  gap: 1rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.08em;
  color: rgba(245,240,232,0.4);
  flex-wrap: wrap;
}
.lp-featured-read {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  background: var(--gold);
  color: var(--ink);
  border: none;
  border-radius: 3px;
  padding: 0.5rem 1rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  cursor: pointer;
  transition: all 0.2s;
  margin-top: 0.25rem;
}
.lp-featured-read:hover { background: var(--gold-light); }

/* ── ARTICLE GRID ────────────────────────── */
.lp-articles-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.5rem;
}
.lp-article-card {
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: 8px;
  overflow: hidden;
  cursor: pointer;
  transition: all 0.25s;
  display: flex;
  flex-direction: column;
}
.lp-article-card:hover {
  border-color: var(--gold);
  transform: translateY(-3px);
  box-shadow: var(--shadow-lg);
}
.lp-card-img-wrap {
  height: 168px;
  background: var(--cream-2);
  overflow: hidden;
  position: relative;
  flex-shrink: 0;
}
.lp-card-img-wrap img {
  width: 100%; height: 100%;
  object-fit: cover;
  transition: transform 0.3s;
}
.lp-article-card:hover .lp-card-img-wrap img { transform: scale(1.04); }
.lp-card-no-img {
  width: 100%; height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2.5rem;
  color: var(--cream-3);
  background: linear-gradient(135deg, var(--cream-2), var(--cream-3));
}
.lp-card-body { padding: 1.25rem; flex: 1; display: flex; flex-direction: column; gap: 0.5rem; }
.lp-card-cat {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.15em;
  color: var(--gold);
  text-transform: uppercase;
}
.lp-card-title {
  font-family: 'Playfair Display', serif;
  font-size: 1.05rem;
  font-weight: 700;
  color: var(--ink);
  line-height: 1.35;
  letter-spacing: -0.01em;
  flex: 1;
}
.lp-card-summary {
  font-size: 0.88rem;
  color: var(--ink-3);
  line-height: 1.6;
  font-weight: 300;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
}
.lp-card-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 0.75rem;
  border-top: 1px solid var(--border-light);
  margin-top: 0.25rem;
}
.lp-card-meta {
  font-family: 'DM Mono', monospace;
  font-size: 0.58rem;
  letter-spacing: 0.06em;
  color: var(--ink-3);
}
.lp-card-actions { display: flex; gap: 0.35rem; }
.lp-card-edit-btn {
  background: none;
  border: 1px solid var(--border-light);
  border-radius: 3px;
  padding: 0.25rem 0.55rem;
  font-size: 0.65rem;
  cursor: pointer;
  color: var(--ink-3);
  transition: all 0.15s;
}
.lp-card-edit-btn:hover { border-color: var(--gold); color: var(--gold); }
.lp-card-del-btn {
  background: none;
  border: 1px solid var(--border-light);
  border-radius: 3px;
  padding: 0.25rem 0.55rem;
  font-size: 0.65rem;
  cursor: pointer;
  color: #dc3545;
  transition: all 0.15s;
}
.lp-card-del-btn:hover { border-color: #dc3545; background: #fff5f5; }

/* ── AUTH BOX ANIMATION ──────────────────── */
#lp-auth-box {
  animation: lp-fadein 0.3s ease;
}
@keyframes lp-fadein { from { opacity:0; transform:translateY(10px); } to { opacity:1; transform:translateY(0); } }

/* ── PORTAL HEADER ENHANCED ─────────────── */
.lp-portal-header {
  background: linear-gradient(135deg, var(--ink) 0%, #1a1816 50%, #0f0e0b 100%);
  padding: 2.5rem 0 2rem;
  border-bottom: 3px solid var(--gold);
  position: relative;
  overflow: hidden;
}
.lp-portal-header::before {
  content: '';
  position: absolute;
  inset: 0;
  background:
    radial-gradient(ellipse 50% 60% at 0% 100%, rgba(184,151,58,0.12) 0%, transparent 60%),
    radial-gradient(ellipse 30% 40% at 100% 0%, rgba(184,151,58,0.07) 0%, transparent 50%);
  pointer-events: none;
}
.lp-portal-header::after {
  content: '§';
  position: absolute;
  right: 4rem;
  top: -1rem;
  font-family: 'Playfair Display', serif;
  font-size: 12rem;
  font-weight: 900;
  color: rgba(184,151,58,0.04);
  line-height: 1;
  pointer-events: none;
  user-select: none;
}

/* ── BREAKING NEWS TICKER ─────────────────── */
.lp-breaking-bar {
  background: var(--gold);
  padding: 0.4rem 0;
  overflow: hidden;
  white-space: nowrap;
}
.lp-breaking-inner {
  display: inline-flex;
  gap: 3rem;
  animation: lp-ticker 30s linear infinite;
  white-space: nowrap;
}
.lp-breaking-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  font-weight: 700;
  letter-spacing: 0.15em;
  color: var(--ink);
  text-transform: uppercase;
  background: var(--ink);
  color: var(--gold);
  padding: 0.2rem 0.6rem;
  border-radius: 2px;
  margin-right: 0.75rem;
}
.lp-breaking-text {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.06em;
  color: var(--ink);
}
@keyframes lp-ticker { 0% { transform: translateX(0); } 100% { transform: translateX(-50%); } }

/* ── ARTICLE CARD ENHANCED ─────────────────── */
.lp-article-card {
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: 10px;
  overflow: hidden;
  cursor: pointer;
  transition: all 0.3s cubic-bezier(.4,0,.2,1);
  display: flex;
  flex-direction: column;
  position: relative;
}
.lp-article-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 3px;
  background: linear-gradient(90deg, var(--gold), var(--gold-light));
  transform: scaleX(0);
  transform-origin: left;
  transition: transform 0.3s ease;
}
.lp-article-card:hover::before { transform: scaleX(1); }
.lp-article-card:hover {
  border-color: var(--gold);
  transform: translateY(-4px);
  box-shadow: 0 16px 48px rgba(15,14,11,0.16);
}

/* ── FEATURED CARD ENHANCED ────────────────── */
.lp-featured-card {
  border-radius: 12px;
  overflow: hidden;
}

/* ── USER STATUS BAR ──────────────────────── */
#lp-user-status-bar {
  background: rgba(184,151,58,0.1);
  border: 1px solid rgba(184,151,58,0.25);
  border-radius: 20px;
  padding: 0.4rem 0.85rem;
}

/* ── SECTION BG ALTERNATING ─────────────────── */
#page-konten {
  background: linear-gradient(180deg, var(--cream) 0%, var(--cream-2) 100%);
}
.lp-portal-inner.lp-portal-body {
  background: transparent;
}

/* ── FILTER BAR ENHANCED ────────────────── */
.lp-filter-bar {
  background: linear-gradient(90deg, var(--ink-2), var(--ink));
  border-bottom: 2px solid rgba(184,151,58,0.3);
  padding: 0;
  overflow-x: auto;
  position: sticky;
  top: 68px;
  z-index: 50;
}

.lp-cat-btn.active {
  background: var(--gold) !important;
  color: var(--ink) !important;
  border-bottom-color: var(--gold) !important;
}


  text-align: center;
  padding: 4rem 2rem;
  background: var(--white);
  border: 2px dashed var(--border-light);
  border-radius: 10px;
}
.lp-empty-icon { font-size: 3rem; margin-bottom: 1rem; }
.lp-empty-title { font-family: 'Playfair Display',serif; font-size: 1.4rem; font-weight: 700; color: var(--ink); margin-bottom: 0.5rem; }
.lp-empty-desc { color: var(--ink-3); font-size: 0.95rem; }

/* ── SIDEBAR ─────────────────────────────── */
.lp-sidebar { display: flex; flex-direction: column; gap: 1.75rem; }
.lp-sidebar-box {
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: 8px;
  padding: 1.25rem;
}
/* ── FORM KIRIM ARTIKEL SIDEBAR ────────────── */
.lp-kirim-box { border-color: var(--gold); }
.lp-kirim-field { margin-bottom: 0.65rem; }
.lp-kirim-input {
  width: 100%;
  padding: 0.55rem 0.75rem;
  background: var(--cream);
  border: 1px solid var(--border-light);
  border-radius: 5px;
  font-family: 'Crimson Pro', serif;
  font-size: 0.9rem;
  color: var(--ink);
  outline: none;
  transition: border-color 0.2s;
  box-sizing: border-box;
}
.lp-kirim-input:focus { border-color: var(--gold); }
.lp-kirim-textarea {
  width: 100%;
  padding: 0.55rem 0.75rem;
  background: var(--cream);
  border: 1px solid var(--border-light);
  border-radius: 5px;
  font-family: 'Crimson Pro', serif;
  font-size: 0.9rem;
  color: var(--ink);
  resize: vertical;
  outline: none;
  transition: border-color 0.2s;
  box-sizing: border-box;
  min-height: 90px;
}
.lp-kirim-textarea:focus { border-color: var(--gold); }
.lp-kirim-btn {
  width: 100%;
  padding: 0.7rem 1rem;
  background: var(--gold);
  color: var(--ink);
  border: none;
  border-radius: 5px;
  font-family: 'DM Mono', monospace;
  font-size: 0.78rem;
  font-weight: 600;
  letter-spacing: 0.05em;
  cursor: pointer;
  transition: background 0.2s, opacity 0.2s;
  margin-top: 0.25rem;
}
.lp-kirim-btn:hover { background: var(--gold-light); }
.lp-kirim-btn:disabled { opacity: 0.6; cursor: not-allowed; }
/* ── /FORM KIRIM ARTIKEL ────────────────────── */
.lp-sidebar-title {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.15em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 1rem;
  padding-bottom: 0.65rem;
  border-bottom: 1px solid var(--border-light);
}
.lp-recent-list { list-style: none; display: flex; flex-direction: column; gap: 0.85rem; }
.lp-recent-list li {
  padding-bottom: 0.85rem;
  border-bottom: 1px solid var(--border-light);
  cursor: pointer;
}
.lp-recent-list li:last-child { border-bottom: none; padding-bottom: 0; }
.lp-recent-title {
  font-family: 'Playfair Display', serif;
  font-size: 0.88rem;
  font-weight: 600;
  color: var(--ink);
  line-height: 1.35;
  margin-bottom: 0.2rem;
  transition: color 0.2s;
}
.lp-recent-list li:hover .lp-recent-title { color: var(--gold); }
.lp-recent-meta {
  font-family: 'DM Mono', monospace;
  font-size: 0.58rem;
  letter-spacing: 0.06em;
  color: var(--ink-3);
}
.lp-cat-list { list-style: none; display: flex; flex-direction: column; gap: 0.5rem; }
.lp-cat-list li {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 0.88rem;
  color: var(--ink-2);
  padding: 0.35rem 0;
  border-bottom: 1px solid var(--border-light);
  cursor: pointer;
  transition: color 0.2s;
}
.lp-cat-list li:hover { color: var(--gold); }
.lp-cat-count {
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  background: var(--cream-2);
  padding: 0.1rem 0.5rem;
  border-radius: 10px;
  color: var(--ink-3);
}

/* ── ADS ─────────────────────────────────── */
.lp-ad-banner {
  background: var(--ink-2);
  border-top: 1px solid rgba(184,151,58,0.2);
  border-bottom: 1px solid rgba(184,151,58,0.2);
  padding: 0.85rem 2rem;
}
.lp-ad-banner-bottom { margin-top: 1rem; }
.lp-ad-content {
  max-width: 1180px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  gap: 1.25rem;
  flex-wrap: wrap;
}
.lp-ad-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.55rem;
  letter-spacing: 0.15em;
  color: rgba(245,240,232,0.25);
  text-transform: uppercase;
  border: 1px solid rgba(245,240,232,0.15);
  padding: 0.1rem 0.4rem;
  border-radius: 2px;
  white-space: nowrap;
  flex-shrink: 0;
}
.lp-ad-logo {
  font-family: 'Playfair Display', serif;
  font-weight: 700;
  font-size: 0.85rem;
  color: var(--gold);
  white-space: nowrap;
  flex-shrink: 0;
}
.lp-ad-text {
  font-size: 0.85rem;
  color: rgba(245,240,232,0.65);
  flex: 1;
  min-width: 160px;
}
.lp-ad-text strong { color: var(--gold-pale); }
.lp-ad-btn {
  display: inline-flex;
  align-items: center;
  background: transparent;
  border: 1px solid rgba(184,151,58,0.5);
  color: var(--gold);
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.08em;
  padding: 0.5rem 1rem;
  border-radius: 3px;
  text-decoration: none;
  transition: all 0.2s;
  white-space: nowrap;
  cursor: pointer;
  flex-shrink: 0;
}
.lp-ad-btn:hover { background: var(--gold); color: var(--ink); }
.lp-ad-sidebar {
  background: var(--ink);
  border: 1px solid rgba(184,151,58,0.25);
  border-radius: 8px;
  overflow: hidden;
}
.lp-ad-sidebar .lp-ad-label {
  display: block;
  padding: 0.4rem 0.75rem;
  background: rgba(184,151,58,0.08);
  border-bottom: 1px solid rgba(184,151,58,0.15);
}
.lp-ad-side-inner { padding: 1.25rem; }
.lp-ad-side-btn {
  display: block;
  text-align: center;
  background: rgba(34,197,94,0.15);
  border: 1px solid rgba(34,197,94,0.4);
  color: #22c55e;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.08em;
  padding: 0.6rem 1rem;
  border-radius: 4px;
  text-decoration: none;
  transition: all 0.2s;
  cursor: pointer;
}
.lp-ad-side-btn:hover { background: rgba(34,197,94,0.25); }

/* ── HERO IMAGE CAPTION ───────────────────── */
.lp-hero-img-caption {
  font-family: 'DM Mono', monospace;
  font-size: 0.72rem;
  letter-spacing: 0.05em;
  color: var(--ink-3);
  text-align: center;
  padding: 0.5rem 1.5rem 0.25rem;
  background: var(--cream-2);
  border-bottom: 1px solid var(--border-light);
  font-style: italic;
  line-height: 1.5;
}

/* ── READ MODAL ─────────────────────────── */
.lp-modal-overlay {
  position: fixed;
  inset: 0;
  background: rgba(15,14,11,0.75);
  z-index: 1000;
  overflow-y: auto;
  padding: 2rem 1rem;
  backdrop-filter: blur(4px);
}
.lp-modal-box {
  background: var(--white);
  border-radius: 10px;
  max-width: 780px;
  margin: 0 auto;
  position: relative;
  overflow: hidden;
}
.lp-modal-close {
  position: absolute;
  top: 1rem; right: 1rem;
  background: rgba(15,14,11,0.08);
  border: none;
  border-radius: 50%;
  width: 34px; height: 34px;
  font-size: 0.9rem;
  cursor: pointer;
  z-index: 10;
  color: var(--ink);
  transition: background 0.2s;
}
.lp-modal-close:hover { background: rgba(15,14,11,0.15); }
.lp-read-ad {
  background: var(--cream-2);
  border-bottom: 1px solid var(--border-light);
  padding: 0.55rem 1.5rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
  flex-wrap: wrap;
}

/* Read content styles */
#lp-read-content { padding: 0; }
.lp-read-hero-img {
  width: 100%;
  max-height: 350px;
  object-fit: cover;
}

/* ── BRANDING LEGALPRENEUR DI AWAL BERITA ── */
.lp-read-brand {
  font-family: 'Playfair Display', Georgia, serif;
  font-size: 0.88rem;
  font-weight: 700;
  letter-spacing: 0.01em;
  line-height: 1;
  margin-bottom: 0.65rem;
  /* Tidak mengganggu baris di bawahnya */
  display: inline-block;
  padding: 0.2rem 0.5rem 0.2rem 0;
}
.lp-read-brand-legal {
  color: var(--ink);
  font-weight: 900;
}
.lp-read-brand-preneur {
  color: var(--gold);
  font-weight: 900;
}
.lp-read-body-wrap { padding: 2rem 2.25rem; }
.lp-read-cat {
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.18em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 0.75rem;
}
.lp-read-title {
  font-family: 'Playfair Display', serif;
  font-size: clamp(1.5rem, 4vw, 2.2rem);
  font-weight: 900;
  line-height: 1.2;
  letter-spacing: -0.02em;
  color: var(--ink);
  margin-bottom: 1rem;
}
.lp-read-byline {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.08em;
  color: var(--ink-3);
  padding: 0.85rem 0;
  border-top: 1px solid var(--border-light);
  border-bottom: 1px solid var(--border-light);
  margin-bottom: 1.5rem;
  flex-wrap: wrap;
  gap: 0.65rem;
}
.lp-read-byline strong { color: var(--ink); }
.lp-byline-author { color: #e07820 !important; font-weight: 600; }
.lp-byline-author strong { color: #e07820 !important; }
.lp-byline-datetime { color: #e07820 !important; font-weight: 600; }

/* Tombol Edit & Hapus di dalam byline */
.lp-read-action-btns {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
  margin-left: auto;
  flex-shrink: 0;
}
.lp-read-edit-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
  background: rgba(184,151,58,0.1);
  border: 1px solid rgba(184,151,58,0.35);
  border-radius: 4px;
  padding: 0.28rem 0.65rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.08em;
  color: var(--gold);
  cursor: pointer;
  transition: all 0.18s;
  white-space: nowrap;
}
.lp-read-edit-btn:hover {
  background: var(--gold);
  color: var(--ink);
  border-color: var(--gold);
}
.lp-read-del-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
  background: rgba(220,53,69,0.07);
  border: 1px solid rgba(220,53,69,0.25);
  border-radius: 4px;
  padding: 0.28rem 0.65rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.08em;
  color: #dc3545;
  cursor: pointer;
  transition: all 0.18s;
  white-space: nowrap;
}
.lp-read-del-btn:hover {
  background: #dc3545;
  color: #fff;
  border-color: #dc3545;
}

/* ── DISCLAIMER ──────────────────────────── */
.lp-read-disclaimer {
  display: flex;
  align-items: flex-start;
  gap: 0.5rem;
  margin-top: 1.75rem;
  padding: 0.75rem 1rem;
  background: var(--cream-2);
  border: 1px solid var(--border-light);
  border-radius: 5px;
  border-left: 3px solid var(--border);
}
.lp-disclaimer-icon {
  font-size: 0.75rem;
  flex-shrink: 0;
  margin-top: 0.1rem;
  opacity: 0.6;
}
.lp-read-disclaimer p {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.03em;
  line-height: 1.65;
  color: var(--ink-3);
  margin: 0;
  font-style: normal;
}
.lp-read-summary-block {
  background: var(--cream);
  border-left: 3px solid var(--gold);
  padding: 1rem 1.25rem;
  font-size: 1.08rem;
  font-style: italic;
  color: var(--ink-2);
  line-height: 1.7;
  margin-bottom: 1.75rem;
  border-radius: 0 4px 4px 0;
}
/* ── WARNA TEKS ARTIKEL: DEFAULT HITAM ──────────────────────────────────
   Teks default hitam. Warna dari span inline style (hasil toolbar warna)
   otomatis menang karena CSS specificity inline > class.
   Tidak ada !important pada base agar warna user tetap tampil.
──────────────────────────────────────────────────────────────────────── */
.lp-read-article-body {
  font-size: 1.08rem;
  line-height: 1.9;
  color: var(--ink);
  letter-spacing: 0.008em;
  border: 1px solid #1a1a1a;
  border-radius: 6px;
  padding: 1.5rem 1.75rem;
  margin: 0.5rem 0;
}
.lp-read-article-body h1 {
  font-family: 'Playfair Display', serif;
  font-size: 1.7rem;
  font-weight: 900;
  color: var(--ink);
  margin: 2.5rem 0 1rem;
  letter-spacing: -0.02em;
  line-height: 1.25;
}
.lp-read-article-body h2 {
  font-family: 'Playfair Display', serif;
  font-size: 1.4rem;
  font-weight: 700;
  color: var(--ink);
  margin: 2.25rem 0 0.85rem;
  letter-spacing: -0.01em;
  line-height: 1.3;
  padding-bottom: 0.4rem;
  border-bottom: 1px solid var(--border-light);
}
.lp-read-article-body h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1.18rem;
  font-weight: 600;
  color: var(--ink);
  margin: 1.85rem 0 0.6rem;
  line-height: 1.35;
}
.lp-read-article-body h4 {
  font-family: 'Crimson Pro', serif;
  font-size: 1.05rem;
  font-weight: 600;
  color: var(--ink);
  margin: 1.5rem 0 0.5rem;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  font-size: 0.9rem;
}
/* Paragraf: jarak antar paragraf proporsional seperti koran */
.lp-read-article-body p {
  margin-bottom: 1.45em;
  text-align: justify;
  hyphens: auto;
}
.lp-read-article-body p:last-child { margin-bottom: 0; }
/* Paragraf pembuka — lebih menonjol (tanpa override warna agar warna user menang) */
.lp-read-article-body p:first-of-type {
  font-size: 1.12rem;
  line-height: 1.95;
}
/* Drop cap DINONAKTIFKAN — huruf pertama sama dengan teks biasa, tidak float, tidak besar */
.lp-read-article-body p:first-of-type::first-letter {
  font-size: inherit !important;
  font-weight: inherit !important;
  line-height: inherit !important;
  float: none !important;
  margin: 0 !important;
  padding: 0 !important;
  color: inherit !important;
  font-family: inherit !important;
}
/* Jika toggle drop cap diaktifkan secara manual */
.lp-read-article-body.dropcap-on p:first-of-type::first-letter {
  font-family: 'Playfair Display', serif !important;
  font-size: 3em !important;
  font-weight: 900 !important;
  line-height: 1 !important;
  float: left !important;
  margin: 0.1em 0.1em 0 0 !important;
  padding: 0 !important;
  color: var(--gold) !important;
}
.lp-read-article-body blockquote {
  border-left: 3px solid var(--gold);
  padding: 1rem 1.5rem;
  margin: 2rem 0;
  background: var(--cream);
  font-style: italic;
  color: var(--ink-2);
  border-radius: 0 6px 6px 0;
  font-size: 1.08rem;
  line-height: 1.8;
}
.lp-read-article-body blockquote cite {
  display: block;
  margin-top: 0.5rem;
  font-size: 0.82rem;
  font-style: normal;
  font-family: 'DM Mono', monospace;
  letter-spacing: 0.06em;
  color: var(--ink-3);
}
.lp-read-article-body ul, .lp-read-article-body ol {
  padding-left: 1.75rem;
  margin: 0.75rem 0 1.5rem;
}
.lp-read-article-body li {
  margin-bottom: 0.55rem;
  line-height: 1.75;
}
.lp-read-article-body li:last-child { margin-bottom: 0; }
.lp-read-article-body hr {
  border: none;
  border-top: 1px solid var(--border-light);
  margin: 2.5rem 0;
}
.lp-read-article-body strong { font-weight: 600; }
.lp-read-article-body a {
  color: var(--gold);
  text-decoration: underline;
  text-decoration-color: rgba(184,151,58,0.4);
  transition: text-decoration-color 0.2s;
}
.lp-read-article-body a:hover { text-decoration-color: var(--gold); }
/* Gambar dalam artikel */
.lp-read-article-body img {
  max-width: 100%;
  height: auto;
  border-radius: 6px;
  margin: 1.5rem 0;
  display: block;
}
.lp-read-article-body figure {
  margin: 2rem 0;
}
.lp-read-article-body figcaption {
  font-family: 'DM Mono', monospace;
  font-size: 0.72rem;
  letter-spacing: 0.05em;
  color: var(--ink-3);
  text-align: center;
  margin-top: 0.5rem;
}
.lp-read-tags {
  display: flex;
  gap: 0.5rem;
  flex-wrap: wrap;
  margin-top: 1.5rem;
  padding-top: 1.5rem;
  border-top: 1px solid var(--border-light);
}
.lp-tag-chip {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.1em;
  color: var(--ink-3);
  background: var(--cream-2);
  border: 1px solid var(--border-light);
  padding: 0.2rem 0.65rem;
  border-radius: 20px;
  text-transform: uppercase;
}
.lp-read-footer { padding: 1.5rem 2.25rem; background: var(--cream); border-top: 1px solid var(--border-light); }

/* ── SHARE BAR UPGRADE ───────────────────── */
.lp-share-section {
  margin-bottom: 1.5rem;
}
.lp-share-section-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.18em;
  color: var(--ink-3);
  text-transform: uppercase;
  margin-bottom: 0.75rem;
  display: flex;
  align-items: center;
  gap: 0.65rem;
}
.lp-share-section-label::before, .lp-share-section-label::after {
  content: '';
  flex: 1;
  height: 1px;
  background: var(--border-light);
}
.lp-share-row {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  flex-wrap: wrap;
}
.lp-share-bar {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  flex-wrap: wrap;
  margin-bottom: 1.25rem;
}
.lp-share-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.1em;
  color: var(--ink-3);
  text-transform: uppercase;
}
.lp-share-btn {
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: 4px;
  padding: 0.45rem 0.85rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.06em;
  cursor: pointer;
  color: var(--ink-2);
  transition: all 0.2s;
}
.lp-share-btn:hover { border-color: var(--gold); color: var(--gold); }

/* Tombol share sosmed spesifik */
.lp-share-btn-wa {
  background: rgba(37,211,102,0.08);
  border-color: rgba(37,211,102,0.35);
  color: #128C7E;
}
.lp-share-btn-wa:hover { background: rgba(37,211,102,0.18); border-color: #25D366; color: #075E54; }
.lp-share-btn-fb {
  background: rgba(24,119,242,0.08);
  border-color: rgba(24,119,242,0.3);
  color: #1877F2;
}
.lp-share-btn-fb:hover { background: rgba(24,119,242,0.18); border-color: #1877F2; color: #0a4fc4; }
.lp-share-btn-ig {
  background: rgba(225,48,108,0.08);
  border-color: rgba(225,48,108,0.3);
  color: #E1306C;
}
.lp-share-btn-ig:hover { background: rgba(225,48,108,0.18); border-color: #E1306C; color: #c41557; }
.lp-share-btn-threads {
  background: rgba(15,14,11,0.05);
  border-color: rgba(15,14,11,0.2);
  color: var(--ink);
}
.lp-share-btn-threads:hover { background: rgba(15,14,11,0.12); border-color: var(--ink); }
.lp-share-btn-x {
  background: rgba(15,14,11,0.05);
  border-color: rgba(15,14,11,0.2);
  color: var(--ink);
}
.lp-share-btn-x:hover { background: rgba(15,14,11,0.12); border-color: var(--ink); }
.lp-share-btn-copy {
  background: var(--gold-pale);
  border-color: var(--border);
  color: var(--ink);
  margin-left: auto;
}
.lp-share-btn-copy:hover { background: var(--gold); color: var(--ink); border-color: var(--gold); }

/* ── IN-ARTICLE AD SLOTS ─────────────────── */
/* Slot iklan di dalam isi berita */
.lp-inread-ad {
  margin: 2rem 0;
  border-radius: 8px;
  overflow: hidden;
  border: 1px solid var(--border-light);
  background: var(--cream);
}
.lp-inread-ad-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.52rem;
  letter-spacing: 0.15em;
  color: var(--ink-3);
  text-transform: uppercase;
  padding: 0.3rem 0.75rem;
  background: var(--cream-2);
  border-bottom: 1px solid var(--border-light);
  display: flex;
  align-items: center;
  gap: 0.5rem;
}
/* Slot Shopee */
.lp-inread-ad-shopee {
  border-color: rgba(238,77,45,0.25);
  background: linear-gradient(135deg, rgba(238,77,45,0.04), rgba(255,140,0,0.04));
}
.lp-inread-ad-shopee .lp-inread-ad-label {
  background: rgba(238,77,45,0.08);
  border-bottom-color: rgba(238,77,45,0.2);
  color: #c94a22;
}
.lp-inread-ad-body {
  padding: 1rem 1.25rem;
  display: flex;
  align-items: center;
  gap: 1rem;
  flex-wrap: wrap;
}
.lp-inread-ad-icon { font-size: 2rem; flex-shrink: 0; }
.lp-inread-ad-text-wrap { flex: 1; min-width: 160px; }
.lp-inread-ad-title {
  font-family: 'Playfair Display', serif;
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 0.2rem;
}
.lp-inread-ad-desc {
  font-size: 0.82rem;
  color: var(--ink-3);
  line-height: 1.55;
  font-weight: 300;
}
.lp-inread-ad-cta {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  padding: 0.55rem 1.1rem;
  border-radius: 4px;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-decoration: none;
  transition: all 0.2s;
  white-space: nowrap;
  flex-shrink: 0;
  cursor: pointer;
  border: none;
}
.lp-inread-ad-shopee .lp-inread-ad-cta {
  background: #EE4D2D;
  color: #fff;
}
.lp-inread-ad-shopee .lp-inread-ad-cta:hover { background: #d4401f; transform: translateY(-1px); }
/* Slot Lynk.id / Produk Digital */
.lp-inread-ad-lynk {
  border-color: rgba(99,102,241,0.25);
  background: linear-gradient(135deg, rgba(99,102,241,0.04), rgba(168,85,247,0.04));
}
.lp-inread-ad-lynk .lp-inread-ad-label {
  background: rgba(99,102,241,0.08);
  border-bottom-color: rgba(99,102,241,0.2);
  color: #4f46e5;
}
.lp-inread-ad-lynk .lp-inread-ad-cta {
  background: linear-gradient(135deg, #6366f1, #a855f7);
  color: #fff;
}
.lp-inread-ad-lynk .lp-inread-ad-cta:hover { opacity: 0.9; transform: translateY(-1px); }
/* Slot Iklan kosong / kustom */
.lp-inread-ad-custom {
  border: 2px dashed var(--border);
  background: transparent;
}
.lp-inread-ad-custom .lp-inread-ad-label { background: var(--cream-2); }
.lp-inread-ad-custom .lp-inread-ad-cta {
  background: var(--gold);
  color: var(--ink);
}
.lp-inread-ad-custom .lp-inread-ad-cta:hover { background: var(--gold-light); }

/* ── SLOT IKLAN DI FOOTER ARTIKEL ────────── */
.lp-read-ad-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0.85rem;
  margin-top: 1rem;
}
@media (max-width: 540px) { .lp-read-ad-grid { grid-template-columns: 1fr; } }
.lp-read-ad-bottom {
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: 6px;
  padding: 1rem 1.25rem;
}

/* ── EDITOR MODAL ───────────────────────── */
.lp-editor-box {
  max-width: 860px;
  background: var(--ink-2);
}
.lp-editor-header {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  padding: 1.5rem 2rem;
  background: var(--ink);
  border-bottom: 2px solid var(--gold);
}
.lp-editor-body { padding: 1.75rem 2rem; overflow-y: auto; max-height: calc(100vh - 180px); }
.lp-field-group { display: flex; flex-direction: column; gap: 0.4rem; margin-bottom: 1.25rem; }
.lp-field-row { display: flex; gap: 1rem; margin-bottom: 1.25rem; }
.lp-field-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.12em;
  color: var(--gold-pale);
  text-transform: uppercase;
}
.lp-required { color: #f87171; }
.lp-field-input {
  background: rgba(245,240,232,0.06);
  border: 1px solid rgba(184,151,58,0.25);
  border-radius: 5px;
  padding: 0.65rem 0.85rem;
  font-family: 'Crimson Pro', serif;
  font-size: 1rem;
  color: var(--white);
  outline: none;
  transition: border-color 0.2s;
  width: 100%;
}
.lp-field-input:focus { border-color: var(--gold); background: rgba(245,240,232,0.09); }
.lp-field-input::placeholder { color: rgba(245,240,232,0.25); }
.lp-field-textarea { resize: vertical; min-height: 80px; }
.lp-field-select { color: var(--white); cursor: pointer; }
.lp-field-select option { background: var(--ink-2); color: var(--white); }
.lp-field-hint {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.06em;
  color: rgba(245,240,232,0.3);
}

/* Template grid */
.lp-template-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap: 0.65rem; }
.lp-tpl-card {
  background: rgba(245,240,232,0.05);
  border: 1px solid rgba(184,151,58,0.2);
  border-radius: 5px;
  padding: 0.75rem 1rem;
  cursor: pointer;
  transition: all 0.2s;
}
.lp-tpl-card:hover { border-color: var(--gold); background: rgba(184,151,58,0.08); }
.lp-tpl-icon { font-size: 1.1rem; margin-bottom: 0.3rem; }
.lp-tpl-name { font-family: 'DM Mono', monospace; font-size: 0.62rem; letter-spacing: 0.1em; color: var(--gold); text-transform: uppercase; margin-bottom: 0.2rem; }
.lp-tpl-title { font-family: 'Crimson Pro', serif; font-size: 0.88rem; color: var(--gold-pale); line-height: 1.35; font-weight: 500; }

/* Image upload */
.lp-img-upload-area {
  border: 2px dashed rgba(184,151,58,0.3);
  border-radius: 6px;
  cursor: pointer;
  transition: border-color 0.2s;
  overflow: hidden;
}
.lp-img-upload-area:hover { border-color: var(--gold); }
.lp-img-placeholder {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  padding: 2rem;
  color: rgba(245,240,232,0.3);
  font-size: 0.85rem;
  text-align: center;
  min-height: 120px;
}

/* Editor toolbar */
.lp-editor-toolbar {
  display: flex;
  align-items: center;
  gap: 0.25rem;
  padding: 0.5rem 0.65rem;
  background: rgba(245,240,232,0.04);
  border: 1px solid rgba(184,151,58,0.2);
  border-bottom: none;
  flex-wrap: wrap;
}
.lp-toolbar-row1 {
  border-radius: 5px 5px 0 0;
  border-bottom: 1px solid rgba(184,151,58,0.1);
}
.lp-toolbar-row2 {
  border-radius: 0;
  border-bottom: 1px solid rgba(184,151,58,0.15);
}
.lp-tb-btn {
  background: rgba(245,240,232,0.06);
  border: 1px solid rgba(184,151,58,0.15);
  border-radius: 3px;
  padding: 0.28rem 0.55rem;
  font-size: 0.78rem;
  color: var(--gold-pale);
  cursor: pointer;
  transition: all 0.15s;
  min-width: 28px;
  user-select: none;
}
.lp-tb-btn:hover { background: rgba(184,151,58,0.18); border-color: var(--gold); color: var(--gold); }
.lp-tb-btn:active { background: rgba(184,151,58,0.3); }
.lp-tb-align { min-width: 30px; font-size: 0.85rem; }
.lp-tb-sep { width: 1px; height: 20px; background: rgba(184,151,58,0.2); margin: 0 0.15rem; flex-shrink: 0; }

/* Select dropdown di toolbar */
.lp-tb-select {
  background: rgba(245,240,232,0.06);
  border: 1px solid rgba(184,151,58,0.2);
  border-radius: 4px;
  padding: 0.28rem 0.5rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.04em;
  color: var(--gold-pale);
  cursor: pointer;
  outline: none;
  transition: border-color 0.2s;
  max-width: 170px;
}
.lp-tb-select-sm { max-width: 120px; }
.lp-tb-select option { background: var(--ink-2); color: var(--white); font-family: sans-serif; }
.lp-tb-select:focus { border-color: var(--gold); }

/* Color picker wrapper */
.lp-tb-color-wrap {
  position: relative;
  display: flex;
  align-items: center;
  cursor: pointer;
}
.lp-tb-color-label {
  background: rgba(245,240,232,0.06);
  border: 1px solid rgba(184,151,58,0.2);
  border-radius: 3px;
  padding: 0.28rem 0.45rem;
  font-size: 0.78rem;
  font-weight: 700;
  color: var(--gold-pale);
  min-width: 28px;
  text-align: center;
  transition: all 0.15s;
  user-select: none;
}
.lp-tb-color-wrap:hover .lp-tb-color-label { border-color: var(--gold); }
.lp-tb-colorpick {
  position: absolute;
  left: 0; top: 0;
  width: 100%; height: 100%;
  opacity: 0;
  cursor: pointer;
  border: none;
  padding: 0;
}
.lp-editor-area {
  min-height: 320px;
  padding: 1.1rem 1.1rem;
  background: rgba(245,240,232,0.06);
  border: 1px solid rgba(184,151,58,0.25);
  border-top: none;
  border-radius: 0 0 5px 5px;
  color: var(--white);
  outline: none;
  font-family: 'Crimson Pro', serif;
  font-size: 1.05rem;
  line-height: 1.85;
  overflow-y: auto;
}
.lp-editor-area:focus { border-color: var(--gold); }
.lp-editor-area h2, .lp-editor-area h3 { font-family: 'Playfair Display', serif; color: var(--gold-pale); margin: 1rem 0 0.5rem; }
.lp-editor-area blockquote { border-left: 3px solid var(--gold); padding-left: 1rem; color: rgba(245,240,232,0.65); font-style: italic; }

/* Buttons */
.lp-editor-actions { display: flex; gap: 0.75rem; flex-wrap: wrap; margin-top: 1rem; }
.lp-btn-ghost {
  background: rgba(245,240,232,0.06);
  border: 1px solid rgba(245,240,232,0.2);
  border-radius: 4px;
  padding: 0.6rem 1.1rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  letter-spacing: 0.08em;
  color: var(--gold-pale);
  cursor: pointer;
  transition: all 0.2s;
}
.lp-btn-ghost:hover { border-color: var(--gold); color: var(--gold); }
.lp-btn-publish {
  background: var(--gold);
  border: none;
  border-radius: 4px;
  padding: 0.6rem 1.5rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  color: var(--ink);
  cursor: pointer;
  transition: all 0.2s;
  margin-left: auto;
}
.lp-btn-publish:hover { background: var(--gold-light); transform: translateY(-1px); }
.lp-btn-sm {
  background: rgba(245,240,232,0.06);
  border: 1px solid rgba(184,151,58,0.2);
  border-radius: 4px;
  padding: 0.4rem 0.65rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  color: var(--gold-pale);
  cursor: pointer;
  white-space: nowrap;
}
.lp-btn-sm:hover { border-color: var(--gold); }

/* ── RESPONSIVE ─────────────────────────── */
@media (max-width: 860px) {
  .lp-portal-inner.lp-portal-body { grid-template-columns: 1fr; }
  .lp-sidebar { order: -1; display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
  .lp-ad-sidebar { grid-column: 1/-1; }
  .lp-portal-header .lp-portal-inner { flex-direction: column; align-items: flex-start; }
  .lp-portal-meta { flex-direction: row; align-items: center; }
}
@media (max-width: 600px) {
  .lp-portal-inner { padding: 0 1.25rem; }
  .lp-portal-body { padding-top: 1.5rem !important; }
  .lp-articles-grid { grid-template-columns: 1fr; }
  .lp-sidebar { grid-template-columns: 1fr; }
  .lp-editor-body { padding: 1.25rem; }
  .lp-editor-header { padding: 1.1rem 1.25rem; }
  .lp-field-row { flex-direction: column; gap: 0; }
  .lp-read-body-wrap { padding: 1.25rem; }
  .lp-read-footer { padding: 1.25rem; }
  .lp-template-grid { grid-template-columns: 1fr 1fr; }
  .lp-editor-actions { flex-direction: column; }
  .lp-btn-publish { margin-left: 0; }
  .lp-ad-content { flex-direction: column; align-items: flex-start; gap: 0.75rem; }
}
</style>

<!-- PRODUK REKOMENDASI SHOPEE PAGE -->
<section class="content-section" id="page-affiliate" style="display:none;">
  <div class="container">
    <div class="section-tag">Produk Rekomendasi</div>
    <h2 class="section-title" style="margin-bottom: 0.75rem;">Katalog Produk <em>Rekomendasi</em></h2>
    <p class="section-lead" style="margin-bottom: 2rem;">Produk-produk berkualitas yang telah terseleksi secara personal — dari kebutuhan produktivitas hingga gaya hidup sehari-hari.</p>
    <div class="shopee-search-wrap">
      <input class="shopee-search" id="shopee-search" type="text" placeholder="🔍  Cari nama produk..." oninput="filterShopee(this.value)">
      <span class="shopee-count" id="shopee-count"></span>
    </div>
    <div class="shopee-grid" id="shopee-grid"></div>
    <!-- PAGINATION -->
    <div class="shopee-pagination" id="shopee-pagination"></div>
  </div>
  <div class="page-mini-footer">
    <button onclick="showPage('home')" class="mini-back-btn">← Kembali ke Beranda</button>
    <span>LegalPreneur · Novrizal, S.I.Kom., S.H., CPM</span>
    <a href="https://wa.me/6281262195937" target="_blank">WhatsApp: 0812-6219-5937</a>
  </div>
</section>

<!-- PRODUK DIGITAL PAGE -->
<section class="content-section" id="page-digital" style="display:none;">
  <div class="container">
    <div class="section-tag">Produk Digital</div>
    <h2 class="section-title" style="margin-bottom: 0.75rem;">E-Book, Game & <em>Simulasi Interaktif</em></h2>
    <p class="section-lead" style="margin-bottom: 3rem;">Karya digital eksklusif oleh Novrizal — tersedia di Lynk.id dan Amazon. Mulai dari panduan hukum praktis hingga game edukasi dan simulasi tes CPNS.</p>
    <div class="content-grid">
      <a href="http://lynk.id/novriz.digital/qp2p592qwj84" target="_blank" class="content-card">
        <div class="content-card-icon">📖</div>
        <div class="content-card-tag">E-Book Hukum · Lynk.id</div>
        <div class="content-card-title">Panduan Menghadapi Debt Collector</div>
        <p class="content-card-desc">Hak-hak Anda sebagai debitur, cara legal menghadapi tekanan penagihan, dan langkah hukum yang bisa ditempuh.</p>
        <div class="content-card-link">Dapatkan di Lynk.id →</div>
      </a>
      <a href="http://lynk.id/novriz.digital/z4q46p9evexv" target="_blank" class="content-card">
        <div class="content-card-icon">💼</div>
        <div class="content-card-tag">E-Book Hukum · Lynk.id</div>
        <div class="content-card-title">Adil di atas Kertas</div>
        <p class="content-card-desc">Legalitas usaha online, perlindungan hak cipta, kontrak digital, dan regulasi e-commerce yang wajib dipahami.</p>
        <div class="content-card-link">Dapatkan di Lynk.id →</div>
      </a>
      <a href="https://www.amazon.com/dp/B0GRJL9XFM" target="_blank" class="content-card">
        <div class="content-card-icon">📕</div>
        <div class="content-card-tag">E-Book Novel · Amazon</div>
        <div class="content-card-title">Novel Geopolitik (Amazon)</div>
        <p class="content-card-desc">Narasi fiksi bertensi tinggi yang mengeksplorasi dinamika kekuasaan dan konsekuensi hukum internasional.</p>
        <div class="content-card-link">Beli di Amazon →</div>
      </a>
      <a href="https://a.co/d/013vts5G" target="_blank" class="content-card">
        <div class="content-card-icon">🌍</div>
        <div class="content-card-tag">E-Book Novel · Amazon</div>
        <div class="content-card-title">Novel Eksklusif — Amazon Store</div>
        <p class="content-card-desc">Karya fiksi terbaru tersedia di platform Amazon untuk pembaca global yang menginginkan cerita berkualitas tinggi.</p>
        <div class="content-card-link">Beli di Amazon →</div>
      </a>
      <a href="http://lynk.id/novriz.digital/8lzqkld4z42m" target="_blank" class="content-card">
        <div class="content-card-icon">🎮</div>
        <div class="content-card-tag">Game Edukasi Hukum · Lynk.id</div>
        <div class="content-card-title">Game Edukasi Hukum Interaktif</div>
        <p class="content-card-desc">Belajar hukum dengan cara yang menyenangkan melalui game interaktif yang dirancang khusus untuk meningkatkan literasi hukum masyarakat.</p>
        <div class="content-card-link">Dapatkan di Lynk.id →</div>
      </a>
      <a href="http://lynk.id/novriz.digital/dlp846yqpp7y" target="_blank" class="content-card">
        <div class="content-card-icon">📝</div>
        <div class="content-card-tag">Simulasi CPNS/ASN · Lynk.id</div>
        <div class="content-card-title">Simulasi Interaktif Tes CPNS/ASN</div>
        <p class="content-card-desc">Persiapkan diri menghadapi tes CPNS/ASN dengan simulasi interaktif yang komprehensif, akurat, dan terpercaya.</p>
        <div class="content-card-link">Dapatkan di Lynk.id →</div>
      </a>
      <a href="http://lynk.id/novriz.digital/9yvm9n4evyke" target="_blank" class="content-card">
        <div class="content-card-icon">🛒</div>
        <div class="content-card-tag">E-Book · Lynk.id</div>
        <div class="content-card-title">Panduan Praktis Jualan Produk Digital</div>
        <p class="content-card-desc">Panduan lengkap dan praktis untuk memulai dan mengembangkan bisnis jualan produk digital secara efektif dan menguntungkan.</p>
        <div class="content-card-link">Dapatkan di Lynk.id →</div>
      </a>
    </div>
  </div>
  <div class="page-mini-footer">
    <button onclick="showPage('home')" class="mini-back-btn">← Kembali ke Beranda</button>
    <span>LegalPreneur · Novrizal, S.I.Kom., S.H., CPM</span>
    <a href="https://wa.me/6281262195937" target="_blank">WhatsApp: 0812-6219-5937</a>
  </div>
</section>
<section class="consult-section" id="konsultasi">
  <div class="container">
    <div class="consult-inner">
      <div>
        <div class="consult-label">Konsultasi Hukum</div>
        <h2 class="consult-title">Ada Pertanyaan <em>Hukum</em>?<br>Kami Siap Membantu.</h2>
        <p class="consult-desc">
          Sampaikan permasalahan hukum Anda — tanpa biaya, tanpa basa-basi. Tim kami akan memberikan panduan awal yang jelas, praktis, dan berintegritas untuk membantu Anda mengambil langkah yang tepat.
        </p>
        <div style="margin-top: 2rem; display: flex; gap: 1.5rem; flex-wrap: wrap;">
          <div style="display: flex; align-items: center; gap: 0.5rem; font-family: 'DM Mono', monospace; font-size: 0.7rem; letter-spacing: 0.1em; color: rgba(245,240,232,0.55);">
            <span style="color: #22c55e;">✓</span> GRATIS untuk konsultasi awal
          </div>
          <div style="display: flex; align-items: center; gap: 0.5rem; font-family: 'DM Mono', monospace; font-size: 0.7rem; letter-spacing: 0.1em; color: rgba(245,240,232,0.55);">
            <span style="color: #22c55e;">✓</span> Respons dalam 1×24 jam
          </div>
          <div style="display: flex; align-items: center; gap: 0.5rem; font-family: 'DM Mono', monospace; font-size: 0.7rem; letter-spacing: 0.1em; color: rgba(245,240,232,0.55);">
            <span style="color: #22c55e;">✓</span> Kerahasiaan terjaga
          </div>
        </div>
        <div style="margin-top: 1.75rem; display: flex; flex-direction: column; gap: 0.65rem;">
          <a href="https://wa.me/6281262195937" target="_blank" style="display:inline-flex;align-items:center;gap:0.6rem;color:#22c55e;text-decoration:none;font-family:'DM Mono',monospace;font-size:0.75rem;letter-spacing:0.08em;">
            📱 WhatsApp: 0812-6219-5937
          </a>
          <a href="tel:085270707883" style="display:inline-flex;align-items:center;gap:0.6rem;color:rgba(245,240,232,0.65);text-decoration:none;font-family:'DM Mono',monospace;font-size:0.75rem;letter-spacing:0.08em;">
            📞 Telepon: 0852-7070-7883
          </a>
          <a href="mailto:novrizal.tan2@gmail.com" style="display:inline-flex;align-items:center;gap:0.6rem;color:rgba(245,240,232,0.65);text-decoration:none;font-family:'DM Mono',monospace;font-size:0.75rem;letter-spacing:0.08em;">
            ✉️ novrizal.tan2@gmail.com
          </a>
        </div>
      </div>

      <div class="consult-form">
        <form onsubmit="handleConsult(event)">
          <label class="form-label" for="c-name">Nama Lengkap</label>
          <input class="form-input" id="c-name" type="text" placeholder="Nama Anda" required>

          <label class="form-label" for="c-contact">Email / WhatsApp</label>
          <input class="form-input" id="c-contact" type="text" placeholder="Email atau nomor WhatsApp" required>

          <label class="form-label" for="c-msg">Pertanyaan / Permasalahan</label>
          <textarea class="form-input" id="c-msg" placeholder="Ceritakan permasalahan hukum Anda secara singkat..." required></textarea>

          <button type="submit" class="form-submit" id="consult-btn">Kirim Konsultasi →</button>
          <div id="consult-msg" style="display:none; text-align:center; color:#22c55e; font-family:'DM Mono',monospace; font-size:0.72rem; margin-top:0.75rem; letter-spacing:0.05em; line-height:1.6;"></div>
          <p class="form-note">Informasi Anda bersifat rahasia dan tidak akan disebarluaskan.</p>
        </form>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer id="kontak">
  <div class="container">
    <div class="footer-grid">
      <div class="footer-brand">
        <div class="logo-text">Legal<span>Preneur</span></div>
        <span class="logo-sub">Advokat - Mediator Non Hakim - Konsultan Hukum</span>
        <p>Platform hukum, literasi, dan gaya hidup digital terpercaya oleh Novrizal, S.I.Kom., S.H., CPM.</p>
        <div style="margin-top: 1.25rem; display: flex; flex-direction: column; gap: 0.5rem;">
          <a href="https://wa.me/6281262195937" target="_blank" style="color:#22c55e;text-decoration:none;font-family:'DM Mono',monospace;font-size:0.68rem;letter-spacing:0.06em;">📱 WA: 0812-6219-5937</a>
          <a href="tel:085270707883" style="color:rgba(245,240,232,0.5);text-decoration:none;font-family:'DM Mono',monospace;font-size:0.68rem;letter-spacing:0.06em;">📞 Tel: 0852-7070-7883</a>
          <a href="mailto:novrizal.tan2@gmail.com" style="color:rgba(245,240,232,0.5);text-decoration:none;font-family:'DM Mono',monospace;font-size:0.68rem;letter-spacing:0.06em;">✉️ novrizal.tan2@gmail.com</a>
        </div>
      </div>

      <div>
        <div class="footer-col-title">Navigasi</div>
        <ul class="footer-links">
          <li><a href="#" onclick="showPage('home');return false;">Beranda</a></li>
          <li><a href="#" onclick="showPage('home');setTimeout(()=>document.getElementById('layanan').scrollIntoView({behavior:'smooth'}),50);return false;">Layanan</a></li>
          <li><a href="#" onclick="showPage('konten');return false;">Konten</a></li>
          <li><a href="#" onclick="showPage('affiliate');return false;">Produk Rekomendasi</a></li>
          <li><a href="#" onclick="showPage('digital');return false;">Produk Digital</a></li>
          <li><a href="#konsultasi">Konsultasi</a></li>
        </ul>
      </div>

      <div>
        <div class="footer-col-title">Layanan Hukum</div>
        <ul class="footer-links">
          <li><a href="#" onclick="showPage('home');setTimeout(()=>document.getElementById('layanan').scrollIntoView({behavior:'smooth'}),50);return false;">Konsultasi Online</a></li>
          <li><a href="#" onclick="showPage('home');setTimeout(()=>document.getElementById('layanan').scrollIntoView({behavior:'smooth'}),50);return false;">Penyusunan Kontrak</a></li>
          <li><a href="#" onclick="showPage('home');setTimeout(()=>document.getElementById('layanan').scrollIntoView({behavior:'smooth'}),50);return false;">Verifikasi Legalitas</a></li>
          <li><a href="#" onclick="showPage('home');setTimeout(()=>document.getElementById('layanan').scrollIntoView({behavior:'smooth'}),50);return false;">Edukasi Hukum</a></li>
          <li><a href="#" onclick="showPage('home');setTimeout(()=>document.getElementById('layanan').scrollIntoView({behavior:'smooth'}),50);return false;">Mediasi</a></li>
        </ul>
      </div>

      <div>
        <div class="footer-col-title">Media Sosial</div>
        <ul class="footer-links">
          <li><a href="https://web.facebook.com/novriz.digital" target="_blank">Facebook</a></li>
          <li><a href="https://www.instagram.com/novriz_dct/" target="_blank">Instagram</a></li>
          <li><a href="https://www.tiktok.com/@novriz77?is_from_webapp=1&sender_device=pc" target="_blank">TikTok</a></li>
          <li><a href="https://www.threads.com/@novriz_dct" target="_blank">Threads</a></li>
          <li><a href="https://x.com/Novriz_Tan" target="_blank">X (Twitter)</a></li>
        </ul>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="footer-copy">
        © 2025 LegalPreneur · Novrizal, S.I.Kom., S.H., CPM ·
        <a href="https://sites.google.com/view/legalpreneur" target="_blank">legalpreneur.site</a>
      </div>
      <ul class="footer-bottom-links">
        <li><a href="#">Kebijakan Privasi</a></li>
        <li><a href="#">Syarat & Ketentuan</a></li>
        <li><a href="#konsultasi">Hubungi Kami</a></li>
      </ul>
    </div>
  </div>
</footer>

<style>
/* Shopee grid */
.shopee-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.5rem;
}
.shopee-card {
  background: var(--white);
  border: 1.5px solid var(--border-light);
  border-radius: 10px;
  padding: 0;
  display: flex;
  flex-direction: column;
  transition: all 0.25s cubic-bezier(.2,.8,.2,1);
  text-decoration: none;
  color: inherit;
  overflow: hidden;
  box-shadow: 0 2px 10px rgba(15,14,11,0.06);
}
.shopee-card:hover {
  border-color: var(--gold);
  transform: translateY(-4px);
  box-shadow: 0 8px 32px rgba(184,151,58,0.18);
}
.shopee-card-header {
  background: linear-gradient(135deg, var(--ink) 0%, #2a2720 100%);
  padding: 0.85rem 1.25rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}
.shopee-card-num {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.12em;
  color: var(--gold);
  background: rgba(184,151,58,0.15);
  border: 1px solid rgba(184,151,58,0.3);
  padding: 0.2rem 0.55rem;
  border-radius: 20px;
  white-space: nowrap;
  flex-shrink: 0;
}
.shopee-card-badge {
  font-family: 'DM Mono', monospace;
  font-size: 0.55rem;
  letter-spacing: 0.1em;
  color: rgba(245,240,232,0.4);
  text-transform: uppercase;
}
.shopee-card-body {
  padding: 1.25rem 1.4rem;
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.shopee-card-name {
  font-family: 'Crimson Pro', serif;
  font-size: 1.08rem;
  font-weight: 600;
  color: var(--ink);
  line-height: 1.5;
  letter-spacing: 0;
  flex: 1;
}
.shopee-card-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 0.45rem;
  background: #f05123;
  color: #fff !important;
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  font-weight: 600;
  letter-spacing: 0.08em;
  padding: 0.65rem 1rem;
  border-radius: 6px;
  transition: background 0.2s;
  text-transform: uppercase;
  text-decoration: none;
}
.shopee-card:hover .shopee-card-link { background: #d9421a; }
.shopee-search-wrap {
  margin-bottom: 2rem;
  display: flex;
  gap: 0.75rem;
  align-items: center;
  flex-wrap: wrap;
}
.shopee-search {
  flex: 1;
  min-width: 200px;
  background: var(--white);
  border: 1.5px solid var(--border-light);
  border-radius: 8px;
  padding: 0.7rem 1.1rem;
  font-family: 'Crimson Pro', serif;
  font-size: 1rem;
  color: var(--ink);
  outline: none;
  transition: border-color 0.2s;
}
.shopee-search:focus { border-color: var(--gold); }
.shopee-search::placeholder { color: var(--ink-3); }
.shopee-count {
  font-family: 'DM Mono', monospace;
  font-size: 0.7rem;
  letter-spacing: 0.08em;
  color: var(--ink-3);
  white-space: nowrap;
}
/* Page sections container */
.page-home-wrapper > section,
.page-home-wrapper > div.hero { display: block; }

/* ══════════════════════════════════════
   SHOPEE PAGINATION
══════════════════════════════════════ */
.shopee-pagination {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.4rem;
  margin-top: 2.5rem;
  flex-wrap: wrap;
}
.pg-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 38px;
  height: 38px;
  padding: 0 0.65rem;
  border: 1.5px solid var(--border-light);
  background: var(--white);
  color: var(--ink-2);
  font-family: 'DM Mono', monospace;
  font-size: 0.72rem;
  letter-spacing: 0.04em;
  border-radius: 6px;
  cursor: pointer;
  transition: all 0.2s;
  user-select: none;
}
.pg-btn:hover:not(:disabled) {
  border-color: var(--gold);
  color: var(--gold);
  background: var(--gold-pale);
}
.pg-btn.active {
  background: var(--ink);
  border-color: var(--ink);
  color: var(--gold);
  font-weight: 700;
}
.pg-btn:disabled {
  opacity: 0.35;
  cursor: not-allowed;
}
.pg-ellipsis {
  font-family: 'DM Mono', monospace;
  font-size: 0.72rem;
  color: var(--ink-3);
  padding: 0 0.3rem;
  user-select: none;
}
.pg-info {
  width: 100%;
  text-align: center;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.08em;
  color: var(--ink-3);
  margin-top: 0.75rem;
}

@media (max-width: 600px) {
  .shopee-grid { grid-template-columns: 1fr; gap: 1rem; }
  .shopee-search-wrap { flex-direction: column; align-items: stretch; gap: 0.6rem; }
  .shopee-search { min-width: unset; font-size: 0.95rem; }
  .shopee-count { text-align: right; }
  .shopee-pagination { gap: 0.3rem; margin-top: 1.75rem; }
  .pg-btn { min-width: 34px; height: 34px; font-size: 0.68rem; padding: 0 0.5rem; }
  .content-grid { grid-template-columns: 1fr; gap: 1rem; }
  .content-card { padding: 1.25rem; }
}

/* ══════════════════════════════════════
   MINI FOOTER (halaman non-home)
══════════════════════════════════════ */
.page-mini-footer {
  background: var(--ink-2);
  border-top: 1px solid rgba(184,151,58,0.2);
  padding: 1.5rem 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 1rem;
  margin-top: 3rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  letter-spacing: 0.06em;
}
.page-mini-footer span {
  color: rgba(245,240,232,0.4);
}
.page-mini-footer a {
  color: var(--gold);
  text-decoration: none;
}
.page-mini-footer a:hover { opacity: 0.75; }
.mini-back-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  background: var(--gold);
  color: var(--ink);
  border: none;
  border-radius: 4px;
  padding: 0.55rem 1.1rem;
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.06em;
  cursor: pointer;
  transition: all 0.2s;
}
.mini-back-btn:hover {
  background: var(--gold-light);
  transform: translateY(-1px);
}
@media (max-width: 600px) {
  .page-mini-footer {
    flex-direction: column;
    align-items: flex-start;
    padding: 1.25rem 1.25rem;
    gap: 0.75rem;
  }
  .mini-back-btn { width: 100%; justify-content: center; }
}

/* ══════════════════════════════════════
   INSIGHT BOX — SIDEBAR
══════════════════════════════════════ */
.lp-insight-box {
  border: 1px solid rgba(184,151,58,0.25) !important;
}
.lp-insight-stats {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0.75rem;
  margin-bottom: 1.25rem;
}
.lp-insight-stat {
  background: var(--cream-2);
  border-radius: 6px;
  padding: 0.75rem 0.6rem;
  text-align: center;
  border: 1px solid var(--border-light);
}
.lp-insight-num {
  font-family: 'Playfair Display', serif;
  font-size: 1.5rem;
  font-weight: 700;
  color: var(--ink);
  letter-spacing: -0.03em;
  line-height: 1;
}
.lp-insight-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.55rem;
  letter-spacing: 0.1em;
  color: var(--ink-3);
  text-transform: uppercase;
  margin-top: 0.25rem;
  line-height: 1.3;
}
.lp-insight-chart-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.12em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 0.6rem;
}
.lp-cat-chart { display:flex; flex-direction:column; gap:0.4rem; }
.lp-cat-bar-row {
  display: flex;
  align-items: center;
  gap: 0.5rem;
}
.lp-cat-bar-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.58rem;
  color: var(--ink-3);
  width: 70px;
  flex-shrink: 0;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.lp-cat-bar-track {
  flex: 1;
  background: var(--cream-3);
  border-radius: 3px;
  height: 6px;
  overflow: hidden;
}
.lp-cat-bar-fill {
  height: 100%;
  background: var(--gold);
  border-radius: 3px;
  transition: width 0.6s ease;
}
.lp-cat-bar-count {
  font-family: 'DM Mono', monospace;
  font-size: 0.58rem;
  color: var(--gold);
  width: 20px;
  text-align: right;
  flex-shrink: 0;
}

/* ══════════════════════════════════════
   DASHBOARD OWNER
══════════════════════════════════════ */
.dash-login-box {
  background: var(--white);
  border: 1px solid var(--border);
  border-radius: 12px;
  padding: 3rem 2.5rem;
  max-width: 420px;
  width: 100%;
  text-align: center;
  box-shadow: var(--shadow-xl);
}
.dash-login-logo { font-size: 3rem; margin-bottom: 1rem; }
.dash-login-title {
  font-family: 'Playfair Display', serif;
  font-size: 1.6rem;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 0.5rem;
}
.dash-login-sub {
  font-size: 0.95rem;
  color: var(--ink-3);
  line-height: 1.6;
  margin-bottom: 1.5rem;
  font-weight: 300;
}
.dash-pw-input {
  width: 100%;
  background: var(--cream);
  border: 1px solid var(--border);
  border-radius: 6px;
  padding: 0.85rem 1rem;
  font-family: 'Crimson Pro', serif;
  font-size: 1.05rem;
  color: var(--ink);
  margin-bottom: 0.85rem;
  outline: none;
  transition: border-color 0.2s;
  text-align: center;
  letter-spacing: 0.15em;
}
.dash-pw-input:focus { border-color: var(--gold); }
.dash-pw-btn {
  width: 100%;
  background: var(--ink);
  color: var(--gold-pale);
  border: none;
  border-radius: 6px;
  padding: 0.9rem 1rem;
  font-family: 'Crimson Pro', serif;
  font-size: 1.05rem;
  font-weight: 700;
  cursor: pointer;
  transition: all 0.2s;
  margin-bottom: 1rem;
}
.dash-pw-btn:hover { background: var(--gold); color: var(--ink); }
.dash-back-link {
  background: none;
  border: none;
  color: var(--ink-3);
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.1em;
  cursor: pointer;
  text-decoration: underline;
  transition: color 0.2s;
}
.dash-back-link:hover { color: var(--gold); }

.dash-header {
  background: var(--ink);
  border-bottom: 3px solid var(--gold);
  padding: 2rem 0;
}
.dash-header-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  gap: 1.5rem;
  flex-wrap: wrap;
}
.dash-header-tag {
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.2em;
  color: var(--gold);
  text-transform: uppercase;
  background: rgba(184,151,58,0.12);
  padding: 0.3rem 0.75rem;
  border-radius: 2px;
  display: inline-block;
  margin-bottom: 0.5rem;
}
.dash-header-title {
  font-family: 'Playfair Display', serif;
  font-size: clamp(1.4rem, 3vw, 2.2rem);
  font-weight: 900;
  color: var(--white);
  letter-spacing: -0.02em;
  margin-bottom: 0.25rem;
}
.dash-header-title em { color: var(--gold); font-style: italic; }
.dash-header-sub {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.1em;
  color: rgba(245,240,232,0.4);
}
.dash-export-btn {
  background: rgba(184,151,58,0.15);
  border: 1px solid rgba(184,151,58,0.4);
  color: var(--gold);
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.08em;
  padding: 0.55rem 1.1rem;
  border-radius: 4px;
  cursor: pointer;
  transition: all 0.2s;
}
.dash-export-btn:hover { background: var(--gold); color: var(--ink); }
.dash-logout-btn {
  background: rgba(220,53,69,0.12);
  border: 1px solid rgba(220,53,69,0.3);
  color: #f87171;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.08em;
  padding: 0.55rem 1.1rem;
  border-radius: 4px;
  cursor: pointer;
  transition: all 0.2s;
}
.dash-logout-btn:hover { background: rgba(220,53,69,0.2); }

.dash-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem 2rem 1rem;
}
.dash-kpi-grid {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  gap: 1rem;
  margin-bottom: 1.75rem;
}
@media (max-width: 900px) { .dash-kpi-grid { grid-template-columns: repeat(3, 1fr); } }
@media (max-width: 540px) { .dash-kpi-grid { grid-template-columns: repeat(2, 1fr); } }
.dash-kpi-card {
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: 8px;
  padding: 1.25rem 1rem;
  text-align: center;
  transition: all 0.2s;
}
.dash-kpi-card:hover {
  border-color: var(--gold);
  box-shadow: 0 4px 16px rgba(184,151,58,0.1);
}
.dash-kpi-icon { font-size: 1.5rem; margin-bottom: 0.5rem; }
.dash-kpi-num {
  font-family: 'Playfair Display', serif;
  font-size: 1.75rem;
  font-weight: 700;
  color: var(--ink);
  letter-spacing: -0.03em;
  line-height: 1;
  margin-bottom: 0.35rem;
}
.dash-kpi-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.58rem;
  letter-spacing: 0.1em;
  color: var(--ink-3);
  text-transform: uppercase;
  line-height: 1.4;
  margin-bottom: 0.35rem;
}
.dash-kpi-trend {
  font-family: 'DM Mono', monospace;
  font-size: 0.58rem;
  color: var(--ink-3);
}
.dash-kpi-trend.positive { color: #22c55e; }

.dash-chart-row {
  display: flex;
  gap: 1.25rem;
  margin-bottom: 1.75rem;
  flex-wrap: wrap;
}
.dash-chart-card {
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: 8px;
  padding: 1.5rem;
  flex: 1;
  min-width: 250px;
}
.dash-chart-title {
  font-family: 'Playfair Display', serif;
  font-size: 1rem;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 1.25rem;
  border-bottom: 1px solid var(--border-light);
  padding-bottom: 0.75rem;
}

.d-top-list { display: flex; flex-direction: column; gap: 0.65rem; }
.d-top-item {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  padding: 0.65rem 0.75rem;
  background: var(--cream);
  border-radius: 6px;
  border-left: 3px solid var(--gold);
}
.d-top-rank {
  font-family: 'Playfair Display', serif;
  font-size: 1.1rem;
  font-weight: 700;
  color: var(--gold);
  width: 28px;
  flex-shrink: 0;
  text-align: center;
}
.d-top-info { flex: 1; min-width: 0; }
.d-top-title {
  font-size: 0.9rem;
  font-weight: 600;
  color: var(--ink);
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  margin-bottom: 0.2rem;
}
.d-top-meta {
  font-family: 'DM Mono', monospace;
  font-size: 0.58rem;
  color: var(--ink-3);
  letter-spacing: 0.06em;
}
.d-top-reads {
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  color: var(--gold);
  font-weight: 700;
  white-space: nowrap;
}

.dash-ad-potential { display: flex; flex-direction: column; gap: 0; }
.dap-row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0.65rem 0;
  border-bottom: 1px solid rgba(184,151,58,0.12);
}
.dap-row:last-of-type { border-bottom: none; }
.dap-label {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.06em;
  color: rgba(245,240,232,0.55);
}
.dap-val {
  font-family: 'DM Mono', monospace;
  font-size: 0.72rem;
  color: var(--gold-pale);
  font-weight: 600;
}
.dap-total-row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 0.75rem;
  padding: 0.85rem 1rem;
  background: rgba(184,151,58,0.1);
  border: 1px solid rgba(184,151,58,0.25);
  border-radius: 6px;
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  letter-spacing: 0.08em;
  color: rgba(245,240,232,0.6);
  margin-bottom: 1rem;
}
.dap-contact-btn {
  display: block;
  text-align: center;
  background: var(--gold);
  color: var(--ink);
  font-family: 'DM Mono', monospace;
  font-size: 0.65rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  padding: 0.75rem;
  border-radius: 4px;
  text-decoration: none;
  transition: all 0.2s;
}
.dap-contact-btn:hover { background: var(--gold-light); }

.d-article-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.88rem;
}
.d-article-table th {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.1em;
  color: var(--gold);
  text-transform: uppercase;
  text-align: left;
  padding: 0.6rem 0.85rem;
  border-bottom: 2px solid var(--border-light);
  background: var(--cream);
}
.d-article-table td {
  padding: 0.65rem 0.85rem;
  border-bottom: 1px solid var(--border-light);
  color: var(--ink-2);
  font-size: 0.88rem;
}
.d-article-table tr:hover td { background: var(--cream); }
.d-table-reads {
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  color: var(--gold);
  font-weight: 600;
}
.d-table-cat {
  font-family: 'DM Mono', monospace;
  font-size: 0.6rem;
  letter-spacing: 0.08em;
  background: rgba(184,151,58,0.1);
  color: var(--gold);
  padding: 0.2rem 0.5rem;
  border-radius: 3px;
  white-space: nowrap;
}

.dash-footer-note {
  text-align: center;
  font-family: 'DM Mono', monospace;
  font-size: 0.62rem;
  letter-spacing: 0.08em;
  color: var(--ink-3);
  padding: 1.5rem;
  border: 1px dashed var(--border-light);
  border-radius: 6px;
  margin-bottom: 1.5rem;
}
</style>

<script>
// ── SHOPEE PRODUCTS ──────────────────────────────────────
const shopeeProducts = [
  // ── Katalog A (produk lama) ──
  { num: 1, name: "JISJIA Kipas 100 Gear Mini LED Kipas Turbo Angin Strong Wind Tampilan Digital", url: "https://s.shopee.co.id/7AZlHRYSL8" },
  { num: 2, name: "Satin Hitam Free Desain/Label Custom – Label Baju/Label Pakaian Custom Merk", url: "https://s.shopee.co.id/30kCJmoJnz" },
  { num: 3, name: "TV Android 43 inch Digital TV 24 inch Televisi LED 1080P TV WIFI – Garansi 5 Tahun", url: "https://s.shopee.co.id/9AKpf7QqHa" },
  { num: 4, name: "Fortisse Mattress Busa Anti-noda High Density Foam – Garansi 15 Tahun High Quality", url: "https://s.shopee.co.id/5Aogtlg4OR" },
  { num: 5, name: "One Set 2 in 1 Setelan Blazer Celana Panjang Nabila", url: "https://s.shopee.co.id/2VnvirqDog" },
  { num: 6, name: "Jaket Couple B Signature Pasangan / Jaket Pasangan Pacar / Sahabat (isi 2 pcs)", url: "https://s.shopee.co.id/30kCJmoJmw" },
  { num: 7, name: "YG300 Proyektor Mini Portable 4K Full HDMI Led Home Theater Mirroring Ponsel", url: "https://s.shopee.co.id/6AhE5bcGMi" },
  { num: 8, name: "Sweater Pria Fleece Tebal Nyaman Hoodie / Jaket Pullover Pocket Zipper Hoodie", url: "https://s.shopee.co.id/6fdUgWaMM1" },
  { num: 9, name: "Speaker Subwoofer Aktif Super Bass 8.8 inch Gratis Microsoft 7802", url: "https://s.shopee.co.id/4fsQIqhyPI" },
  { num: 10, name: "Motor Trail Lenka MC 69 50CC Trail Anak & Remaja 2 TAK Medium Kendaraan Mainan", url: "https://s.shopee.co.id/AKWn3GMOux" },
  { num: 11, name: "iPhone 11 / 11 Pro / 11 Pro Max / SE 2020 Tempered Glass Blue Light Anti Radiasi", url: "https://s.shopee.co.id/5L8764fR4g" },
  { num: 12, name: "T-JERZEN Kamera Digital CCD Mini 2.4 Inci 8X Zoom 1080p Vlog Flash Otomatis", url: "https://s.shopee.co.id/AADMqxN2Fs" },
  { num: 13, name: "Minyak Telon My Baby 150ml", url: "https://s.shopee.co.id/901PSoRTcZ" },
  { num: 14, name: "ZPER Satu Set Alat Perkakas Bor Listrik Cordless Toolkit 124 in 1 pcs", url: "https://s.shopee.co.id/901PSoRTdY" },
  { num: 15, name: "Kompor Listrik 2 Tungku Cooking Heating Coil 2000W", url: "https://s.shopee.co.id/9paWSLOIvu" },
  { num: 16, name: "Running Pad Pastel / Treadmill / Running Pad / Gym / Alat Olahraga", url: "https://s.shopee.co.id/8ASITHUeKV" },
  { num: 17, name: "TV Digital Smart 32 inch / 43 inch 4K USB/HDMI/WiFi/Netflix/YouTube – Garansi 3 Tahun", url: "https://s.shopee.co.id/9AKpf7QqIb" },
  { num: 18, name: "Kasur Busa Vassa Quilting / Premium 15–25 cm / Royal Foam Inside", url: "https://s.shopee.co.id/8fOZ4CSkIT" },
  { num: 19, name: "Lemari TV Serbaguna Rotan Plastik 2 Susun", url: "https://s.shopee.co.id/60NntIcthh" },
  { num: 20, name: "Kasur The Erland in Box Luxury Edition", url: "https://s.shopee.co.id/AKWn3GMOvw" },
  { num: 21, name: "Expert Care Face & Body Lotion Bayi & Anak – Colloidal Oatmeal (50g / 150g)", url: "https://s.shopee.co.id/6pwuspZj27" },
  { num: 22, name: "TCL Kulkas 2 Pintu F130-A50 – 118L 3D Surround Cooling Low Noise 39dB", url: "https://s.shopee.co.id/4Aw9hvjsQH" },
  { num: 23, name: "Sepeda Gunung MTB 26/27.5 ATLANTIS Odessy 730 21Speed NEW", url: "https://s.shopee.co.id/40cjVckVlE" },
  { num: 24, name: "Zwitsal Essential Baby Gift Set Hampers Perlengkapan Bayi 1 Pc", url: "https://s.shopee.co.id/5q4NgzdX2k" },
  { num: 25, name: "Jaket Kupluk Tahan Air dan Angin ZHAGO ORIGINAL", url: "https://s.shopee.co.id/6L0eHubd1n" },
  { num: 26, name: "Baju Muslim Pria Jubah Gamis Altan ORIGINAL RAFVERO", url: "https://s.shopee.co.id/808sGyVHfS" },
  { num: 27, name: "Lemari Susun Baby Karakter Beruang / Model Eropa 4–5 Susun", url: "https://s.shopee.co.id/50VGhSghjO" },
  { num: 28, name: "Moell Physical Sunscreen Anak 30gr SPF 50+ PA++++ – Tahan Air & Keringat", url: "https://s.shopee.co.id/6VK4UDazgo" },
  { num: 29, name: "Moell Face Cream 40gr Healthy Glow Barrier with Green Tea Extract + Panthenol", url: "https://s.shopee.co.id/7KtBTkXp05" },
  { num: 30, name: "Moell Body Lotion Bayi 185gr – Kulit Sensitif & Kering Daily Use", url: "https://s.shopee.co.id/4VZ06XibkN" },
  { num: 31, name: "Sajadah Kubah Premium 65x105 cm – Tebal Foam, Sudah List, Banyak Pilihan Warna", url: "https://s.shopee.co.id/7fW1sMWYLA" },
  { num: 32, name: "TASGUE Ransel Sekolah JT996 – Backpack Korea Lucu Anak & Wanita", url: "https://s.shopee.co.id/4qBqV9hL4L" },
  { num: 33, name: "ANGOLA Lemari Pakaian Anak 4–5 Tingkat C70-C71 Serbaguna", url: "https://s.shopee.co.id/2qQm7Tox7t" },
  { num: 34, name: "Bitzen Ikat Pinggang Wanita Kulit Sapi Slim Casual Belt Gesper Sabuk Pinggang", url: "https://s.shopee.co.id/7AZlHRYSM9" },
  { num: 35, name: "Helm MLA J5 Grey Glossy Kaca Visor Bening Half Face Premium SNI", url: "https://s.shopee.co.id/9Uxg3jPZbo" },
  { num: 36, name: "DGC Speaker Bluetooth Plus Mic Mini Karaoke Portable dengan 2 MIC Bluetooth", url: "https://s.shopee.co.id/7ppS4fVv0D" },
  { num: 37, name: "Scarlett Whitening Eau De Parfum 30ml – Dreamy / Sweet Memories / Euphoria", url: "https://s.shopee.co.id/8phzGVS6yZ" },
  { num: 38, name: "Imboost Kids Extra Vit C & D3 Tablet Hisap Suplemen Daya Tahan Tubuh [21 Tablet]", url: "https://s.shopee.co.id/5q4NgzdX3l" },
  { num: 39, name: "Kipas Angin Mini Portable USB Genggam N68 Layar LED 100 High Speed Digital Display", url: "https://s.shopee.co.id/3B3cW5ngRz" },
  { num: 40, name: "Baggy Jeans Wanita Hitam Retro Terbaru – Celana Baggy Loose Reguler Kekinian", url: "https://s.shopee.co.id/8fOZ4CSkJW" },
  { num: 41, name: "Celana Pendek Chino Pria Dewasa Short Pants Premium Size 27–38 Bahan Drill", url: "https://s.shopee.co.id/7VCbg3XBgB" },
  { num: 42, name: "Colfi Payung Lipat Otomatis Jumbo Buka Tutup Anti UV 10 Rangka Premium", url: "https://s.shopee.co.id/5fkxUgeANj" },
  { num: 43, name: "Panci Listrik Serbaguna Hemat Listrik 450W Anti Lengket / Elektrik Cooker Multifungsi", url: "https://s.shopee.co.id/8ASITHUeJQ" },
  { num: 44, name: "Mangkok Tulip 12 PCS (1 Lusin) Banyak Varian", url: "https://s.shopee.co.id/4LFZuEjF5K" },
  { num: 45, name: "Rak Dapur Makanan Tabita Food Grade Penyimpanan Praktis Multifungsi Food Cabinet", url: "https://s.shopee.co.id/9fH6G2OwGt" },
  { num: 46, name: "AH Botol Air Minum Bulat Tritan Aesthetic High Quality 800ml", url: "https://s.shopee.co.id/7VCbg3XBf6" },
  { num: 47, name: "Glad2Glow Brightening Lip Serum 7g – Mencerahkan, Melembabkan, Menambah Warna 3in1", url: "https://s.shopee.co.id/9ztweeNfar" },
  { num: 48, name: "LIGHTSPEED Dumbbell 1Kg / Barbel Mini Wanita Vinyl – Latihan Beban", url: "https://s.shopee.co.id/5VRXINenjj" },
  { num: 49, name: "Selimut Bulu Dewasa Halus 150x200 Motif Keren – Asriyasashii Berkualitas", url: "https://s.shopee.co.id/808sGyVHeP" },
  { num: 50, name: "Celana Pendek Pria Boardshort Cargo (Shortpants) Premium Quality", url: "https://s.shopee.co.id/6pwuspZj12" },
  { num: 51, name: "COSMOS Blender 3 in 1 CB282G Kaca 2 Liter – Garansi Resmi", url: "https://s.shopee.co.id/16akGzjt7" },
  { num: 52, name: "Sendal Sepatu Slip On Clogs Casual Sporty Bahan Karet EVA Empuk Anti Licin Size 35–44", url: "https://s.shopee.co.id/AUqDFZLlZy" },
  { num: 53, name: "Senter LED Super Terang Mini 3 Mata 5 Mode Pengisian Daya Klip Magnet COD", url: "https://s.shopee.co.id/7ppS4fVuzC" },
  { num: 54, name: "Ecentio Botol Minum Portable 500ml Aesthetic Olahraga Anti Bocor BPA Free", url: "https://s.shopee.co.id/70GL58Z5g7" },
  { num: 55, name: "ETHES CHOCOLATE Coklat isi 24 pcs", url: "https://s.shopee.co.id/8V58rtTNeX" },
  { num: 56, name: "Rak Troli Plastik Toilet / Kamar Mandi / Dapur Serbaguna dengan Roda Rak Bumbu Susun", url: "https://s.shopee.co.id/8V58rtTNdW" },
  { num: 57, name: "Timbangan Gantung Digital 50 kg Portable Scale Kotak Hook", url: "https://s.shopee.co.id/8KlifaU0yV" },
  { num: 58, name: "Pashmina Chiffon Ceruty Printed – Preorder", url: "https://s.shopee.co.id/qfhjnwZCC" },
  { num: 59, name: "Tumbler Handle 1 CARA Coffee Cup Termos Insulated Stainless 900 ml", url: "https://s.shopee.co.id/BQ0wZz6Y8" },
  { num: 60, name: "Tas Selempang Pria Waterproof Anti Air / Tas Pinggang / Tas Punggung Pria", url: "https://s.shopee.co.id/8phzGVS6xU" },
  { num: 61, name: "Botol Minum Lipat Portable BPA Free 700ml / Botol Travel Olahraga Silikon Anti Tumpah", url: "https://s.shopee.co.id/9KeFrQQCwn" },
  { num: 62, name: "Hand Sealer Mini / Alat Press Perekat Plastik Makanan Bungkusan Snack JRW0003", url: "https://s.shopee.co.id/6fdUgWaMN4" },
  { num: 63, name: "Ciput Pet Marsya / Ciput Antem Mika", url: "https://s.shopee.co.id/7fW1sMWYKB" },
  { num: 64, name: "Lunch Box Bento LB SLIM / Kotak Makan 1100ML BPA Free / Tempat Bekal", url: "https://s.shopee.co.id/10z7w6vvrH" },
  { num: 65, name: "Jas Hujan Eva Raincoat Korea Motor Unisex Lengan Panjang Waterproof", url: "https://s.shopee.co.id/gMHXUxCXB" },
  // ── Katalog B (produk baru) ──
  { num: 66, name: "Mainan Mobil Remote Jeep Diecast Bintang RC Metal Rubicon Baterai Charger Buka Pintu & Kap Mesin", url: "https://s.shopee.co.id/4AwpxgLRDe" },
  { num: 67, name: "V380 Pro CCTV Lampu Dual Lens Kamera HD 8MP Smart Wifi Two Way Audio Motion Detection", url: "https://s.shopee.co.id/6VKkjyCYUW" },
  { num: 68, name: "TAS DADA ROMPI TACTICAL ARMY HITAM POLICE ORIGINAL TERBARU", url: "https://s.shopee.co.id/8KmOvL5Zm5" },
  { num: 69, name: "GREENPETS Kandang Kucing Besar Murah Kokoh Beberapa Tingkat", url: "https://s.shopee.co.id/7KtrjV9Nnb" },
  { num: 70, name: "Sepatu Lari Pria Wanita 37-45 Original Sneakers OOTD Olahraga Running V80", url: "https://s.shopee.co.id/50VwxDIGXs" },
  { num: 71, name: "Jas Hujan Pria Wanita Setelan Dewasa Anti Rembes Raincoat PVC Tebal – Akula", url: "https://s.shopee.co.id/2g82AvR9HW" },
  { num: 72, name: "PAKET DIET DETOX 3IN1 – Sari Lemon 500ml, Cuka Apel 500ml, Chia Seed 70gr Halal", url: "https://s.shopee.co.id/3g0ZMlNLFk" },
  { num: 73, name: "Plester Tidur Anti-Kerutan Asam Hialuronat – Stiker Wajah Anti Kerut Patch Silikon", url: "https://s.shopee.co.id/2g82AvR9GV" },
  { num: 74, name: "YIGONG RC Excavator 11 CH 1:20 Crawler 2.4Ghz Mainan Anak Laki-laki Penggali", url: "https://s.shopee.co.id/60OU93ESVT" },
  { num: 75, name: "Rak Piring Tertutup Anti Serangga dengan Pintu Kabinet Sepenuhnya Tertutup", url: "https://s.shopee.co.id/8ASyj26D74" },
  { num: 76, name: "Lahap Bareng Iga Sapi Sambal Bakar Pedas – Makanan Lauk Instant Halal Tanpa Pengawet", url: "https://s.shopee.co.id/gMxnFYlKw" },
  { num: 77, name: "YG300 Proyektor Mini Portable Hp Android 4K Full HDMI Led Mini Home Theater", url: "https://s.shopee.co.id/20sLNhTgc3" },
  { num: 78, name: "Momoda Kipas Angin Portable Tahan Lama Kalung / Kipas Portable Mini Leher", url: "https://s.shopee.co.id/2qRSNEQVvW" },
  { num: 79, name: "Stop Kontak Premium Tahan Api Multifungsi 3–10 Plug Wireless USB Type C 10A 250V", url: "https://s.shopee.co.id/6AhuLMDpAU" },
  { num: 80, name: "Kasur Latex Memory Foam 10cm Premium Nyaman Anti Pegal 90x200 / 180x200", url: "https://s.shopee.co.id/9fHmVn0V4D" },
  { num: 81, name: "Smartwatch Watch 9 Jam Pintar Olahraga Bluetooth IP68 Monitor Detak Jantung", url: "https://s.shopee.co.id/809YWj6qS3" },
  { num: 82, name: "Mobil Aki Mainan Anak Jeep PMB M 8288 / 8299B Dual Dynamo Dual Accu", url: "https://s.shopee.co.id/BQhCKafLn" },
  { num: 83, name: "Ransel Sekolah Unisex Tas Punggung Terbaru 2025 New Trend Buy1 Get5", url: "https://s.shopee.co.id/1gFUz5UxHt" },
  { num: 84, name: "Tas Selempang Pria Pinggang Anti Air Waistbag Sporty Waterproof", url: "https://s.shopee.co.id/4qCWkuItrq" },
  { num: 85, name: "Dearday Foldable Portable Water Bottle 600ml", url: "https://s.shopee.co.id/3Vh9ASNyZi" },
  { num: 86, name: "TV Android 43 inch Smart TV 4K dengan Youtube/Google/Netflix/WIFI – Garansi 5 Tahun", url: "https://s.shopee.co.id/7AaRXCA18S" },
  { num: 87, name: "Kaos Kerah Polo Shirt Pria Motif Bordir Lengan Pendek Size M–XXXXL COD", url: "https://s.shopee.co.id/4AwpxgLREh" },
  { num: 88, name: "Dompet Panjang Kulit Premium Import Unisex Clutch Original", url: "https://s.shopee.co.id/4VZgMIKAXg" },
  { num: 89, name: "BOBO 2.4Ghz Excavator RC 16 Channel Beko Besar Alloy Semprot Air Mainan Anak", url: "https://s.shopee.co.id/9Kew7B1lkB" },
  { num: 90, name: "Myiwe Hair Coloring Shampoo Penghilang Uban / Shampoo Penghitam Rambut Uban", url: "https://s.shopee.co.id/1LceaTWDys" },
  { num: 91, name: "Kursi Roda Standar Rumah Sakit / Kursi Roda Medis Luar Kota", url: "https://s.shopee.co.id/2qRSNEQVwZ" },
  { num: 92, name: "GUMANI Tas Ransel Traveling Wanita/Pria Multifungsi Kapasitas Besar 45L Ruang Sepatu", url: "https://s.shopee.co.id/3LNiy9Obuh" },
  { num: 93, name: "Ortuseight Sepatu Running Hyperfuse 3.0 White Aqua", url: "https://s.shopee.co.id/20sLNhTgd4" },
  { num: 94, name: "Cairan Aroma Untuk Mesin Scenting Diffuser 1 Liter Ambune", url: "https://s.shopee.co.id/10zoBrXUey" },
  { num: 95, name: "Kandang Ayam Petelur 6 Pintu Isi 6 Ayam Besi Tebal Kalvanis", url: "https://s.shopee.co.id/1qYvBOUJwu" },
  { num: 96, name: "SmartWatch S11 PRO MAX 2.1 HD AMOLED GPS NFC Waterproof Bluetooth Call", url: "https://s.shopee.co.id/1LceaTWDxr" },
  { num: 97, name: "Tablet Android 10.1 inch 16GB+1TB High-definition Murah COD Ready Stock", url: "https://s.shopee.co.id/2VobycRmb6" },
  { num: 98, name: "Sampo Penumbuh Rambut Cepat Ekstrak Polygonum & Jahe Anti Rontok 500ML", url: "https://s.shopee.co.id/5ApN9WHdBs" },
  { num: 99, name: "SERUM WHITENING FAST Dr. Azka Skincare", url: "https://s.shopee.co.id/70H1KtAeTR" },
  { num: 100, name: "WEMI M2-C 3in1 Magnetic Mini Tripod Selfie Stick Remote Bluetooth Monopod Tongsis", url: "https://s.shopee.co.id/8fPFJx4J6F" },
  { num: 101, name: "Maxie Glow Skincare BPOM Kemasan Terbaru", url: "https://s.shopee.co.id/1Vw4mmVadv" },
  { num: 102, name: "CUTEHOME Kasur Busa Lateks Sutra Susu 3D Antibakteri 180x200x9cm", url: "https://s.shopee.co.id/4VZgMIKAYj" },
  { num: 103, name: "Mainan Pesawat Terbang 2.4G EPP Stunt Remote Control Led Glider Airplane Foam RC", url: "https://s.shopee.co.id/5ApN9WHdCv" },
  { num: 104, name: "Paket Kandang Ayam Petelur Fullset 3 Tingkat Aksesoris Lengkap Modern", url: "https://s.shopee.co.id/3B4IlqPFGb" },
  { num: 105, name: "Herbal Obat Asam Lambung GERD Paling Ampuh", url: "https://s.shopee.co.id/1Vw4mmVacs" },
  { num: 106, name: "Alat Pijat Penirus Wajah Face Lifting Double Chin V-Shaped", url: "https://s.shopee.co.id/2LVBmJSPw5" },
  { num: 107, name: "FIFTH LOVE Polygonum Multiflorum Shampoo Anti Rontok Panjangin Rambut Formula Botani", url: "https://s.shopee.co.id/W3XawZOem" },
  { num: 108, name: "Rak Kosmetik Acrylic Organizer Besar Makeup TOP1570", url: "https://s.shopee.co.id/BQhCKafKk" },
  { num: 109, name: "CCTV V380 Pro IP Camera Bulb 1080P Wireless WiFi Two Way Audio Remote Viewing", url: "https://s.shopee.co.id/17H01bIfj" },
  { num: 110, name: "Cetaphil Moisturizing Cream 100g dengan Vitamin E dan Almond Oil Pelembab Wajah", url: "https://s.shopee.co.id/1BJEOAWrIy" },
  { num: 111, name: "RC Beko Excavator YIGONG 11 CH 1:20 Crawler 2.4Ghz Mainan Anak Mobil Remote", url: "https://s.shopee.co.id/10zoBrXUdx" },
  { num: 112, name: "3IN1 Alat Pijat Pengencang Kulit Wajah Leher Mata / Setrika Wajah Perawatan Kecantikan", url: "https://s.shopee.co.id/qgNzYY7yw" },
  { num: 113, name: "Gembok Alarm Kunci Anti Maling", url: "https://s.shopee.co.id/gMxnFYlJv" },
  { num: 114, name: "1 Dus Rinso Cair Isi 104 SC Anti Noda Kemasan 500 20G", url: "https://s.shopee.co.id/4LGG9zKnsf" },
  { num: 115, name: "ERTO'S Astaxanthine Krim Mencerahkan Pelembab Wajah Anti Flek Hitam", url: "https://s.shopee.co.id/40dPlNM4Yd" },
  { num: 116, name: "Animate 5x Active Whitening Series 5in1 / Paket Kecantikan", url: "https://s.shopee.co.id/50VwxDIGWr" },
  { num: 117, name: "RC Mobil Sport Car Robot Deformation 2.4Ghz 1:14 Baterai Cas Autobot Remot", url: "https://s.shopee.co.id/4ft6YbJXCp" },
  { num: 118, name: "Jovitech Smartwatch Full HD 1.39 inch IPS Bluetooth Heart Rate Waterproof SW37", url: "https://s.shopee.co.id/3B4IlqPFFY" },
  { num: 119, name: "DGC Jemuran Lipat Dinding Stainless Steel Jemuran Baju Pakaian Dinding", url: "https://s.shopee.co.id/30ksZXPsaX" },
  { num: 120, name: "Cetaphil Moisturizing Cream 453g – Sunflower Oil, Vitamin E – Kulit Sangat Kering", url: "https://s.shopee.co.id/3g0ZMlNLEj" },
  { num: 121, name: "Aquarium Mini Akrilik Minimalis Fullset Plus Mesin Aerator Oksigen dan Lampu", url: "https://s.shopee.co.id/6feAwHBv9P" },
  { num: 122, name: "WARDAH Gel Moisturizer 30g – Vitamin C, Cica Complex, 14X Hyaluron, Tranexamic", url: "https://s.shopee.co.id/7fWi87877d" },
  { num: 123, name: "Terpal Kolam Ikan Lele 200x100x50 Tinggi A3 Termurah Grosir", url: "https://s.shopee.co.id/7VDHvo8kSc" },
  { num: 124, name: "Whitelab Paket Wajah Brightening Niacinamide – Facial Wash, Toner, Serum, Moisturizer, Sunscreen 6 pcs", url: "https://s.shopee.co.id/5q53wkF5qK" },
  { num: 125, name: "Dermatix Ultra 15gr Cream Penghilang Bekas Luka & Bekas Jerawat", url: "https://s.shopee.co.id/5fldkRFjBJ" },
  { num: 126, name: "Shampoo Kemiri Bakar Penumbuh Rambut Rontok Anti Ketombe Penghilang Uban Original", url: "https://s.shopee.co.id/5VSDY8GMWI" },
  { num: 127, name: "Jilbab Hijab Segitiga Instan Jersey Premium Segi Tiga Daily", url: "https://s.shopee.co.id/5L8nLpGzrH" },
  { num: 128, name: "PERFACE BPOM Lazy Cream Tone Up Brightening & Whitening Moisturizing", url: "https://s.shopee.co.id/6L1KXfDBpV" },
  { num: 129, name: "Vaseline Gluta Hya 330ml Multi Pack", url: "https://s.shopee.co.id/9pbCi5zrjE" },
  { num: 130, name: "KUCADI Meja Komputer Gaming Minimalis Modern Laptop Belajar Kantor – Garansi 5 Tahun", url: "https://s.shopee.co.id/9UyMJU18PC" },
  { num: 131, name: "TOUITECH 5IN1 Speaker Bluetooth PowerBank Phone Holder Stereo Mic Karaoke Portable", url: "https://s.shopee.co.id/AUqtVJxKNQ" },
  { num: 132, name: "Gio Saverino Sepatu Sekolah Hitam Pakai Tali Joker", url: "https://s.shopee.co.id/AKXTJ0xxiP" },
  { num: 133, name: "Tranq Tas Pria 3 in 1 Selempang Waterproof Handbag Clutchbag Premium Kuliah & Kantor", url: "https://s.shopee.co.id/AAE36hyb3O" },
  { num: 134, name: "ELDORE Paket Isi 12 Masker Facial Sheet Mask", url: "https://s.shopee.co.id/9zucuOzEON" },
  { num: 135, name: "Pagar Bayi Bermain Pembatas Kasur Pagar Mainan Anak Playground Pengaman Bayi", url: "https://s.shopee.co.id/8V5p7e4wR6" },
  { num: 136, name: "KAHF Skincare Cowok Halal – Perawatan Kulit Pria", url: "https://s.shopee.co.id/9ALVus2P5I" },
  { num: 137, name: "Headset QKZ AK6 Sport Earphone Bass Gaming Headset Dengan Mic", url: "https://s.shopee.co.id/9025iZ32QH" },
  { num: 138, name: "Dispenser Beras Otomatis Estetik 5kg/10kg Food Grade Anti Kutu", url: "https://s.shopee.co.id/8pifWG3flG" },
  { num: 139, name: "Cetaphil Moisturizing Lotion 236ml dengan Avocado Oil – Kulit Kering, Berminyak, Sensitif", url: "https://s.shopee.co.id/1qYvBOUJxx" },
  { num: 140, name: "iPhone 12 Pro Max 128GB/256GB Good Condition Like New Bergaransi", url: "https://s.shopee.co.id/2LVBmJSPx6" },
  { num: 141, name: "EXTERJAS Jas Hujan Raincoat Ransel Backpack Pria Wanita Mantel Motor PVC", url: "https://s.shopee.co.id/2VobycRmc9" },
  { num: 142, name: "Natasha by Dr Fredi Setyawan Lightening Night Cream 10gr", url: "https://s.shopee.co.id/Lk7Oda20m" },
  { num: 143, name: "Teh Rimpang JSR Syifacare – Minuman Instan Rempah Diet Detox Pelangsing Herbal BPOM", url: "https://s.shopee.co.id/W3XawZOfp" },
  { num: 144, name: "TrailTop Timbangan Badan Digital LCD Kaca Tempered Berat Max 180kg", url: "https://s.shopee.co.id/1BJEOAWrK1" },
  { num: 145, name: "TrailTop Meja Kursi Lipat Outdoor 1 Set Beban 150KG Baja Karbon Portable", url: "https://s.shopee.co.id/qgNzYY7zz" },
  { num: 146, name: "Hanasui Collagen Water Sunscreen SPF 50 – Ringan No Whitecast Tidak Kusam", url: "https://s.shopee.co.id/4LGG9zKntg" },
  { num: 147, name: "Tas New Benington Black White Forever", url: "https://s.shopee.co.id/4ft6YbJXDq" },
  { num: 148, name: "TONER BADAN AHA 2 PCS – Cerahkan Lipatan Gelap & Angkat Daki Whitening Saptadasa", url: "https://s.shopee.co.id/4qCWkuItst" },
  { num: 149, name: "10 Pasang Kaos Kaki Pendek Pria Wanita Atas Mata Kaki Olahraga Sport", url: "https://s.shopee.co.id/30ksZXPsbY" },
  { num: 150, name: "Parfum Vanilla Beli 1 Dapat 2 – Parfum Wanita Tahan Lama 24 Jam 35ml Eau De Parfume", url: "https://s.shopee.co.id/3qJzZ4Mhun" },
  { num: 151, name: "Scarlett Body Lotion Termurah", url: "https://s.shopee.co.id/3LNiy9Obvi" },
  { num: 152, name: "Cetaphil Moisturising Lotion 59ml Avocado Oil – Kulit Kering, Berminyak, Sensitif", url: "https://s.shopee.co.id/3Vh9ASNyal" },
  { num: 153, name: "LivChic LS304 3IN1 Catokan Rambut 65W 2 Meter 360° Sudut Belok Jauh 3IN1", url: "https://s.shopee.co.id/70H1KtAeUS" },
  { num: 154, name: "Sepatu ATT SMH 969 Sepatu Karet Pria Slip On Kerja", url: "https://s.shopee.co.id/7AaRXCA19V" },
  { num: 155, name: "PAKET 3in1 Mark Him BLUE & BLACK & SPORT EDP Parfum Pria 30ml Import Tahan 8 Jam", url: "https://s.shopee.co.id/6feAwHBvAQ" },
  { num: 156, name: "Natasha by Dr Fredi Setyawan Moisturizing Skin Toner 150ml", url: "https://s.shopee.co.id/6pxb8aBHpT" },
];

// ── PAGINATION STATE ──────────────────────────────────────
const ITEMS_PER_PAGE = 12;
let currentPage = 1;
let filteredProducts = [...shopeeProducts];

// Render one page of products
function renderShopee(list) {
  const grid = document.getElementById('shopee-grid');
  const count = document.getElementById('shopee-count');
  if (!grid) return;

  filteredProducts = list !== undefined ? list : shopeeProducts;
  currentPage = 1;
  if (count) count.textContent = filteredProducts.length + ' produk';
  renderPage();
}

function renderPage() {
  const grid = document.getElementById('shopee-grid');
  if (!grid) return;

  const start = (currentPage - 1) * ITEMS_PER_PAGE;
  const end   = start + ITEMS_PER_PAGE;
  const page  = filteredProducts.slice(start, end);

  if (page.length === 0) {
    grid.innerHTML = '<p style="grid-column:1/-1;text-align:center;color:var(--ink-3);font-family:\'DM Mono\',monospace;font-size:0.8rem;padding:3rem 0;">Produk tidak ditemukan.</p>';
    renderPagination();
    return;
  }

  grid.innerHTML = page.map(p => `
    <a href="${p.url}" target="_blank" rel="noopener" class="shopee-card">
      <div class="shopee-card-header">
        <span class="shopee-card-num">NO. ${String(p.num).padStart(3,'0')}</span>
        <span class="shopee-card-badge">Shopee Affiliate</span>
      </div>
      <div class="shopee-card-body">
        <div class="shopee-card-name">${p.name}</div>
        <div class="shopee-card-link">🛒 &nbsp;Beli di Shopee →</div>
      </div>
    </a>
  `).join('');

  renderPagination();

  // Scroll to top of affiliate section smoothly
  const sec = document.getElementById('page-affiliate');
  if (sec) sec.scrollIntoView({ behavior: 'smooth', block: 'start' });
}

function renderPagination() {
  const container = document.getElementById('shopee-pagination');
  if (!container) return;

  const total = filteredProducts.length;
  const totalPages = Math.ceil(total / ITEMS_PER_PAGE);

  if (totalPages <= 1) { container.innerHTML = ''; return; }

  const startItem = (currentPage - 1) * ITEMS_PER_PAGE + 1;
  const endItem   = Math.min(currentPage * ITEMS_PER_PAGE, total);

  // Build page buttons with ellipsis
  let pages = [];
  if (totalPages <= 7) {
    for (let i = 1; i <= totalPages; i++) pages.push(i);
  } else {
    if (currentPage <= 4) {
      pages = [1, 2, 3, 4, 5, '...', totalPages];
    } else if (currentPage >= totalPages - 3) {
      pages = [1, '...', totalPages-4, totalPages-3, totalPages-2, totalPages-1, totalPages];
    } else {
      pages = [1, '...', currentPage-1, currentPage, currentPage+1, '...', totalPages];
    }
  }

  const btnHTML = pages.map(p => {
    if (p === '...') return `<span class="pg-ellipsis">…</span>`;
    return `<button class="pg-btn${p === currentPage ? ' active' : ''}" onclick="goToPage(${p})">${p}</button>`;
  }).join('');

  container.innerHTML = `
    <button class="pg-btn" onclick="goToPage(${currentPage - 1})" ${currentPage === 1 ? 'disabled' : ''}>‹ Prev</button>
    ${btnHTML}
    <button class="pg-btn" onclick="goToPage(${currentPage + 1})" ${currentPage === totalPages ? 'disabled' : ''}>Next ›</button>
    <div class="pg-info">Menampilkan ${startItem}–${endItem} dari ${total} produk · Halaman ${currentPage} / ${totalPages}</div>
  `;
}

function goToPage(page) {
  const totalPages = Math.ceil(filteredProducts.length / ITEMS_PER_PAGE);
  if (page < 1 || page > totalPages) return;
  currentPage = page;
  renderPage();
}

function filterShopee(q) {
  const keyword = q.trim().toLowerCase();
  const filtered = keyword
    ? shopeeProducts.filter(p => p.name.toLowerCase().includes(keyword))
    : shopeeProducts;
  renderShopee(filtered);
}

// ── PAGE ROUTING ─────────────────────────────────────────
const homeElements = [];
let homeReady = false;

function collectHomeElements() {
  if (homeReady) return;
  // Hero, tentang, layanan, konsultasi, footer, announce-bar
  const selectors = ['.announce-bar','nav','.hero','.about-section','#tentang','.services-section','#layanan','.consult-section','#konsultasi','footer#kontak'];
  // We'll use a different approach: wrap home content
  homeReady = true;
}

function showPage(page, cat) {
  const allPages = ['page-konten','page-affiliate','page-digital','page-dashboard'];

  // Semua elemen yang hanya tampil di halaman home
  const hero     = document.querySelector('.hero');
  const tentang  = document.querySelector('.about-section');
  const layanan  = document.querySelector('.services-section');
  const konsultasi = document.getElementById('konsultasi');
  const footerEl = document.querySelector('footer');
  const announceBar = document.querySelector('.announce-bar');

  if (page === 'home') {
    // Tampilkan semua elemen home
    hero         && (hero.style.display = '');
    tentang      && (tentang.style.display = '');
    layanan      && (layanan.style.display = '');
    konsultasi   && (konsultasi.style.display = '');
    footerEl     && (footerEl.style.display = '');
    announceBar  && (announceBar.style.display = '');
    // Sembunyikan semua halaman lain
    allPages.forEach(id => {
      const el = document.getElementById(id);
      if (el) el.style.display = 'none';
    });
    window.scrollTo({ top: 0, behavior: 'smooth' });
  } else {
    // Sembunyikan semua elemen home
    hero         && (hero.style.display = 'none');
    tentang      && (tentang.style.display = 'none');
    layanan      && (layanan.style.display = 'none');
    konsultasi   && (konsultasi.style.display = 'none');
    footerEl     && (footerEl.style.display = 'none');
    announceBar  && (announceBar.style.display = 'none');
    // Tampilkan halaman yang dipilih
    allPages.forEach(id => {
      const el = document.getElementById(id);
      if (el) el.style.display = (id === 'page-' + page) ? 'block' : 'none';
    });
    if (page === 'affiliate') renderShopee();
    if (page === 'konten') {
      lp_init();
      setTimeout(lp_renderPortalWithOwnerCheck, 200);
      // Jika ada kategori, filter setelah render
      if (cat) {
        setTimeout(() => {
          lp_activeFilter = cat;
          lp_renderPortal();
          // Update tombol kategori aktif
          document.querySelectorAll('.lp-cat-btn').forEach(b => {
            b.classList.remove('active');
            const btnCat = b.getAttribute('onclick') && b.getAttribute('onclick').match(/lp_filterCat\('([^']+)'/);
            if (btnCat && btnCat[1] === cat) b.classList.add('active');
          });
        }, 100);
      } else {
        // Reset filter ke 'semua' dan pastikan tombol Semua aktif
        lp_activeFilter = 'semua';
        setTimeout(() => {
          document.querySelectorAll('.lp-cat-btn').forEach(b => b.classList.remove('active'));
          const allBtn = document.querySelector('.lp-cat-btn');
          if (allBtn) allBtn.classList.add('active');
        }, 50);
      }
    }
    if (page === 'digital') { if (typeof renderDigital === 'function') renderDigital(); }
    if (page === 'dashboard') {
      dashCheckSession();
      lpTrackView();
      setTimeout(lp_updateFirebaseBanner, 500);
    }
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  // Update active nav link highlight
  document.querySelectorAll('.nav-menu a').forEach(a => {
    a.style.fontWeight = '';
    a.style.color = '';
  });
}

// ── TAB SWITCHING ────────────────────────────────────────
function switchTab(btn, id) {
  const parentSection = btn.closest('section');
  parentSection.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
  parentSection.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
  btn.classList.add('active');
  parentSection.querySelector('#tab-' + id).classList.add('active');
}

// ── CONSULT FORM ─────────────────────────────────────────
function handleConsult(e) {
  e.preventDefault();
  const btn = document.getElementById('consult-btn');
  const msg = document.getElementById('consult-msg');

  const nama    = document.getElementById('c-name').value.trim();
  const kontak  = document.getElementById('c-contact').value.trim();
  const pesan   = document.getElementById('c-msg').value.trim();

  const waNumber = '6281262195937';
  const emailTo  = 'novrizal.tan2@gmail.com';

  // Susun pesan WhatsApp
  const waText = encodeURIComponent(
    `Halo Novrizal, saya ingin berkonsultasi:\n\n` +
    `*Nama:* ${nama}\n` +
    `*Kontak:* ${kontak}\n\n` +
    `*Permasalahan:*\n${pesan}`
  );
  const waUrl = `https://wa.me/${waNumber}?text=${waText}`;

  // Susun email (mailto)
  const emailSubject = encodeURIComponent(`Konsultasi Hukum dari ${nama}`);
  const emailBody = encodeURIComponent(
    `Nama: ${nama}\nKontak: ${kontak}\n\nPermasalahan:\n${pesan}`
  );
  const mailtoUrl = `mailto:${emailTo}?subject=${emailSubject}&body=${emailBody}`;

  btn.textContent = 'Mengirim...';
  btn.disabled = true;

  setTimeout(() => {
    // Buka WhatsApp di tab baru
    window.open(waUrl, '_blank');

    // Buka email client
    window.location.href = mailtoUrl;

    msg.style.display = 'block';
    msg.textContent = '✓ Pesan diteruskan! WhatsApp & email telah dibuka. Tim kami akan segera menghubungi Anda.';
    btn.style.display = 'none';
    e.target.reset();
  }, 800);
}

// ════════════════════════════════════════════════════════
// LEGALPRENEUR — SISTEM ARTIKEL / PORTAL BERITA
// ════════════════════════════════════════════════════════

// ── DATA STORE (Google Sheets sebagai Database) ──────────
const LP_STORE_KEY = 'lp_articles_v2'; // untuk draft & cache lokal

// Artikel di localStorage dipertahankan antar sesi (tidak dihapus saat refresh).
let lp_articles = [];
let lp_currentArticle = null;
let lp_editId = null;
let lp_activeFilter = 'semua';
let lp_autoSaveTimer = null;
let lp_dateTimeInterval = null;
let lp_initialized = false; // FIX: cegah double-init saat klik Konten berulang

// ═══════════════════════════════════════════════════════════════
// ╔══════════════════════════════════════════════════════════╗
// ║         KONFIGURASI GOOGLE SHEETS DATABASE              ║
// ║                                                          ║
// ║  LANGKAH SETUP (5 menit):                               ║
// ║  1. Buka: https://sheets.new  (buat spreadsheet baru)   ║
// ║  2. Beri nama: "LegalPreneur Articles"                   ║
// ║  3. Buka Extensions → Apps Script                        ║
// ║  4. Hapus semua kode, paste kode dari bawah ini         ║
// ║  5. Klik Deploy → New Deployment → Web App              ║
// ║     - Execute as: Me                                     ║
// ║     - Who has access: Anyone                             ║
// ║  6. Copy URL deployment, tempel ke LP_SHEETS_URL bawah  ║
// ╚══════════════════════════════════════════════════════════╝
// ═══════════════════════════════════════════════════════════════

// ─── TEMPEL URL GOOGLE APPS SCRIPT DEPLOYMENT DI SINI ───────
const LP_SHEETS_URL = 'https://script.google.com/macros/s/AKfycbz0lk-MgqlmgQY9OnINBm98C5Gki0Up-vpnAXHuHGkdA_S8rvhLBxsMSj5egecdWoi4/exec';
// Contoh: 'https://script.google.com/macros/s/AKfycbxXXXXX.../exec'
// ────────────────────────────────────────────────────────────

// ─── BASE URL UNTUK LINK SHARE ────────────────────────────
// Jika website sudah punya domain (mis. legalpreneur.my.id atau di Google Sites),
// isi LP_SITE_URL dengan URL lengkap website. Jika kosong (''), otomatis pakai
// URL saat ini (cocok untuk Google Sites hosting).
// Contoh: const LP_SITE_URL = 'https://sites.google.com/view/legalpreneur';
// Atau:   const LP_SITE_URL = 'https://legalpreneur.my.id';
const LP_SITE_URL = '';
// ────────────────────────────────────────────────────────────

// ─── URL GOOGLE APPS SCRIPT UNTUK KIRIM ARTIKEL (form eksternal) ───
const LP_KIRIM_URL = 'https://script.google.com/macros/s/AKfycbwMFDB4c5uhlGEikqftvMgjz6jZ1GMMvNPhXMhyTm2tnIaaZ3gqPkUexvx-TQ6CD5R6SA/exec';
// ────────────────────────────────────────────────────────────

// ─── KODE GOOGLE APPS SCRIPT (copy-paste ke Apps Script) ────
// ╔══════════════════════════════════════════════════════════╗
// ║  Paste kode berikut ke Google Apps Script Anda:         ║
// ╚══════════════════════════════════════════════════════════╝
/*
const SHEET_NAME = 'Sheet1';

function doGet(e) {
  const action = e.parameter.action;
  const callback = e.parameter.callback; // untuk JSONP
  const sheet = SpreadsheetApp.getActiveSpreadsheet().getSheetByName(SHEET_NAME)
    || SpreadsheetApp.getActiveSpreadsheet().insertSheet(SHEET_NAME);

  // Setup header jika sheet baru
  const headers = ['id','title','cat','author','summary','body','tags','img','createdAt','updatedAt'];
  if (sheet.getLastRow() === 0) {
    sheet.appendRow(headers);
    sheet.getRange(1,1,1,headers.length).setFontWeight('bold').setBackground('#2a2720').setFontColor('#f0e4c0');
    sheet.setFrozenRows(1);
  }

  if (action === 'getAll') {
    const data = sheet.getDataRange().getValues();
    if (data.length <= 1) return jsonpResponse([], callback);
    const hdrs = data[0];
    const rows = data.slice(1).map(row => {
      const obj = {};
      hdrs.forEach((h, i) => { obj[h] = row[i]; });
      return obj;
    }).filter(row => row.id && row.title); // filter baris kosong
    return jsonpResponse(rows.reverse(), callback);
  }

  // FIX: Handle save via GET + JSONP (fallback dari no-cors POST yang gagal)
  if (action === 'save') {
    try {
      const payload = JSON.parse(decodeURIComponent(e.parameter.data || '{}'));
      const art = payload.article;
      if (!art || !art.id) return jsonpResponse({ success: false, error: 'No article data' }, callback);
      const data = sheet.getDataRange().getValues();
      const hdrs = data[0];
      const idIdx = hdrs.indexOf('id');
      let found = false;
      for (let i = 1; i < data.length; i++) {
        if (String(data[i][idIdx]) === String(art.id)) {
          const row = hdrs.map(h => art[h] !== undefined ? art[h] : '');
          sheet.getRange(i+1, 1, 1, hdrs.length).setValues([row]);
          found = true; break;
        }
      }
      if (!found) {
        const row = hdrs.map(h => art[h] !== undefined ? art[h] : '');
        sheet.appendRow(row);
      }
      return jsonpResponse({ success: true, id: art.id }, callback);
    } catch(err) {
      return jsonpResponse({ success: false, error: err.toString() }, callback);
    }
  }

  // FIX: Handle delete via GET + JSONP
  if (action === 'delete') {
    try {
      const payload = JSON.parse(decodeURIComponent(e.parameter.data || '{}'));
      const id = payload.id || e.parameter.id;
      if (!id) return jsonpResponse({ success: false, error: 'No id' }, callback);
      const data = sheet.getDataRange().getValues();
      const hdrs = data[0];
      const idIdx = hdrs.indexOf('id');
      for (let i = 1; i < data.length; i++) {
        if (String(data[i][idIdx]) === String(id)) {
          sheet.deleteRow(i+1);
          return jsonpResponse({ success: true }, callback);
        }
      }
      return jsonpResponse({ success: false, error: 'Tidak ditemukan' }, callback);
    } catch(err) {
      return jsonpResponse({ success: false, error: err.toString() }, callback);
    }
  }

  return jsonpResponse({ error: 'Unknown action' }, callback);
}

function doPost(e) {
  const payload = JSON.parse(e.postData.contents);
  const action = payload.action;
  const sheet = SpreadsheetApp.getActiveSpreadsheet().getSheetByName(SHEET_NAME)
    || SpreadsheetApp.getActiveSpreadsheet().insertSheet(SHEET_NAME);

  // Setup header jika sheet baru
  const headers = ['id','title','cat','author','summary','body','tags','img','createdAt','updatedAt'];
  if (sheet.getLastRow() === 0) {
    sheet.appendRow(headers);
    sheet.getRange(1,1,1,headers.length).setFontWeight('bold').setBackground('#2a2720').setFontColor('#f0e4c0');
    sheet.setFrozenRows(1);
  }

  if (action === 'save') {
    const art = payload.article;
    const data = sheet.getDataRange().getValues();
    const hdrs = data[0];
    const idIdx = hdrs.indexOf('id');
    // Cari baris existing
    let found = false;
    for (let i = 1; i < data.length; i++) {
      if (data[i][idIdx] === art.id) {
        // Update baris
        const row = hdrs.map(h => art[h] !== undefined ? art[h] : '');
        sheet.getRange(i+1, 1, 1, hdrs.length).setValues([row]);
        found = true; break;
      }
    }
    if (!found) {
      // Tambah baris baru
      const row = hdrs.map(h => art[h] !== undefined ? art[h] : '');
      sheet.appendRow(row);
    }
    return jsonResponse({ success: true, id: art.id });
  }

  if (action === 'delete') {
    const id = payload.id;
    const data = sheet.getDataRange().getValues();
    const hdrs = data[0];
    const idIdx = hdrs.indexOf('id');
    for (let i = 1; i < data.length; i++) {
      if (data[i][idIdx] === id) {
        sheet.deleteRow(i+1);
        return jsonResponse({ success: true });
      }
    }
    return jsonResponse({ success: false, error: 'Tidak ditemukan' });
  }

  return jsonResponse({ error: 'Unknown action' });
}

function jsonResponse(data) {
  return ContentService
    .createTextOutput(JSON.stringify(data))
    .setMimeType(ContentService.MimeType.JSON);
}

// JSONP response untuk mendukung cross-origin dari Google Sites
function jsonpResponse(data, callback) {
  if (callback) {
    // JSONP: bungkus data dalam fungsi callback
    return ContentService
      .createTextOutput(callback + '(' + JSON.stringify(data) + ')')
      .setMimeType(ContentService.MimeType.JAVASCRIPT);
  }
  return jsonResponse(data);
}
*/
// ────────────────────────────────────────────────────────────

let lp_sheetsReady = false;

// Cek apakah URL sudah dikonfigurasi
(function lp_sheetsInit() {
  if (LP_SHEETS_URL && LP_SHEETS_URL !== 'TEMPEL_URL_DEPLOYMENT_ANDA_DI_SINI') {
    lp_sheetsReady = true;
    console.log('LegalPreneur: Google Sheets database siap.');
  } else {
    console.warn('LegalPreneur: Google Sheets belum dikonfigurasi. Pakai localStorage sementara.');
  }
})();

const LP_CAT_LABELS = {
  hukum: '⚖️ Hukum', mediasi: '🤝 Mediasi', finansial: '💰 Finansial',
  digital: '📱 Digital', regulasi: '🏛️ Regulasi', opini: '✍️ Opini'
};

// ── TEMPLATE ARTIKEL ──────────────────────────────────────
const LP_TEMPLATES = [
  {
    icon: '⚖️', cat: 'hukum',
    name: 'Analisis Hukum',
    title: 'Memahami Hak dan Kewajiban dalam Perjanjian Kerja: Panduan Lengkap',
    summary: 'Banyak pekerja dan pengusaha tidak memahami hak dan kewajiban yang tertuang dalam perjanjian kerja. Artikel ini mengulas dasar hukum dan poin-poin penting yang wajib dipahami.',
    body: `<h2>Latar Belakang</h2><p>Perjanjian kerja merupakan dasar hubungan hukum antara pengusaha dan pekerja. Namun, dalam praktiknya, masih banyak pihak yang tidak memahami isi perjanjian yang mereka tandatangani.</p><h2>Dasar Hukum</h2><p>Berdasarkan Undang-Undang No. 13 Tahun 2003 tentang Ketenagakerjaan, perjanjian kerja harus memuat identitas para pihak, jabatan atau jenis pekerjaan, tempat pekerjaan, besarnya upah dan cara pembayarannya.</p><h2>Hak-Hak Pekerja</h2><p>Setiap pekerja berhak atas upah yang layak, jaminan sosial, cuti tahunan, dan perlindungan keselamatan kerja. Hak-hak ini tidak dapat dihilangkan meskipun telah diperjanjikan sebaliknya.</p><h2>Kewajiban Pengusaha</h2><p>Pengusaha wajib memberikan upah tepat waktu, menyediakan lingkungan kerja yang aman, mendaftarkan pekerja ke BPJS, dan mematuhi ketentuan jam kerja yang berlaku.</p><h2>Kesimpulan</h2><p>Pahami setiap klausul sebelum menandatangani perjanjian kerja. Bila ada ketidakjelasan, jangan ragu untuk berkonsultasi dengan advokat atau konsultan hukum terpercaya.</p>`,
    tags: 'hukum ketenagakerjaan, perjanjian kerja, hak pekerja'
  },
  {
    icon: '🤝', cat: 'mediasi',
    name: 'Panduan Mediasi',
    title: 'Mediasi sebagai Solusi Sengketa Tanpa Pengadilan: Lebih Cepat, Lebih Hemat',
    summary: 'Sengketa tidak selalu harus diselesaikan di pengadilan. Mediasi menawarkan penyelesaian yang lebih cepat, hemat biaya, dan menjaga hubungan baik antara para pihak.',
    body: `<h2>Apa Itu Mediasi?</h2><p>Mediasi adalah proses penyelesaian sengketa di luar pengadilan yang melibatkan pihak ketiga netral (mediator) untuk membantu para pihak mencapai kesepakatan.</p><h2>Keunggulan Mediasi</h2><p>Dibandingkan litigasi (pengadilan), mediasi memiliki sejumlah keunggulan: prosesnya lebih cepat (umumnya 1–3 bulan), biaya lebih rendah, bersifat rahasia, dan menghasilkan kesepakatan yang lebih diterima kedua pihak.</p><h2>Jenis Sengketa yang Cocok</h2><p>Mediasi sangat efektif untuk sengketa bisnis, sengketa keluarga, sengketa ketenagakerjaan, dan sengketa tanah. Hampir semua jenis sengketa perdata dapat diselesaikan melalui mediasi.</p><h2>Proses Mediasi</h2><p>Proses mediasi umumnya terdiri dari: pembukaan, penyampaian masalah oleh masing-masing pihak, identifikasi kepentingan, perundingan, dan penandatanganan kesepakatan.</p><h2>Peran Mediator Bersertifikat</h2><p>Mediator bersertifikat memiliki keahlian komunikasi, negosiasi, dan pemahaman hukum yang diperlukan untuk memfasilitasi proses secara profesional dan imparsial.</p>`,
    tags: 'mediasi, penyelesaian sengketa, non-litigasi, arbitrase'
  },
  {
    icon: '💰', cat: 'finansial',
    name: 'Literasi Finansial',
    title: 'Hak Konsumen Menghadapi Debt Collector: Apa yang Boleh dan Tidak Boleh?',
    summary: 'Penagihan utang yang agresif kerap menimbulkan ketakutan. Padahal, ada aturan hukum yang melindungi Anda. Kenali hak-hak Anda sebagai debitur.',
    body: `<h2>Fenomena Penagihan Agresif</h2><p>Tidak sedikit debitur yang mengalami intimidasi, pelecehan verbal, bahkan ancaman dari oknum debt collector. Padahal, ada regulasi yang mengatur batas-batas penagihan yang diperbolehkan.</p><h2>Regulasi yang Berlaku</h2><p>OJK telah menerbitkan aturan tegas mengenai penagihan oleh lembaga keuangan. Penagihan hanya boleh dilakukan pada jam tertentu (08.00–20.00), tidak boleh menggunakan ancaman, kekerasan, atau cara yang mempermalukan debitur.</p><h2>Hak-Hak Anda sebagai Debitur</h2><p>Anda berhak meminta identitas debt collector, menolak penagihan di luar jam yang diizinkan, melarang penagihan di tempat kerja, dan tidak dihubungi oleh orang yang tidak berwenang.</p><h2>Langkah Hukum yang Bisa Ditempuh</h2><p>Jika hak Anda dilanggar, Anda dapat melaporkan ke OJK, melapor ke kepolisian atas dugaan pengancaman, dan meminta bantuan advokat untuk membuat somasi resmi.</p><h2>Kesimpulan</h2><p>Memiliki utang bukan berarti kehilangan hak sebagai manusia. Kenali hak Anda, dokumentasikan setiap pelanggaran, dan jangan ragu mencari bantuan hukum.</p>`,
    tags: 'debt collector, hak konsumen, OJK, perlindungan debitur'
  },
  {
    icon: '🏛️', cat: 'regulasi',
    name: 'Analisis Regulasi',
    title: 'Update Regulasi Terbaru: Dampaknya bagi Pelaku Usaha Digital di Indonesia',
    summary: 'Pemerintah terus memperbarui regulasi di sektor digital. Artikel ini menganalisis perubahan terbaru dan implikasinya bagi para pelaku usaha online dan startup.',
    body: `<h2>Lanskap Regulasi Digital Indonesia</h2><p>Indonesia terus memperkuat kerangka hukum di sektor digital. Berbagai regulasi baru diterbitkan untuk mengikuti perkembangan ekosistem teknologi yang sangat dinamis.</p><h2>Poin-Poin Regulasi Penting</h2><p>Pelaku usaha digital perlu memperhatikan ketentuan mengenai perlindungan data pribadi, ketentuan e-commerce, pajak digital, dan perizinan berusaha berbasis risiko melalui OSS.</p><h2>Kewajiban Pelaku Usaha</h2><p>Setiap platform digital wajib memiliki kebijakan privasi yang jelas, mekanisme penanganan keluhan konsumen, dan mematuhi ketentuan konten yang berlaku di wilayah Indonesia.</p><h2>Sanksi atas Pelanggaran</h2><p>Pelanggaran terhadap regulasi digital dapat berujung pada sanksi administratif, pemblokiran platform, hingga tuntutan pidana bagi pemilik atau pengelolanya.</p><h2>Rekomendasi</h2><p>Lakukan legal audit secara berkala, konsultasikan model bisnis Anda dengan konsultan hukum, dan pastikan selalu up-to-date dengan perubahan regulasi terbaru.</p>`,
    tags: 'regulasi digital, hukum teknologi, startup, e-commerce'
  },
  {
    icon: '📱', cat: 'digital',
    name: 'Literasi Digital',
    title: 'Bijak Bermedia Sosial: Aspek Hukum yang Wajib Dipahami Sebelum Posting',
    summary: 'Media sosial bukan ruang bebas hukum. Setiap konten yang Anda unggah bisa membawa konsekuensi hukum. Kenali aturannya sebelum terlambat.',
    body: `<h2>Media Sosial dan Tanggung Jawab Hukum</h2><p>Banyak pengguna media sosial tidak menyadari bahwa setiap unggahan, komentar, dan bagian konten tunduk pada hukum yang berlaku di Indonesia.</p><h2>UU ITE dan Ancamannya</h2><p>Undang-Undang ITE mengatur berbagai perbuatan yang dapat dipidana, termasuk penyebaran konten yang mengandung penghinaan, fitnah, ancaman, ujaran kebencian, dan berita bohong (hoaks).</p><h2>Konten yang Berisiko Hukum</h2><p>Berhati-hatilah dengan konten yang menyerang reputasi orang lain, mengandung SARA, menyebarkan informasi yang belum terverifikasi, atau mendistribusikan karya orang lain tanpa izin.</p><h2>Perlindungan Anda sebagai Pengguna</h2><p>Simpan bukti setiap konten yang menyerang Anda, lakukan screen capture, dan segera konsultasikan dengan advokat bila merasa menjadi korban kejahatan siber.</p><h2>Tips Bijak Bermedia Sosial</h2><p>Verifikasi sebelum berbagi, jaga privasi informasi pribadi, hormati hak cipta orang lain, dan selalu berpikir sebelum memposting.</p>`,
    tags: 'UU ITE, media sosial, hoaks, ujaran kebencian, hukum digital'
  },
  {
    icon: '✍️', cat: 'opini',
    name: 'Opini & Editorial',
    title: 'Opini: Mengapa Kesadaran Hukum Masyarakat Harus Dimulai dari Sekarang',
    summary: 'Rendahnya melek hukum masyarakat Indonesia menjadi akar dari banyak permasalahan sosial. Saatnya kita berbicara tentang literasi hukum sebagai kebutuhan dasar.',
    body: `<h2>Realita Literasi Hukum Kita</h2><p>Survei demi survei menunjukkan bahwa sebagian besar masyarakat Indonesia tidak memahami hak-hak dasar mereka di hadapan hukum. Ini bukan sekadar masalah pendidikan — ini adalah krisis sistemik.</p><h2>Dampak Rendahnya Melek Hukum</h2><p>Rendahnya kesadaran hukum membuat masyarakat mudah menjadi korban penipuan, eksploitasi, dan ketidakadilan. Mereka tidak tahu kemana harus melapor, tidak tahu apa yang bisa dilakukan, dan seringkali menyerah pada ketidakadilan.</p><h2>Peran Platform Hukum Digital</h2><p>Di sinilah platform seperti LegalPreneur hadir — menjembatani jarak antara masyarakat awam dan akses terhadap informasi hukum yang akurat, mudah dipahami, dan relevan dengan kehidupan sehari-hari.</p><h2>Apa yang Bisa Kita Lakukan?</h2><p>Literasi hukum bukan hanya tanggung jawab advokat. Setiap warga negara bisa berkontribusi dengan menyebarkan informasi hukum yang benar, mendukung platform literasi, dan mulai bertanya ketika ada yang tidak dipahami.</p><h2>Penutup</h2><p>Hukum bukan milik orang-orang yang punya kuasa. Hukum adalah milik semua warga negara — dan sudah saatnya kita semua memanfaatkannya.</p>`,
    tags: 'opini, literasi hukum, kesadaran hukum, advokasi'
  }
];

// ── INIT ──────────────────────────────────────────────────
function lp_init() {
  lp_updateDateTime();
  if (!lp_dateTimeInterval) {
    lp_dateTimeInterval = setInterval(lp_updateDateTime, 60000);
  }
  lp_buildTemplateGrid();
  lp_updateUserBar();

  // FIX: Jika sudah punya artikel di memori, langsung render tanpa reload
  // Ini mencegah artikel hilang saat user klik menu Konten berulang kali
  if (lp_initialized && lp_articles.length > 0) {
    lp_renderPortal();
    return;
  }

  lp_initialized = true;

  if (lp_sheetsReady) {
    // Google Sheets sudah dikonfigurasi — load dari cloud
    lp_loadFromSheets();
  } else {
    // Belum dikonfigurasi — pakai localStorage sebagai fallback
    lp_loadFromLocalStorage();
  }
}

function lp_showPortalLoading() {
  var featuredWrap = document.getElementById('lp-featured-wrap');
  var gridWrap = document.getElementById('lp-grid-wrap');
  var empty = document.getElementById('lp-empty');
  if (featuredWrap) featuredWrap.innerHTML = '<div style="text-align:center;padding:3.5rem 2rem;color:var(--ink-3);font-family:DM Mono,monospace;font-size:0.78rem;letter-spacing:0.1em;line-height:2;"><div style="font-size:2rem;margin-bottom:1rem;">📊</div>Memuat artikel dari Google Sheets...<br><span style="font-size:0.65rem;opacity:0.6;">Mohon tunggu sebentar</span></div>';
  if (gridWrap) gridWrap.innerHTML = '';
  if (empty) empty.style.display = 'none';
}

function lp_loadFromLocalStorage() {
  try {
    var stored = localStorage.getItem(LP_STORE_KEY);
    lp_articles = stored ? JSON.parse(stored) : [];
  } catch(e) { lp_articles = []; }
  lp_renderPortal();
}

// ── LOAD DARI GOOGLE SHEETS ───────────────────────────────
// ──────────────────────────────────────────────────────────
// SISTEM PENYIMPANAN GANDA:
//  1. localStorage  → UTAMA (selalu bekerja, langsung, tanpa CORS)
//  2. Google Sheets → BACKUP CLOUD (sinkronisasi background via JSONP)
//
// Cara kerja:
//  SIMPAN : localStorage dulu (langsung) → Sheets background (async)
//  MUAT   : localStorage dulu (instan) → coba Sheets JSONP (update jika ada data baru)
//  HAPUS  : localStorage dulu (langsung) → Sheets background (async)
// ──────────────────────────────────────────────────────────

// Callback global untuk JSONP dari Google Sheets
window.lp_sheetsCallback = function(rows) {
  try {
    if (!Array.isArray(rows) || rows.length === 0) {
      // Sheets kosong atau gagal — tetap pakai data localStorage yang sudah ada
      if (lp_articles.length === 0) lp_loadFromLocalStorage();
      return;
    }
    var mapped = rows.map(function(row) {
      return {
        id:        String(row.id || ''),
        title:     String(row.title || ''),
        cat:       String(row.cat || 'umum'),
        author:    String(row.author || 'Novrizal, S.I.Kom., S.H., CPM'),
        summary:   String(row.summary || ''),
        body:      String(row.body || ''),
        tags:      String(row.tags || ''),
        img:       String(row.img || ''),
        imgCaption: String(row.imgCaption || ''),
        createdAt: Number(row.createdAt) || Date.now(),
        updatedAt: Number(row.updatedAt) || Date.now()
      };
    }).filter(function(a) { return a.id && a.title; });

    // Gabungkan: Sheets sebagai sumber utama (artikel cloud)
    // Pertahankan artikel lokal yang belum tersinkron ke Sheets
    var sheetsIds = mapped.map(function(a) { return a.id; });
    // Ambil artikel dari localStorage yang ID-nya belum ada di Sheets (belum tersinkron)
    var localUnsyncedIds = [];
    try {
      var localData = JSON.parse(localStorage.getItem(LP_STORE_KEY)) || [];
      localUnsyncedIds = localData.filter(function(a) {
        return a.id && a.title && !sheetsIds.includes(a.id);
      });
    } catch(e) {}

    // Artikel Sheets + artikel lokal yang belum masuk Sheets
    lp_articles = mapped.concat(localUnsyncedIds);
    lp_articles.sort(function(a,b){ return b.createdAt - a.createdAt; });

    // Update localStorage dengan data terbaru dari Sheets
    try { localStorage.setItem(LP_STORE_KEY, JSON.stringify(lp_articles)); } catch(e) {}
    lp_renderPortal();

    // Jika ada artikel lokal yang belum ada di Sheets, sync sekarang
    if (localUnsyncedIds.length > 0) {
      localUnsyncedIds.forEach(function(art) {
        var artForSheets = Object.assign({}, art);
        if (artForSheets.img && artForSheets.img.startsWith('data:')) artForSheets.img = '';
        fetch(LP_SHEETS_URL, {
          method: 'POST',
          mode: 'no-cors',
          headers: { 'Content-Type': 'text/plain' },
          body: JSON.stringify({ action: 'save', article: artForSheets })
        }).catch(function() {});
      });
    }
  } catch(e) {
    console.warn('lp_sheetsCallback error:', e);
    // Fallback: tetap pakai localStorage
    lp_loadFromLocalStorage();
  } finally {
    // Hapus script tag JSONP setelah selesai
    var old = document.getElementById('lp-jsonp-script');
    if (old && old.parentNode) old.parentNode.removeChild(old);
    // Batalkan timeout jika callback sudah berhasil lebih dulu
    if (window._lp_sheetsTimeout) {
      clearTimeout(window._lp_sheetsTimeout);
      window._lp_sheetsTimeout = null;
    }
  }
};

// Load dari Google Sheets via JSONP (bekerja tanpa CORS)
function lp_loadFromSheets() {
  // 1. Cek apakah localStorage punya data
  var hasLocalData = false;
  try {
    var localRaw = localStorage.getItem(LP_STORE_KEY);
    var localArr = localRaw ? JSON.parse(localRaw) : [];
    hasLocalData = Array.isArray(localArr) && localArr.length > 0;
  } catch(e) {}

  if (hasLocalData) {
    // Ada data lokal: tampilkan dulu (instan), lalu sync Sheets di background
    lp_loadFromLocalStorage();
  } else {
    // Tidak ada data lokal (browser baru / incognito / setelah clear cache):
    // Tampilkan indikator loading, tunggu Sheets
    lp_showPortalLoading();
  }

  // 2. Jika Sheets dikonfigurasi, load/sync via JSONP
  if (!lp_sheetsReady) {
    // Sheets belum dikonfigurasi: render portal dengan data lokal (mungkin kosong)
    if (!hasLocalData) lp_loadFromLocalStorage();
    return;
  }

  lp_fetchFromSheets(false);
}

function lp_fetchFromSheets(isRetry) {
  // Hapus script JSONP lama jika ada
  var old = document.getElementById('lp-jsonp-script');
  if (old && old.parentNode) old.parentNode.removeChild(old);

  var script = document.createElement('script');
  script.id = 'lp-jsonp-script';
  script.src = LP_SHEETS_URL + '?action=getAll&callback=lp_sheetsCallback&t=' + Date.now();
  script.onerror = function() {
    var s = document.getElementById('lp-jsonp-script');
    if (s && s.parentNode) s.parentNode.removeChild(s);
    if (!isRetry) {
      // Coba sekali lagi setelah 3 detik
      console.warn('Google Sheets JSONP gagal - mencoba ulang...');
      setTimeout(function() { lp_fetchFromSheets(true); }, 3000);
    } else {
      console.warn('Google Sheets tidak dapat dijangkau - menggunakan localStorage');
    }
  };
  document.head.appendChild(script);

  // Timeout 10 detik: jika Sheets tidak merespons, retry sekali
  var timeoutId = setTimeout(function() {
    var s = document.getElementById('lp-jsonp-script');
    if (s && s.parentNode) {
      s.parentNode.removeChild(s);
      if (!isRetry) {
        console.warn('Google Sheets timeout - mencoba ulang...');
        setTimeout(function() { lp_fetchFromSheets(true); }, 2000);
      } else {
        console.warn('Google Sheets timeout (retry) - tetap pakai localStorage');
      }
    }
    }, 20000); // Simpan timeoutId agar bisa dibatalkan jika callback berhasil lebih dulu
  window._lp_sheetsTimeout = timeoutId;
}

// ── SIMPAN KE GOOGLE SHEETS ───────────────────────────────
function lp_save() {
  // Simpan ke localStorage (selalu berhasil)
  try { localStorage.setItem(LP_STORE_KEY, JSON.stringify(lp_articles)); } catch(e) {}
}

// ── HELPER: Kirim data ke GAS via form POST (menghindari CORS preflight) ──
function lp_gasPost(payload) {
  // Gunakan teknik iframe hidden form POST — 100% bypass CORS, tidak butuh CORS header di GAS
  // Data dikirim sebagai form field 'data' berisi JSON string
  try {
    var iframe = document.createElement('iframe');
    iframe.name = 'lp_gas_post_' + Date.now();
    iframe.style.display = 'none';
    document.body.appendChild(iframe);

    var form = document.createElement('form');
    form.method = 'POST';
    form.action = LP_SHEETS_URL;
    form.target = iframe.name;
    form.style.display = 'none';

    // GAS doPost membaca e.postData.contents — kirim payload sebagai field tersembunyi
    // Agar GAS bisa baca: gunakan application/x-www-form-urlencoded
    // Tapi GAS hanya baca e.postData.contents untuk raw body.
    // Solusi terbaik: encode payload ke query string GET (doGet)
    // Untuk save/delete: gunakan JSONP GET dengan action=save&data=...
    document.body.removeChild(iframe);

    // === SOLUSI NYATA: Gunakan JSONP GET dengan data ter-encode ===
    lp_gasJsonpAction(payload);
  } catch(e) {
    console.warn('lp_gasPost error:', e);
  }
}

// Kirim aksi ke GAS via JSONP GET (bekerja tanpa CORS)
function lp_gasJsonpAction(payload) {
  try {
    var callbackName = 'lp_gasActionCb_' + Date.now();
    var scriptEl = document.createElement('script');
    var dataEncoded = encodeURIComponent(JSON.stringify(payload));
    scriptEl.src = LP_SHEETS_URL + '?action=' + payload.action + '&data=' + dataEncoded + '&callback=' + callbackName + '&t=' + Date.now();
    scriptEl.onerror = function() {
      if (scriptEl.parentNode) scriptEl.parentNode.removeChild(scriptEl);
      if (window[callbackName]) delete window[callbackName];
    };
    window[callbackName] = function(result) {
      if (scriptEl.parentNode) scriptEl.parentNode.removeChild(scriptEl);
      delete window[callbackName];
      if (result && result.success) {
        console.log('Google Sheets sync berhasil:', payload.action);
      } else {
        console.warn('Google Sheets sync response:', result);
      }
    };
    // Timeout 15 detik
    setTimeout(function() {
      if (scriptEl.parentNode) scriptEl.parentNode.removeChild(scriptEl);
      if (window[callbackName]) delete window[callbackName];
    }, 15000);
    document.head.appendChild(scriptEl);
  } catch(e) {
    console.warn('lp_gasJsonpAction error:', e);
  }
}

// Simpan satu artikel ke Sheets + localStorage
function lp_saveArticleToFirestore(article) {
  // Nama fungsi dipertahankan agar kompatibel dengan kode lain

  // === LANGKAH 1: Simpan ke localStorage DULU (langsung, tidak pernah gagal) ===
  var existingIdx = lp_articles.findIndex(function(x) { return x.id === article.id; });
  if (existingIdx > -1) {
    lp_articles[existingIdx] = article;
  } else {
    lp_articles.unshift(article);
  }
  try { localStorage.setItem(LP_STORE_KEY, JSON.stringify(lp_articles)); } catch(e) {}

  // FIX: Reset flag agar saat kembali ke halaman Konten, artikel baru terrender
  lp_initialized = false;

  // === LANGKAH 2: Sync ke Google Sheets via JSONP GET (bypass CORS) ===
  if (lp_sheetsReady) {
    // Untuk Google Sheets: hapus base64 image (terlalu besar, max ~50k char per cell)
    var articleForSheets = Object.assign({}, article);
    if (articleForSheets.img && articleForSheets.img.startsWith('data:')) {
      articleForSheets.img = '';
    }

    // Coba fetch no-cors dulu (biasanya berhasil kirim data ke GAS)
    fetch(LP_SHEETS_URL, {
      method: 'POST',
      mode: 'no-cors',
      headers: { 'Content-Type': 'text/plain' },
      body: JSON.stringify({ action: 'save', article: articleForSheets })
    }).then(function() {
      console.log('Artikel terkirim ke Google Sheets via POST (background)');
    }).catch(function(e) {
      // Fallback: coba via JSONP GET jika POST gagal
      console.warn('POST gagal, mencoba JSONP:', e.message);
      lp_gasJsonpAction({ action: 'save', article: articleForSheets });
    });
  }

  // Return Promise.resolve() agar kode pemanggil tetap berjalan normal
  return Promise.resolve({ success: true });

}

// Hapus satu artikel dari localStorage + Sheets
function lp_deleteArticleFromFirestore(id) {
  // Nama fungsi dipertahankan agar kompatibel dengan kode lain

  // === LANGKAH 1: Hapus dari localStorage DULU ===
  lp_articles = lp_articles.filter(function(x) { return x.id !== id; });
  try { localStorage.setItem(LP_STORE_KEY, JSON.stringify(lp_articles)); } catch(e) {}

  // FIX: Reset flag agar portal ter-refresh dengan benar
  lp_initialized = false;

  // === LANGKAH 2: Sync hapus ke Google Sheets di background ===
  if (lp_sheetsReady) {
    fetch(LP_SHEETS_URL, {
      method: 'POST',
      mode: 'no-cors',
      headers: { 'Content-Type': 'text/plain' },
      body: JSON.stringify({ action: 'delete', id: id })
    }).catch(function(e) {
      // Fallback via JSONP GET
      lp_gasJsonpAction({ action: 'delete', id: id });
    });
  }

  return Promise.resolve({ success: true });
}

// ── DATE/TIME ─────────────────────────────────────────────
function lp_updateDateTime() {
  const el = document.getElementById('lp-date-now');
  if (!el) return;
  const now = new Date();
  const days = ['Minggu','Senin','Selasa','Rabu','Kamis','Jumat','Sabtu'];
  const months = ['Jan','Feb','Mar','Apr','Mei','Jun','Jul','Ags','Sep','Okt','Nov','Des'];
  el.textContent = `${days[now.getDay()]}, ${now.getDate()} ${months[now.getMonth()]} ${now.getFullYear()} · ${String(now.getHours()).padStart(2,'0')}.${String(now.getMinutes()).padStart(2,'0')} WIB`;
}

// ── RENDER PORTAL (dengan kontrol akses pemilik) ──────────
function lp_renderPortalWithOwnerCheck() {
  // Tombol Tulis Artikel: tampil untuk owner ATAU pengguna terdaftar (lp_isLoggedIn)
  const writeBtnWrap = document.getElementById('lp-write-btn-wrap');
  if (writeBtnWrap) writeBtnWrap.style.display = (lp_isOwner() || lp_isLoggedIn()) ? '' : 'none';
  // Form kirim artikel: tampil untuk semua (termasuk visitor yang sudah daftar)
  const kirimBox = document.getElementById('lp-kirim-form-box');
  if (kirimBox) kirimBox.style.display = lp_isLoggedIn() || lp_isOwner() ? '' : 'none';
  // Re-render konten portal
  lp_renderPortal();
}

function lp_renderPortal() {
  const isOwner = lp_isOwner();
  const filtered = lp_activeFilter === 'semua'
    ? [...lp_articles]
    : lp_articles.filter(a => a.cat === lp_activeFilter);

  filtered.sort((a,b) => b.createdAt - a.createdAt);

  // Featured
  const featuredWrap = document.getElementById('lp-featured-wrap');
  const gridWrap = document.getElementById('lp-grid-wrap');
  const empty = document.getElementById('lp-empty');
  const visitorNotice = document.getElementById('lp-visitor-notice');

  if (!featuredWrap) return;

  // Semua pengunjung bisa melihat artikel — sembunyikan visitor notice
  if (visitorNotice) visitorNotice.style.display = 'none';

  if (filtered.length === 0) {
    featuredWrap.innerHTML = '';
    if (gridWrap) gridWrap.innerHTML = '';
    if (empty) empty.style.display = '';
  } else {
    if (empty) empty.style.display = 'none';
    const [featured, ...rest] = filtered;
    featuredWrap.innerHTML = lp_renderFeatured(featured);
    if (gridWrap) gridWrap.innerHTML = rest.map(a => lp_renderCard(a)).join('');
  }

  lp_renderSidebar();
  lp_renderCatCounts();
  // Render insight stats
  setTimeout(lp_renderInsight, 100);
}

function lp_renderFeatured(a) {
  const catLabel = LP_CAT_LABELS[a.cat] || a.cat;
  const dateStr = lp_formatDateTime(a.createdAt);
  const imgHtml = a.img
    ? `<img src="${lp_esc(a.img)}" class="lp-featured-img" alt="${lp_esc(a.title)}" onerror="this.style.display='none'">`
    : `<div class="lp-featured-no-img">${lp_catIcon(a.cat)}</div>`;
  return `
    <div class="lp-featured-card" onclick="lp_openRead('${a.id}')">
      ${imgHtml}
      <div class="lp-featured-overlay"></div>
      <div class="lp-featured-body">
        <div class="lp-featured-badge">🔥 Artikel Pilihan &nbsp;·&nbsp; ${catLabel}</div>
        <div class="lp-featured-title">${lp_esc(a.title)}</div>
        <div class="lp-featured-summary">${lp_esc(a.summary)}</div>
        <div class="lp-featured-meta">
          <span>✍️ ${lp_esc(a.author || 'Novrizal, S.I.Kom., S.H., CPM')}</span>
          <span>🕐 ${dateStr}</span>
          <span>⏱ ${lp_readTime(a.body)} menit baca</span>
        </div>
        <div style="display:flex;align-items:center;gap:0.75rem;flex-wrap:wrap;">
          <button class="lp-featured-read" onclick="event.stopPropagation();lp_openRead('${a.id}')">Baca Selengkapnya →</button>
          ${lp_isOwner() ? `<button class="lp-card-edit-btn" onclick="event.stopPropagation();lp_openEditor('${a.id}')" style="flex-shrink:0;">✏️ Edit</button>` : ''}
          ${lp_isOwner() ? `<button class="lp-card-edit-btn" onclick="event.stopPropagation();lp_deleteArticle('${a.id}')" style="flex-shrink:0;color:#f87171;">🗑️ Hapus</button>` : ''}
        </div>
      </div>
    </div>`;
}

function lp_renderCard(a) {
  const catLabel = LP_CAT_LABELS[a.cat] || a.cat;
  const dateStr = lp_formatDateTime(a.createdAt);
  const imgHtml = a.img
    ? `<img src="${lp_esc(a.img)}" alt="${lp_esc(a.title)}" onerror="this.parentElement.innerHTML='<div class=lp-card-no-img>${lp_catIcon(a.cat)}</div>'">`
    : `<div class="lp-card-no-img">${lp_catIcon(a.cat)}</div>`;
  const editBtn = lp_isOwner()
    ? `<div class="lp-card-actions" onclick="event.stopPropagation()"><button class="lp-card-edit-btn" onclick="lp_openEditor('${a.id}')">✏️ Edit</button><button class="lp-card-edit-btn" onclick="lp_deleteArticle('${a.id}')" style="color:#f87171;">🗑️ Hapus</button></div>`
    : '';
  return `
    <div class="lp-article-card" onclick="lp_openRead('${a.id}')">
      <div class="lp-card-img-wrap">${imgHtml}</div>
      <div class="lp-card-body">
        <div class="lp-card-cat">${catLabel}</div>
        <div class="lp-card-title">${lp_esc(a.title)}</div>
        <div class="lp-card-summary">${lp_esc(a.summary)}</div>
        <div class="lp-card-footer">
          <div class="lp-card-meta">🕐 ${dateStr} · ⏱ ${lp_readTime(a.body)} mnt</div>
          ${editBtn}
        </div>
      </div>
    </div>`;
}

function lp_renderSidebar() {
  const list = document.getElementById('lp-recent-list');
  if (!list) return;
  const recent = [...lp_articles].sort((a,b) => b.createdAt - a.createdAt).slice(0, 6);
  if (recent.length === 0) {
    list.innerHTML = '<li style="color:var(--ink-3); font-size:0.85rem; font-style:italic;">Belum ada artikel.</li>';
    return;
  }
  list.innerHTML = recent.map(a => `
    <li onclick="lp_openRead('${a.id}')">
      <div class="lp-recent-title">${lp_esc(a.title)}</div>
      <div class="lp-recent-meta">${LP_CAT_LABELS[a.cat] || a.cat} · ${lp_formatDateTime(a.createdAt)}</div>
    </li>`).join('');
}

function lp_renderCatCounts() {
  const el = document.getElementById('lp-cat-count-list');
  if (!el) return;
  const cats = Object.entries(LP_CAT_LABELS);
  el.innerHTML = cats.map(([key, label]) => {
    const count = lp_articles.filter(a => a.cat === key).length;
    return `<li onclick="lp_filterCat('${key}', null)">
      <span>${label}</span>
      <span class="lp-cat-count">${count}</span>
    </li>`;
  }).join('');
}

// ── FILTER ────────────────────────────────────────────────
function lp_filterCat(cat, btn) {
  lp_activeFilter = cat;
  document.querySelectorAll('.lp-cat-btn').forEach(b => b.classList.remove('active'));
  if (btn) {
    btn.classList.add('active');
  } else {
    // Dipanggil dari sidebar (btn=null) — cari dan aktifkan tombol yang sesuai
    document.querySelectorAll('.lp-cat-btn').forEach(b => {
      const match = b.getAttribute('onclick') && b.getAttribute('onclick').match(/lp_filterCat\('([^']+)'/);
      if (match && match[1] === cat) b.classList.add('active');
    });
  }
  lp_renderPortal();
}

// ── OPEN READ ─────────────────────────────────────────────
function lp_openRead(id) {
  const a = lp_articles.find(x => x.id === id);
  if (!a) return;
  lp_currentArticle = a;

  // Track pembaca (kecuali preview)
  if (id !== '__preview__') lpTrackRead(id);

  const catLabel = LP_CAT_LABELS[a.cat] || a.cat;
  const dateStr = lp_formatDateTime(a.createdAt);
  const tagsHtml = a.tags
    ? a.tags.split(',').map(t => `<span class="lp-tag-chip">${lp_esc(t.trim())}</span>`).join('')
    : '';
  const imgHtml = a.img
    ? `<figure style="margin:0;padding:0;">
        <img src="${lp_esc(a.img)}" class="lp-read-hero-img" alt="${lp_esc(a.title)}" onerror="this.parentElement.style.display='none'">
        <figcaption class="lp-hero-img-caption">${lp_esc(a.imgCaption || a.title)}</figcaption>
       </figure>`
    : '';

  // Sisipkan slot iklan tengah artikel (setelah paragraf ke-3)
  const bodyWithAds = lp_injectInReadAds(a.body);
  const isPreview = a._isPreview;

  document.getElementById('lp-read-content').innerHTML = `
    ${imgHtml}
    <div class="lp-read-body-wrap">
      <!-- Branding LegalPreneur -->
      <div class="lp-read-brand">
        <span class="lp-read-brand-legal">Legal</span><span class="lp-read-brand-preneur">Preneur</span>
      </div>
      <div class="lp-read-cat">${catLabel}</div>
      <h1 class="lp-read-title">${lp_esc(a.title)}</h1>
      <div class="lp-read-byline">
        <span class="lp-byline-author">✍️ <strong>${lp_esc(a.author || 'Novrizal, S.I.Kom., S.H., CPM')}</strong></span>
        <span class="lp-byline-datetime">🕐 ${dateStr}</span>
        <span>⏱ ${lp_readTime(a.body)} menit baca</span>
        <span class="lp-read-action-btns" onclick="event.stopPropagation()" style="margin-left:auto; display:inline-flex; align-items:center; gap:0.35rem;">
          ${!isPreview && lp_isOwner() ? `<button class="lp-read-edit-btn" onclick="lp_closeRead();lp_openEditor('${a.id}')" title="Edit artikel ini">✏️ Edit</button>` : ''}
          ${!isPreview && lp_isOwner() ? `<button class="lp-read-edit-btn" onclick="lp_deleteFromRead('${a.id}')" title="Hapus artikel ini" style="color:#f87171;">🗑️ Hapus</button>` : ''}
        </span>
      </div>
      <div class="lp-read-summary-block">${lp_esc(a.summary)}</div>
      <div class="lp-read-article-body" id="lp-article-body-el">${bodyWithAds}</div>
      ${tagsHtml ? `<div class="lp-read-tags">${tagsHtml}</div>` : ''}
      <!-- Disclaimer -->
      <div class="lp-read-disclaimer">
        <span class="lp-disclaimer-icon">ℹ️</span>
        <p>Konten ini dimuat untuk tujuan edukasi dan informasi. Apabila terdapat pihak yang merasa dirugikan, hak jawab dapat disampaikan sesuai ketentuan Undang‑Undang Nomor 40 Tahun 1999 tentang Pers.</p>
      </div>
    </div>`;

  document.getElementById('lp-read-modal').style.display = '';
  document.body.style.overflow = 'hidden';
  // Update URL hash dengan ID artikel agar bisa dibagikan
  if (id !== '__preview__') {
    history.replaceState(null, '', '#artikel=' + encodeURIComponent(id));
    // Update OG/Twitter meta tags agar preview share (WA, FB, dll) menampilkan gambar & judul
    lp_updateOgTags(a);
  }
}

// ── BUKA ARTIKEL DARI DATA (untuk link share yang diterima orang lain) ──────
// Fungsi ini menampilkan artikel langsung dari data JSON yang di-decode dari URL,
// tanpa memerlukan artikel di localStorage penerima.
function lp_openReadFromData(a) {
  if (!a || !a.title || !a.body) return;
  lp_currentArticle = a;

  const catLabel = LP_CAT_LABELS[a.cat] || a.cat;
  const dateStr = lp_formatDateTime(a.createdAt);
  const tagsHtml = a.tags
    ? a.tags.split(',').map(t => `<span class="lp-tag-chip">${lp_esc(t.trim())}</span>`).join('')
    : '';
  const imgHtml = a.img
    ? `<figure style="margin:0;padding:0;"><img src="${lp_esc(a.img)}" class="lp-read-hero-img" alt="${lp_esc(a.title)}" onerror="this.parentElement.style.display='none'" style="width:100%;max-height:350px;object-fit:cover;"><figcaption class="lp-hero-img-caption">${lp_esc(a.imgCaption || a.title)}</figcaption></figure>`
    : '';
  const bodyWithAds = lp_injectInReadAds ? lp_injectInReadAds(a.body) : a.body;

  document.getElementById('lp-read-content').innerHTML = `
    ${imgHtml}
    <div class="lp-read-body-wrap">
      <div class="lp-read-brand">
        <span class="lp-read-brand-legal">Legal</span><span class="lp-read-brand-preneur">Preneur</span>
      </div>
      <div class="lp-read-cat">${catLabel}</div>
      <h1 class="lp-read-title">${lp_esc(a.title)}</h1>
      <div class="lp-read-byline">
        <span class="lp-byline-author">✍️ <strong>${lp_esc(a.author || 'Novrizal, S.I.Kom., S.H., CPM')}</strong></span>
        <span class="lp-byline-datetime">🕐 ${dateStr}</span>
        <span>⏱ ${lp_readTime(a.body)} menit baca</span>
        <span style="margin-left:auto; font-family:'DM Mono',monospace; font-size:0.6rem; color:var(--gold); padding:0.28rem 0.65rem; background:rgba(184,151,58,0.08); border:1px solid rgba(184,151,58,0.25); border-radius:4px;">🔗 Dibagikan</span>
      </div>
      <div class="lp-read-summary-block">${lp_esc(a.summary)}</div>
      <div class="lp-read-article-body" id="lp-article-body-el">${bodyWithAds}</div>
      ${tagsHtml ? `<div class="lp-read-tags">${tagsHtml}</div>` : ''}
      <div class="lp-read-disclaimer">
        <span class="lp-disclaimer-icon">ℹ️</span>
        <p>Konten ini dimuat untuk tujuan edukasi dan informasi. Apabila terdapat pihak yang merasa dirugikan, hak jawab dapat disampaikan sesuai ketentuan Undang‑Undang Nomor 40 Tahun 1999 tentang Pers.</p>
      </div>
    </div>`;

  document.getElementById('lp-read-modal').style.display = '';
  document.body.style.overflow = 'hidden';
}

// ── DROP CAP TOGGLE ───────────────────────────────────────
function lp_toggleDropcap() {
  const body = document.getElementById("lp-article-body-el");
  const btn  = document.getElementById("lp-dropcap-toggle");
  if (!body) return;
  const isOn = body.classList.contains("dropcap-on");
  if (isOn) {
    body.classList.remove("dropcap-on");
    if (btn) { btn.style.opacity = "0.55"; btn.title = "Aktifkan Drop Cap"; }
  } else {
    body.classList.add("dropcap-on");
    if (btn) { btn.style.opacity = "1"; btn.title = "Nonaktifkan Drop Cap"; }
  }
}

// Hapus artikel langsung dari modal baca
function lp_deleteFromRead(id) {
  const a = lp_articles.find(x => x.id === id);
  if (!a) return;
  if (!confirm(`Hapus artikel "${a.title}"?\nTindakan ini tidak dapat dibatalkan.`)) return;
  lp_closeRead();
  lp_deleteArticleFromFirestore(id).then(function() {
    lp_renderPortal();
  });
}


// ══════════════════════════════════════════════════════
// SHARE SYSTEM — ARTIKEL BISA DIBUKA SIAPAPUN
// Artikel di-encode sebagai base64 di URL hash, sehingga
// penerima link bisa membaca artikel tanpa perlu data di localStorage.
// ══════════════════════════════════════════════════════

// ── UPDATE OG / TWITTER META TAGS UNTUK SHARE PREVIEW ────────
// WhatsApp, Telegram, Facebook, X/Twitter membaca meta tag OG
// saat link pertama kali dibagikan. Fungsi ini memperbarui tag
// tersebut secara dinamis agar preview menampilkan gambar & judul artikel.
//
// CATATAN PENTING — GitHub Pages & hosting statis:
// Platform messenger (WA, Telegram, dll) membaca OG tags saat
// crawling, SEBELUM JavaScript dijalankan. Oleh karena itu,
// meta tag yang diubah JS di sini hanya efektif untuk platform
// yang re-crawl setelah JS selesai (mis. beberapa versi Facebook).
// Solusi terbaik: pastikan setiap artikel punya URL gambar eksternal
// (bukan base64/data:), dan gunakan tombol share yang sudah menyertakan
// URL gambar langsung di teks pesan (lihat lp_shareWA).
function lp_updateOgTags(a) {
  if (!a) return;
  // Bangun URL artikel
  const siteBase = (typeof LP_SITE_URL !== 'undefined' && LP_SITE_URL && LP_SITE_URL.trim())
    ? LP_SITE_URL.trim().replace(/\/$/, '')
    : (window.location.protocol !== 'file:' ? window.location.href.split('#')[0].replace(/\/$/, '') : '');
  const articleUrl = siteBase ? siteBase + '#artikel=' + encodeURIComponent(a.id) : '';
  const title      = a.title || 'LegalPreneur';
  const desc       = a.summary || 'Artikel hukum & literasi digital oleh Novrizal, S.I.Kom., S.H., CPM';

  // Gunakan URL gambar eksternal artikel (bukan base64).
  // Jika tidak ada gambar, buat OG image otomatis via microlink.io
  // (service gratis yang generate screenshot/card dari teks)
  let img = (a.img && !a.img.startsWith('data:') && a.img.startsWith('http')) ? a.img : '';
  if (!img && articleUrl) {
    // Generate OG image otomatis berisi judul & nama situs menggunakan
    // layanan Microlink Cards (gratis, tidak perlu API key)
    const encodedTitle = encodeURIComponent(title);
    const encodedSub   = encodeURIComponent('LegalPreneur — Portal Hukum Digital');
    img = 'https://api.microlink.io/?url=' + encodeURIComponent(articleUrl)
        + '&screenshot=true&meta=false&embed=screenshot.url';
  }

  // Helper update meta
  function setMeta(id, val) {
    const el = document.getElementById(id);
    if (el && val) el.setAttribute('content', val);
  }

  document.title = title + ' — LegalPreneur';
  setMeta('og-title',       title);
  setMeta('og-description', desc);
  setMeta('og-url',         articleUrl);
  setMeta('tw-title',       title);
  setMeta('tw-description', desc);
  if (img) {
    setMeta('og-image', img);
    setMeta('tw-image', img);
    document.getElementById('tw-card')?.setAttribute('content', 'summary_large_image');
  } else {
    document.getElementById('tw-card')?.setAttribute('content', 'summary');
  }
}

// Reset OG tags ke default situs (dipanggil saat modal artikel ditutup)
function lp_resetOgTags() {
  const defaultTitle = 'LegalPreneur — Advokat & Konsultan Hukum Digital';
  const defaultDesc  = 'LegalPreneur oleh Novrizal, S.I.Kom., S.H., CPM — Advokat & Konsultan Hukum, Mediator, dan platform literasi hukum digital terpercaya.';
  document.title = defaultTitle;
  ['og-title','tw-title'].forEach(id => document.getElementById(id)?.setAttribute('content', defaultTitle));
  ['og-description','tw-description'].forEach(id => document.getElementById(id)?.setAttribute('content', defaultDesc));
  ['og-image','tw-image'].forEach(id => document.getElementById(id)?.setAttribute('content', ''));
  ['og-url'].forEach(id => document.getElementById(id)?.setAttribute('content', ''));
}

function lp_encodeArticleToUrl(article) {
  // Gunakan format pendek: hanya ID artikel (#artikel=ID)
  // Penerima link akan load artikel dari Google Sheets berdasarkan ID

  // Prioritas sumber URL:
  // 1. LP_SITE_URL (dikonfigurasi manual - paling andal untuk share)
  // 2. window.location.href jika BUKAN protokol file://
  // 3. Jika file:// (buka lokal), kembalikan hanya hash saja
  var base;
  if (typeof LP_SITE_URL !== 'undefined' && LP_SITE_URL && LP_SITE_URL.trim() !== '') {
    base = LP_SITE_URL.trim().split('#')[0].split('?')[0].replace(/\/$/, '');
  } else if (window.location.protocol !== 'file:') {
    base = window.location.href.split('#')[0].split('?')[0].replace(/\/$/, '');
  } else {
    // File lokal: tidak bisa dibagikan ke luar, tampilkan peringatan
    return '#artikel=' + encodeURIComponent(article.id);
  }
  return base + '#artikel=' + encodeURIComponent(article.id);
}

function lp_getShareUrl() {
  if (!lp_currentArticle || lp_currentArticle.id === '__preview__') {
    if (window.location.protocol === 'file:') return '';
    return window.location.href.split('#')[0];
  }
  var url = lp_encodeArticleToUrl(lp_currentArticle);
  // Jika URL masih relatif (file lokal, LP_SITE_URL belum diisi), beri tahu user
  if (!url.startsWith('http')) {
    return 'FILE_LOKAL_BELUM_UPLOAD_KE_HOSTING';
  }
  return url;
}

function lp_getShareText() {
  if (!lp_currentArticle) return '';
  return `${lp_currentArticle.title} — ${lp_currentArticle.summary.slice(0,80)}...`;
}

// ── COPY TO CLIPBOARD — iframe-safe (Google Sites compatible) ────────────────
// Google Sites embed HTML dalam <iframe> yang memblokir clipboard API dan
// execCommand. Solusi: coba clipboard API dulu, jika gagal tampilkan modal
// popup berisi link agar user bisa menyalin secara manual (Ctrl+C / tap & hold).
function lp_copyToClipboard(text, btnEl, successMsg, origHTML) {
  const markDone = () => {
    if (btnEl) {
      btnEl.textContent = successMsg;
      setTimeout(() => { btnEl.innerHTML = origHTML || successMsg; }, 2500);
    }
  };

  const showCopyModal = () => {
    // Hapus modal lama jika ada
    const old = document.getElementById('lp-copy-modal');
    if (old) old.remove();

    const modal = document.createElement('div');
    modal.id = 'lp-copy-modal';
    modal.style.cssText = `
      position:fixed;inset:0;z-index:9999;
      display:flex;align-items:center;justify-content:center;
      background:rgba(15,14,11,0.75);backdrop-filter:blur(4px);
      padding:1rem;
    `;
    modal.innerHTML = `
      <div style="
        background:var(--white,#fdfcf9);border-radius:10px;
        padding:1.75rem 2rem;max-width:540px;width:100%;
        box-shadow:0 24px 80px rgba(15,14,11,0.35);
        font-family:'Crimson Pro',Georgia,serif;
      ">
        <div style="font-family:'DM Mono',monospace;font-size:0.65rem;letter-spacing:0.15em;color:var(--gold,#b8973a);text-transform:uppercase;margin-bottom:0.75rem;">🔗 Salin Link Artikel</div>
        <div style="font-family:'Playfair Display',serif;font-size:1.05rem;font-weight:700;color:var(--ink,#0f0e0b);margin-bottom:1rem;line-height:1.35;">
          Pilih teks di bawah lalu tekan <kbd style="background:var(--cream-2,#ede6d6);border:1px solid #ccc;border-radius:3px;padding:0.1rem 0.4rem;font-size:0.85rem;">Ctrl+C</kbd> atau tahan untuk menyalin
        </div>
        <textarea id="lp-copy-ta" readonly style="
          width:100%;min-height:80px;padding:0.75rem;
          font-family:'DM Mono',monospace;font-size:0.68rem;
          background:var(--cream,#f5f0e8);border:2px solid var(--gold,#b8973a);
          border-radius:6px;color:var(--ink,#0f0e0b);
          resize:none;outline:none;word-break:break-all;line-height:1.5;
        ">${text}</textarea>
        <div style="display:flex;gap:0.75rem;margin-top:1rem;flex-wrap:wrap;">
          <button id="lp-copy-try-btn" style="
            flex:1;background:var(--ink,#0f0e0b);color:var(--gold-pale,#f0e4c0);
            border:none;border-radius:5px;padding:0.75rem 1rem;
            font-family:'DM Mono',monospace;font-size:0.7rem;font-weight:700;
            letter-spacing:0.08em;cursor:pointer;transition:all 0.2s;
          ">📋 Salin Otomatis</button>
          <button onclick="document.getElementById('lp-copy-modal').remove()" style="
            background:transparent;border:1px solid rgba(92,87,73,0.3);
            border-radius:5px;padding:0.75rem 1rem;
            font-family:'DM Mono',monospace;font-size:0.7rem;
            color:var(--ink-3,#5c5749);cursor:pointer;
          ">✕ Tutup</button>
        </div>
        <div id="lp-copy-status" style="font-family:'DM Mono',monospace;font-size:0.65rem;color:var(--ink-3,#5c5749);margin-top:0.6rem;min-height:1.2em;text-align:center;"></div>
      </div>`;

    document.body.appendChild(modal);

    // Auto-select teks di textarea
    const ta = document.getElementById('lp-copy-ta');
    setTimeout(() => { ta.focus(); ta.select(); }, 80);

    // Tombol salin otomatis
    document.getElementById('lp-copy-try-btn').addEventListener('click', () => {
      const statusEl = document.getElementById('lp-copy-status');
      ta.focus(); ta.select();
      // Coba clipboard API
      if (navigator.clipboard && navigator.clipboard.writeText) {
        navigator.clipboard.writeText(text)
          .then(() => {
            statusEl.textContent = '✅ Berhasil disalin!';
            statusEl.style.color = '#22c55e';
            markDone();
            setTimeout(() => modal.remove(), 1200);
          })
          .catch(() => {
            // Coba execCommand
            try {
              const ok = document.execCommand('copy');
              if (ok) {
                statusEl.textContent = '✅ Berhasil disalin!';
                statusEl.style.color = '#22c55e';
                markDone();
                setTimeout(() => modal.remove(), 1200);
              } else {
                statusEl.textContent = 'Tekan Ctrl+C (Windows/Linux) atau ⌘+C (Mac) setelah teks terpilih.';
              }
            } catch(e) {
              statusEl.textContent = 'Tekan Ctrl+C (Windows/Linux) atau ⌘+C (Mac) setelah teks terpilih.';
            }
          });
      } else {
        try {
          const ok = document.execCommand('copy');
          statusEl.textContent = ok ? '✅ Berhasil disalin!' : 'Tekan Ctrl+C setelah teks terpilih.';
          if (ok) { statusEl.style.color = '#22c55e'; markDone(); setTimeout(() => modal.remove(), 1200); }
        } catch(e) {
          statusEl.textContent = 'Tekan Ctrl+C setelah teks terpilih di atas.';
        }
      }
    });

    // Tutup modal jika klik di luar
    modal.addEventListener('click', (e) => { if (e.target === modal) modal.remove(); });
  };

  // Coba clipboard API langsung terlebih dahulu
  if (navigator.clipboard && navigator.clipboard.writeText) {
    navigator.clipboard.writeText(text)
      .then(() => { markDone(); })
      .catch(() => showCopyModal());
  } else {
    // Coba execCommand dulu sebelum tampilkan modal
    try {
      const ta = document.createElement('textarea');
      ta.value = text; ta.style.cssText = 'position:fixed;left:-9999px;top:-9999px;opacity:0;';
      document.body.appendChild(ta); ta.focus(); ta.select();
      const ok = document.execCommand('copy');
      document.body.removeChild(ta);
      if (ok) { markDone(); } else { showCopyModal(); }
    } catch(e) {
      showCopyModal();
    }
  }
}

function lp_shareWA() {
  const url = lp_getShareUrl();
  if (!url || !url.startsWith('http')) {
    lp_shareCopy();
    return;
  }
  const a = lp_currentArticle;
  const title   = a ? a.title : 'Artikel LegalPreneur';
  const summary = a ? a.summary.slice(0, 120) + '...' : '';
  // Sertakan URL gambar artikel agar WhatsApp auto-generate preview thumbnail
  const imgLine = (a && a.img && !a.img.startsWith('data:') && a.img.startsWith('http'))
    ? '\n\n📷 ' + a.img : '';
  const text = encodeURIComponent(
    '*' + title + '*\n\n' +
    summary + '\n\n' +
    'Baca selengkapnya:\n' + url + imgLine + '\n\n' +
    '— Portal Hukum LegalPreneur\nNovrizal, S.I.Kom., S.H., CPM'
  );
  window.open('https://wa.me/?text=' + text, '_blank');
}

function lp_shareCopy() {
  const btn = document.getElementById('lp-copy-btn');
  const origHTML = btn ? btn.innerHTML : '🔗 Salin Link';
  var url = lp_getShareUrl();
  if (!url || url === 'FILE_LOKAL_BELUM_UPLOAD_KE_HOSTING' || url === '') {
    // File dibuka lokal, belum di-hosting
    var old2 = document.getElementById('lp-copy-modal');
    if (old2) old2.remove();
    var modal2 = document.createElement('div');
    modal2.id = 'lp-copy-modal';
    modal2.style.cssText = 'position:fixed;inset:0;z-index:9999;display:flex;align-items:center;justify-content:center;background:rgba(15,14,11,0.75);backdrop-filter:blur(4px);padding:1rem;';
    modal2.innerHTML = '<div style="background:var(--white,#fdfcf9);border-radius:10px;padding:1.75rem 2rem;max-width:480px;width:100%;box-shadow:0 24px 80px rgba(15,14,11,0.35);font-family:Crimson Pro,Georgia,serif;"><div style="font-family:DM Mono,monospace;font-size:0.65rem;letter-spacing:0.15em;color:#f59e0b;text-transform:uppercase;margin-bottom:0.75rem;">⚠️ Konfigurasi Diperlukan</div><div style="font-size:1rem;color:var(--ink,#0f0e0b);margin-bottom:1rem;line-height:1.6;">Website ini dibuka dari <strong>file lokal</strong>. Link share hanya bisa berfungsi jika website sudah di-upload ke hosting (Google Sites, Netlify, dll).<br><br>Isi variabel <code style="background:#f5f0e8;padding:0.2rem 0.4rem;border-radius:3px;font-size:0.85rem;">LP_SITE_URL</code> dengan URL website Anda setelah di-hosting.</div><button onclick="document.getElementById(\'lp-copy-modal\').remove()" style="background:var(--ink,#0f0e0b);color:var(--gold-pale,#f0e4c0);border:none;border-radius:5px;padding:0.65rem 1.25rem;font-family:DM Mono,monospace;font-size:0.7rem;cursor:pointer;">✕ Tutup</button></div>';
    modal2.addEventListener('click', function(e){ if(e.target===modal2) modal2.remove(); });
    document.body.appendChild(modal2);
    return;
  }
  lp_copyToClipboard(url, btn, '✅ Tersalin!', origHTML);
}

function lp_shareX() {
  const text = encodeURIComponent(lp_getShareText() + ' #LegalPreneur #Hukum');
  const url = encodeURIComponent(lp_getShareUrl());
  window.open(`https://x.com/intent/tweet?text=${text}&url=${url}`, '_blank');
}

function lp_shareFB() {
  const url = encodeURIComponent(lp_getShareUrl());
  window.open(`https://www.facebook.com/sharer/sharer.php?u=${url}`, '_blank');
}

function lp_shareIG() {
  const btn = document.querySelector('.lp-share-btn-ig');
  const origHTML = btn ? btn.innerHTML : '📸 Instagram';
  lp_copyToClipboard(lp_getShareUrl(), btn, '✅ Link disalin! Paste di Bio/Story IG', origHTML);
  setTimeout(() => window.open('https://www.instagram.com/', '_blank'), 300);
}

function lp_shareThreads() {
  const text = encodeURIComponent(
    `${lp_getShareText()}\n\nBaca: ${lp_getShareUrl()}\n\n#LegalPreneur #Hukum`
  );
  window.open(`https://www.threads.net/intent/post?text=${text}`, '_blank');
}

// ── INJECT IN-READ ADS ─────────────────────────────────────
// Sisipkan slot iklan Shopee + Lynk.id di dalam isi artikel (setelah paragraf ke-3)
function lp_injectInReadAds(body) {
  if (!body) return body;
  // Pisahkan per tag blok tingkat atas
  const tempDiv = document.createElement('div');
  tempDiv.innerHTML = body;
  const children = Array.from(tempDiv.childNodes);
  const blockTags = ['P','H1','H2','H3','H4','H5','H6','BLOCKQUOTE','UL','OL','TABLE','FIGURE','HR','DIV'];
  let blockCount = 0;
  let injected = false;
  const result = [];
  for (const node of children) {
    result.push(node.outerHTML || node.textContent);
    if (!injected && node.nodeType === 1 && blockTags.includes(node.tagName)) {
      blockCount++;
      // Sisipkan setelah blok ke-3 (atau ke-2 jika artikel pendek)
      if (blockCount === 3) {
        injected = true;
        result.push(`
          <div class="lp-inread-ad lp-inread-ad-shopee" style="margin:2rem 0;">
            <div class="lp-inread-ad-label">🛒 Iklan · Shopee Affiliate</div>
            <div class="lp-inread-ad-body">
              <div class="lp-inread-ad-icon">🛒</div>
              <div class="lp-inread-ad-text-wrap">
                <div class="lp-inread-ad-title">Produk Pilihan di Shopee</div>
                <div class="lp-inread-ad-desc">Cari produk berkualitas yang telah diseleksi — dari kebutuhan harian hingga alat produktivitas.</div>
              </div>
              <a href="#" onclick="showPage('affiliate');document.getElementById('lp-read-modal').style.display='none';document.body.style.overflow='';return false;" class="lp-inread-ad-cta">🛍️ Lihat Katalog</a>
            </div>
          </div>`);
      }
    }
  }
  // Sisipkan Lynk.id slot menjelang akhir artikel (setelah 2/3 konten)
  const midPoint = Math.floor(children.filter(n => n.nodeType === 1 && blockTags.includes(n?.tagName)).length * 0.65);
  if (blockCount > 5) {
    // Sisipkan Lynk.id setelah 65% blok
    let bc2 = 0;
    let injected2 = false;
    const result2 = [];
    for (const chunk of result) {
      result2.push(chunk);
      if (!injected2 && typeof chunk === 'string') {
        const m = chunk.match(/^<(p|h[1-6]|blockquote|ul|ol|div|figure)\b/i);
        if (m) {
          bc2++;
          if (bc2 === midPoint) {
            injected2 = true;
            result2.push(`
              <div class="lp-inread-ad lp-inread-ad-lynk" style="margin:2rem 0;">
                <div class="lp-inread-ad-label">📚 Iklan · Produk Digital</div>
                <div class="lp-inread-ad-body">
                  <div class="lp-inread-ad-icon">📖</div>
                  <div class="lp-inread-ad-text-wrap">
                    <div class="lp-inread-ad-title">E-Book & Panduan Hukum Praktis</div>
                    <div class="lp-inread-ad-desc">Tersedia di Lynk.id — panduan hukum, simulasi CPNS, game edukasi, dan lebih banyak lagi.</div>
                  </div>
                  <a href="http://lynk.id/novriz.digital" target="_blank" class="lp-inread-ad-cta">📖 Lihat di Lynk.id</a>
                </div>
              </div>`);
          }
        }
      }
    }
    return result2.join('');
  }
  return result.join('');
}

// ── EDITOR ────────────────────────────────────────────────
function lp_buildTemplateGrid() {
  const grid = document.getElementById('lp-template-grid');
  if (!grid) return;
  grid.innerHTML = LP_TEMPLATES.map((t, i) => `
    <div class="lp-tpl-card" onclick="lp_applyTemplate(${i})">
      <div class="lp-tpl-icon">${t.icon}</div>
      <div class="lp-tpl-name">${t.name}</div>
      <div class="lp-tpl-title">${t.title}</div>
    </div>`).join('');
}

function lp_applyTemplate(i) {
  const t = LP_TEMPLATES[i];
  document.getElementById('lp-ed-title').value = t.title;
  document.getElementById('lp-ed-cat').value = t.cat;
  document.getElementById('lp-ed-summary').value = t.summary;
  document.getElementById('lp-ed-body').innerHTML = t.body;
  document.getElementById('lp-ed-tags').value = t.tags;
  lp_updateSummaryCount();
  document.getElementById('lp-ed-title').scrollIntoView({ behavior: 'smooth', block: 'nearest' });
}

function lp_openEditor(id) {
  // Hak akses: pemilik web ATAU pengguna yang sudah login
  if (!lp_isOwner() && !lp_isLoggedIn()) {
    lp_showPortalToast('🔒 Masuk atau daftar terlebih dahulu untuk menulis artikel.');
    lp_showAuthBox();
    return;
  }
  // Auto-isi nama penulis dari user session jika belum diisi
  const defaultAuthorVal = lp_isOwner()
    ? 'Novrizal, S.I.Kom., S.H., CPM'
    : (lp_getLoggedInUser()?.name || '');
  lp_editId = id;
  const modeLabel = document.getElementById('lp-editor-mode-label');

  if (id) {
    // Edit artikel yang sudah ada — hanya owner atau penulis artikel itu
    const a = lp_articles.find(x => x.id === id);
    if (!a) return;
    if (!lp_isOwner() && lp_getLoggedInUser()?.name !== a.author) {
      lp_showPortalToast('🔒 Anda hanya bisa mengedit artikel milik Anda sendiri.');
      return;
    }
    modeLabel.textContent = '✏️ Edit Artikel';
    document.getElementById('lp-ed-title').value   = a.title;
    document.getElementById('lp-ed-cat').value     = a.cat;
    document.getElementById('lp-ed-author').value  = a.author || defaultAuthorVal;
    document.getElementById('lp-ed-summary').value = a.summary;
    document.getElementById('lp-ed-body').innerHTML = a.body;
    document.getElementById('lp-ed-tags').value    = a.tags || '';
    if (a.img) {
      document.getElementById('lp-ed-imgurl').value = a.img;
      lp_previewUrl(a.img);
    } else { lp_clearImg(); }
    if (document.getElementById('lp-ed-imgcaption')) document.getElementById('lp-ed-imgcaption').value = a.imgCaption || '';
  } else {
    // Artikel baru — coba pulihkan dari draft tersimpan
    modeLabel.textContent = '✏️ Tulis Artikel Baru';
    const DRAFT_KEY = 'lp_draft_v2';
    let restoredDraft = false;
    try {
      const saved = localStorage.getItem(DRAFT_KEY);
      if (saved) {
        const draft = JSON.parse(saved);
        // Hanya pulihkan draft baru (bukan draft edit artikel lama)
        if (!draft.id && draft.title) {
          document.getElementById('lp-ed-title').value   = draft.title || '';
          document.getElementById('lp-ed-cat').value     = draft.cat || '';
          document.getElementById('lp-ed-author').value  = draft.author || 'Novrizal, S.I.Kom., S.H., CPM';
          document.getElementById('lp-ed-summary').value = draft.summary || '';
          document.getElementById('lp-ed-body').innerHTML = draft.body || '';
          document.getElementById('lp-ed-tags').value    = draft.tags || '';
          if (draft.img) { lp_showImgPreview(draft.img); } else { lp_clearImg(); }
          restoredDraft = true;
        } else {
          lp_clearForm();
        }
      } else {
        lp_clearForm();
      }
    } catch(e) { lp_clearForm(); }

    if (restoredDraft) {
      setTimeout(() => lp_showEditorMsg('📂 Draft sebelumnya dipulihkan otomatis.', 'success'), 300);
    }
  }

  document.getElementById('lp-editor-msg').style.display = 'none';
  lp_updateSummaryCount();
  // Tampilkan tombol Hapus hanya saat edit artikel yang sudah ada
  const delBtn = document.getElementById('lp-ed-delete-btn');
  if (delBtn) delBtn.style.display = id ? '' : 'none';
  document.getElementById('lp-editor-modal').style.display = '';
  document.body.style.overflow = 'hidden';
  lp_startAutoSave();
}

function lp_clearForm() {
  const defaultAuthor = lp_isOwner()
    ? 'Novrizal, S.I.Kom., S.H., CPM'
    : (lp_getLoggedInUser()?.name || '');
  document.getElementById('lp-ed-title').value   = '';
  document.getElementById('lp-ed-cat').value     = '';
  document.getElementById('lp-ed-author').value  = defaultAuthor;
  document.getElementById('lp-ed-summary').value = '';
  document.getElementById('lp-ed-body').innerHTML = '';
  document.getElementById('lp-ed-tags').value    = '';
  lp_clearImg();
}

function lp_confirmClose() {
  const title = document.getElementById('lp-ed-title').value.trim();
  const body  = document.getElementById('lp-ed-body').innerHTML.trim();
  if (title || body) {
    // Auto-simpan draft sebelum tutup
    lp_saveDraft(true);
    const status = document.getElementById('lp-autosave-status');
    if (status) {
      const t = new Date();
      status.textContent = `💾 Draft tersimpan pukul ${String(t.getHours()).padStart(2,'0')}.${String(t.getMinutes()).padStart(2,'0')}`;
    }
  }
  lp_closeEditor();
}
function lp_closeEditor() {
  document.getElementById('lp-editor-modal').style.display = 'none';
  document.body.style.overflow = '';
  lp_stopAutoSave();
}

function lp_updateSummaryCount() {
  const ta = document.getElementById('lp-ed-summary');
  const counter = document.getElementById('lp-summary-count');
  if (ta && counter) counter.textContent = ta.value.length;
}
document.addEventListener('DOMContentLoaded', () => {
  const ta = document.getElementById('lp-ed-summary');
  if (ta) ta.addEventListener('input', lp_updateSummaryCount);
});

// ── TOOLBAR FORMAT ────────────────────────────────────────
function lp_fmt(cmd) {
  document.execCommand(cmd, false, null);
  document.getElementById('lp-ed-body').focus();
}
function lp_fmtBlock(tag) {
  document.execCommand('formatBlock', false, tag);
  document.getElementById('lp-ed-body').focus();
}
function lp_setFont(font) {
  if (!font) return;
  document.execCommand('fontName', false, font);
  document.getElementById('lp-ed-body').focus();
}
function lp_setFontSize(size) {
  if (!size) return;
  document.execCommand('fontSize', false, size);
  document.getElementById('lp-ed-body').focus();
}
// ── UNDO / REDO ───────────────────────────────────────────
function lp_undo() {
  document.getElementById('lp-ed-body').focus();
  document.execCommand('undo', false, null);
}
function lp_redo() {
  document.getElementById('lp-ed-body').focus();
  document.execCommand('redo', false, null);
}

// ── HELPER: WRAP SELECTION DENGAN SPAN INLINE STYLE ────────
// Pendekatan ini menjamin warna tersimpan sebagai HTML inline style
// yang akan tampil identik saat preview maupun diterbitkan.
function lp_wrapSelectionWithStyle(styleProp, styleVal) {
  const editor = document.getElementById('lp-ed-body');
  editor.focus();
  const sel = window.getSelection();
  if (!sel || sel.rangeCount === 0 || sel.isCollapsed) return;
  const range = sel.getRangeAt(0);

  // Cek apakah seluruh selection sudah punya style ini → toggle off
  const frag = range.cloneContents();
  const tempDiv = document.createElement('div');
  tempDiv.appendChild(frag);
  const allStyled = Array.from(tempDiv.querySelectorAll('*')).every(el => {
    return el.style && el.style[styleProp] === styleVal;
  });

  const span = document.createElement('span');
  if (styleProp === 'color') {
    // Warna default hitam → tidak perlu span (hapus style saja)
    if (styleVal === '#0f0e0b' || styleVal === '#000000' || styleVal === 'black') {
      lp_removeColorFromSelection('color');
      return;
    }
    span.style.color = styleVal;
  } else if (styleProp === 'backgroundColor') {
    if (styleVal === 'transparent' || styleVal === '') {
      lp_removeColorFromSelection('backgroundColor');
      return;
    }
    span.style.backgroundColor = styleVal;
  }

  try {
    range.surroundContents(span);
  } catch(e) {
    // surroundContents gagal jika selection parsial — pakai extractContents
    const extracted = range.extractContents();
    span.appendChild(extracted);
    range.insertNode(span);
  }
  // Restore selection
  sel.removeAllRanges();
  const newRange = document.createRange();
  newRange.selectNodeContents(span);
  sel.addRange(newRange);
}

// Hapus color/backgroundColor dari selection (kembalikan ke default)
function lp_removeColorFromSelection(prop) {
  const editor = document.getElementById('lp-ed-body');
  const sel = window.getSelection();
  if (!sel || sel.rangeCount === 0) return;
  const range = sel.getRangeAt(0);
  const frag = range.cloneContents();
  const tempDiv = document.createElement('div');
  tempDiv.appendChild(frag);
  // Hapus inline style dari semua span dalam selection
  tempDiv.querySelectorAll('span').forEach(s => { s.style[prop] = ''; });
  // Ganti konten
  range.deleteContents();
  range.insertNode(tempDiv.firstChild || document.createTextNode(''));
}

function lp_setColor(color) {
  lp_wrapSelectionWithStyle('color', color);
  lp_updateColorLabel('lp-txt-color-label', color);
  const picker = document.getElementById('lp-txt-color');
  if (picker) picker.value = (color.startsWith('#') && color.length === 7) ? color : picker.value;
  document.getElementById('lp-ed-body').focus();
}
function lp_setHighlight(color) {
  lp_wrapSelectionWithStyle('backgroundColor', color);
  lp_updateBgLabel('lp-bg-color-label', color);
  const picker = document.getElementById('lp-bg-color');
  if (picker && color !== 'transparent' && color.startsWith('#')) picker.value = color;
  document.getElementById('lp-ed-body').focus();
}
function lp_applyPresetColor(color) {
  lp_wrapSelectionWithStyle('color', color);
  lp_updateColorLabel('lp-txt-color-label', color);
  const picker = document.getElementById('lp-txt-color');
  if (picker && color.startsWith('#') && color.length === 7) picker.value = color;
  document.getElementById('lp-ed-body').focus();
}
function lp_applyPresetHighlight(color) {
  lp_wrapSelectionWithStyle('backgroundColor', color);
  lp_updateBgLabel('lp-bg-color-label', color);
  const picker = document.getElementById('lp-bg-color');
  if (picker && color !== 'transparent' && color.startsWith('#')) picker.value = color;
  document.getElementById('lp-ed-body').focus();
}
function lp_updateColorLabel(id, color) {
  const el = document.getElementById(id);
  if (!el) return;
  el.style.color = color;
  el.style.textDecorationColor = color;
  el.style.textDecoration = 'underline';
  el.style.textDecorationThickness = '3px';
}
function lp_updateBgLabel(id, color) {
  const el = document.getElementById(id);
  if (!el) return;
  if (color === 'transparent' || color === '') {
    el.style.background = 'transparent';
    el.style.borderBottomColor = 'transparent';
    el.style.color = 'rgba(245,240,232,0.6)';
  } else {
    el.style.background = color;
    el.style.borderBottomColor = color;
    const r = parseInt(color.slice(1,3),16)||0,
          g = parseInt(color.slice(3,5),16)||0,
          b = parseInt(color.slice(5,7),16)||0;
    const lum = 0.299*r + 0.587*g + 0.114*b;
    el.style.color = lum > 140 ? '#0f0e0b' : '#fdfcf9';
  }
}
function lp_insertHR() {
  document.execCommand('insertHorizontalRule', false, null);
  document.getElementById('lp-ed-body').focus();
}
function lp_insertLink() {
  const url = prompt('Masukkan URL tautan:');
  if (url) document.execCommand('createLink', false, url);
  document.getElementById('lp-ed-body').focus();
}

// ── SISIPKAN SLOT IKLAN DI EDITOR ─────────────────────────
function lp_insertShopeeAd() {
  const shopeeUrl = prompt('URL Shopee Affiliate (kosongkan untuk pakai default katalog):', '');
  const url = shopeeUrl && shopeeUrl.trim() ? shopeeUrl.trim() : '#';
  const label = prompt('Nama / deskripsi produk Shopee:', 'Produk Pilihan di Shopee') || 'Produk Pilihan di Shopee';
  const html = `<div class="lp-inread-ad lp-inread-ad-shopee"><div class="lp-inread-ad-label">🛒 Iklan · Shopee Affiliate</div><div class="lp-inread-ad-body"><div class="lp-inread-ad-icon">🛒</div><div class="lp-inread-ad-text-wrap"><div class="lp-inread-ad-title">${label}</div><div class="lp-inread-ad-desc">Klik untuk melihat produk dan melakukan pembelian di Shopee.</div></div><a href="${url}" target="_blank" class="lp-inread-ad-cta">🛍️ Beli di Shopee</a></div></div><p></p>`;
  document.execCommand('insertHTML', false, html);
  document.getElementById('lp-ed-body').focus();
}

function lp_insertLynkAd() {
  const lynkUrl = prompt('URL Lynk.id / Produk Digital (kosongkan untuk pakai default):', 'http://lynk.id/novriz.digital') || 'http://lynk.id/novriz.digital';
  const label = prompt('Nama produk digital:', 'Panduan Hukum Praktis oleh Novrizal, S.I.Kom., S.H., CPM') || 'Panduan Hukum Praktis oleh Novrizal, S.I.Kom., S.H., CPM';
  const html = `<div class="lp-inread-ad lp-inread-ad-lynk"><div class="lp-inread-ad-label">📚 Iklan · Produk Digital</div><div class="lp-inread-ad-body"><div class="lp-inread-ad-icon">📖</div><div class="lp-inread-ad-text-wrap"><div class="lp-inread-ad-title">${label}</div><div class="lp-inread-ad-desc">Tersedia di Lynk.id — e-book, game edukasi hukum, dan panduan digital.</div></div><a href="${lynkUrl}" target="_blank" class="lp-inread-ad-cta">📖 Dapatkan Sekarang</a></div></div><p></p>`;
  document.execCommand('insertHTML', false, html);
  document.getElementById('lp-ed-body').focus();
}

// ── IMAGE HANDLING ────────────────────────────────────────
function lp_handleImg(input) {
  const file = input.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = e => {
    lp_showImgPreview(e.target.result);
    document.getElementById('lp-ed-imgurl').value = '';
  };
  reader.readAsDataURL(file);
}
function lp_previewUrl(url) {
  if (url && url.startsWith('http')) lp_showImgPreview(url);
  else if (!url) lp_clearImg();
}
function lp_showImgPreview(src) {
  document.getElementById('lp-img-placeholder').style.display = 'none';
  const img = document.getElementById('lp-img-preview');
  img.src = src;
  img.style.display = 'block';
}
function lp_clearImg() {
  document.getElementById('lp-img-placeholder').style.display = '';
  const img = document.getElementById('lp-img-preview');
  img.style.display = 'none';
  img.src = '';
  document.getElementById('lp-ed-imgurl').value = '';
  document.getElementById('lp-ed-img').value = '';
}
function lp_getImgSrc() {
  const preview = document.getElementById('lp-img-preview');
  return preview.style.display !== 'none' ? preview.src : '';
}

// ── AUTO SAVE ─────────────────────────────────────────────
function lp_startAutoSave() {
  lp_stopAutoSave();
  lp_autoSaveTimer = setInterval(() => { lp_saveDraft(true); }, 30000);
}
function lp_stopAutoSave() {
  if (lp_autoSaveTimer) clearInterval(lp_autoSaveTimer);
}
function lp_saveDraft(silent) {
  // Hak akses: pemilik web ATAU pengguna yang sudah login
  if (!lp_isOwner() && !lp_isLoggedIn() && !silent) {
    lp_showEditorMsg('🔒 Masuk atau daftar terlebih dahulu untuk menyimpan artikel.', 'error');
    return;
  }

  const title = document.getElementById('lp-ed-title').value.trim();
  if (!title) { if (!silent) lp_showEditorMsg('❌ Judul artikel wajib diisi.', 'error'); return; }
  const DRAFT_KEY = 'lp_draft_v2';
  const draft = {
    id: lp_editId,
    title, cat: document.getElementById('lp-ed-cat').value,
    author: document.getElementById('lp-ed-author').value,
    summary: document.getElementById('lp-ed-summary').value,
    body: document.getElementById('lp-ed-body').innerHTML,
    tags: document.getElementById('lp-ed-tags').value,
    img: lp_getImgSrc()
  };
  try { localStorage.setItem(DRAFT_KEY, JSON.stringify(draft)); } catch(e) {}

  // Jika artikel bukan template cepat (ada konten nyata), simpan juga ke Google Sheets sebagai draft
  if (!silent && lp_sheetsReady && draft.title && draft.body && draft.body !== '<br>') {
    const draftArticle = {
      id: lp_editId || ('draft_' + Date.now() + '_' + Math.random().toString(36).slice(2,7)),
      title: '[DRAFT] ' + draft.title,
      cat: draft.cat || 'umum',
      author: draft.author || 'Novrizal, S.I.Kom., S.H., CPM',
      summary: draft.summary || '',
      body: draft.body,
      tags: draft.tags || '',
      img: draft.img && !draft.img.startsWith('data:') ? draft.img : '',
      createdAt: Date.now(),
      updatedAt: Date.now(),
      status: 'draft'
    };
    fetch(LP_SHEETS_URL, {
      method: 'POST',
      mode: 'no-cors',
      headers: { 'Content-Type': 'text/plain' },
      body: JSON.stringify({ action: 'save', article: draftArticle })
    }).catch(function() {
      lp_gasJsonpAction({ action: 'save', article: draftArticle });
    });
  }

  const status = document.getElementById('lp-autosave-status');
  if (status) {
    const t = new Date();
    status.textContent = `💾 Draft tersimpan pukul ${String(t.getHours()).padStart(2,'0')}.${String(t.getMinutes()).padStart(2,'0')}`;
  }
  if (!silent) lp_showEditorMsg('💾 Draft berhasil disimpan ke perangkat & Google Sheets.', 'success');
}

function lp_clearDraftAndForm() {
  if (!confirm('Hapus draft ini dan kosongkan form? Artikel yang sudah diterbitkan tidak terpengaruh.')) return;
  try { localStorage.removeItem('lp_draft_v2'); } catch(e) {}
  lp_clearForm();
  lp_editId = null;
  lp_updateSummaryCount();
  const status = document.getElementById('lp-autosave-status');
  if (status) status.textContent = '';
  lp_showEditorMsg('🗑️ Draft dihapus. Form telah dikosongkan.', 'success');
}

// ── PREVIEW ───────────────────────────────────────────────
// State tersimpan sementara saat preview agar editor bisa dibuka kembali
let lp_previewState = null;

function lp_previewArticle() {
  const title   = document.getElementById('lp-ed-title').value.trim();
  const summary = document.getElementById('lp-ed-summary').value.trim();
  if (!title || !summary) {
    lp_showEditorMsg('❌ Isi judul dan ringkasan untuk preview.', 'error');
    return;
  }

  // Simpan state editor sebelum preview
  lp_previewState = {
    editId:  lp_editId,
    title,
    cat:     document.getElementById('lp-ed-cat').value,
    author:  document.getElementById('lp-ed-author').value,
    summary,
    body:    document.getElementById('lp-ed-body').innerHTML,
    tags:    document.getElementById('lp-ed-tags').value,
    img:     lp_getImgSrc()
  };

  // Simpan draft otomatis agar tidak hilang
  lp_saveDraft(true);

  const fakeArticle = {
    id: '__preview__',
    title, summary,
    cat:    lp_previewState.cat || 'hukum',
    author: lp_previewState.author,
    body:   lp_previewState.body,
    tags:   lp_previewState.tags,
    img:    lp_previewState.img,
    createdAt: Date.now(),
    _isPreview: true
  };

  // Tutup editor, buka modal preview
  document.getElementById('lp-editor-modal').style.display = 'none';
  lp_stopAutoSave();

  // Inject ke array sementara lalu buka read modal
  lp_articles.unshift(fakeArticle);
  lp_openRead('__preview__');
  lp_articles.shift();
}

// Dipanggil saat menutup modal baca artikel — jika dari preview, buka kembali editor
function lp_closeRead() {
  document.getElementById('lp-read-modal').style.display = 'none';
  document.body.style.overflow = '';
  // Bersihkan hash URL saat modal ditutup
  history.replaceState(null, '', window.location.pathname + window.location.search);
  // Reset OG/Twitter meta tags ke default
  lp_resetOgTags();

  // Jika menutup preview, pulihkan editor dengan data tersimpan
  if (lp_previewState) {
    const state = lp_previewState;
    lp_previewState = null;

    // Isi ulang editor dengan data sebelum preview
    lp_editId = state.editId;
    const modeLabel = document.getElementById('lp-editor-mode-label');
    if (modeLabel) modeLabel.textContent = state.editId ? '✏️ Edit Artikel' : '✏️ Tulis Artikel Baru';

    document.getElementById('lp-ed-title').value   = state.title;
    document.getElementById('lp-ed-cat').value     = state.cat;
    document.getElementById('lp-ed-author').value  = state.author;
    document.getElementById('lp-ed-summary').value = state.summary;
    document.getElementById('lp-ed-body').innerHTML = state.body;
    document.getElementById('lp-ed-tags').value    = state.tags;

    if (state.img) {
      document.getElementById('lp-ed-imgurl').value = state.img;
      lp_showImgPreview(state.img);
    } else {
      lp_clearImg();
    }

    lp_updateSummaryCount();
    document.getElementById('lp-editor-msg').style.display = 'none';
    document.getElementById('lp-editor-modal').style.display = '';
    document.body.style.overflow = 'hidden';
    lp_startAutoSave();

    // Tampilkan notif bahwa kembali dari preview
    setTimeout(() => lp_showEditorMsg('👁️ Kembali dari preview — artikel masih tersimpan di draft.', 'success'), 200);
  }
}

// ── PUBLISH ───────────────────────────────────────────────
function lp_publishArticle() {
  // Hak akses: pemilik web ATAU pengguna yang sudah login
  if (!lp_isOwner() && !lp_isLoggedIn()) {
    lp_showEditorMsg('🔒 Masuk atau daftar terlebih dahulu untuk menerbitkan artikel.', 'error');
    lp_closeEditor();
    lp_showAuthBox();
    return;
  }

  // Ambil nama penulis dari user session jika bukan owner
  let defaultAuthor = 'Novrizal, S.I.Kom., S.H., CPM';
  if (!lp_isOwner() && lp_isLoggedIn()) {
    const u = lp_getLoggedInUser();
    if (u) defaultAuthor = u.name;
  }

  const title = document.getElementById('lp-ed-title').value.trim();
  const cat = document.getElementById('lp-ed-cat').value || 'umum';
  const summary = document.getElementById('lp-ed-summary').value.trim();
  const body = document.getElementById('lp-ed-body').innerHTML.trim();

  if (!title) { lp_showEditorMsg('❌ Judul artikel wajib diisi.', 'error'); return; }
  if (!summary) { lp_showEditorMsg('❌ Ringkasan artikel wajib diisi.', 'error'); return; }
  if (!body || body === '<br>') { lp_showEditorMsg('❌ Isi artikel tidak boleh kosong.', 'error'); return; }

  const authorVal = document.getElementById('lp-ed-author').value.trim() || defaultAuthor;

  const article = {
    id: lp_editId || ('lp_' + Date.now() + '_' + Math.random().toString(36).slice(2,7)),
    title, cat,
    author: authorVal,
    summary, body,
    tags: document.getElementById('lp-ed-tags').value.trim(),
    img: lp_getImgSrc(),
    imgCaption: (document.getElementById('lp-ed-imgcaption')?.value || '').trim(),
    createdAt: lp_editId ? (lp_articles.find(x=>x.id===lp_editId)?.createdAt || Date.now()) : Date.now(),
    updatedAt: Date.now()
  };

  // Tampilkan loading di tombol
  const btn = document.querySelector('.lp-btn-publish');
  if (btn) { btn.disabled = true; btn.textContent = '⏳ Menyimpan...'; }

  // Simpan ke localStorage dulu (langsung berhasil) + sync Sheets background
  lp_saveArticleToFirestore(article).then(function() {
    // Selalu render ulang portal setelah simpan
    lp_renderPortal();
    lp_closeEditor();
    if (btn) { btn.disabled = false; btn.textContent = '🚀 Terbitkan Artikel'; }
    // Kirim notifikasi artikel ke Google Apps Script eksternal
    kirimArtikel(article);
    lp_showPortalToast('✅ Artikel berhasil diterbitkan!');
    setTimeout(function() {
      const wrap = document.getElementById('lp-featured-wrap');
      if (wrap) wrap.scrollIntoView({ behavior: 'smooth' });
    }, 300);
    // Tampilkan info jika Sheets dikonfigurasi
    if (lp_sheetsReady) {
      console.log('Artikel tersimpan di localStorage & dikirim ke Google Sheets (background)');
    }
  }).catch(function(e) {
    if (btn) { btn.disabled = false; btn.textContent = '🚀 Terbitkan Artikel'; }
    lp_showEditorMsg('❌ Gagal menyimpan: ' + e.message, 'error');
  });
}

// ── KIRIM ARTIKEL KE GOOGLE SHEETS EKSTERNAL ────────────────
function kirimArtikel(article) {
  if (!LP_KIRIM_URL) return;
  var data = {
    title:   article.title,
    date:    new Date().toLocaleDateString('id-ID'),
    author:  article.author || 'Novrizal',
    content: article.body,
    url:     window.location.href
  };
  fetch(LP_KIRIM_URL, {
    method: 'POST',
    body: JSON.stringify(data)
  }).then(function() {
    console.log('Artikel berhasil dikirim ke form eksternal.');
  }).catch(function(e) {
    console.warn('kirimArtikel gagal (tidak mempengaruhi penyimpanan utama):', e.message);
  });
}

// ── FORM KIRIM ARTIKEL (SIDEBAR EMBED) ──────────────────────
// Fungsi ini mengirim data dari form sidebar ke Google Sheets via LP_KIRIM_URL
function lp_kirimFormArtikel() {
  var judul  = (document.getElementById('lp-kirim-judul')  || {}).value || '';
  var penulis = (document.getElementById('lp-kirim-penulis') || {}).value || '';
  var isi    = (document.getElementById('lp-kirim-isi')    || {}).value || '';
  var btn    = document.getElementById('lp-kirim-btn');
  var msg    = document.getElementById('lp-kirim-msg');
  var label  = document.getElementById('lp-kirim-btn-label');

  // Validasi
  if (!judul.trim()) { lp_kirimShowMsg('❌ Judul artikel wajib diisi.', 'error'); return; }
  if (!isi.trim())   { lp_kirimShowMsg('❌ Isi artikel tidak boleh kosong.', 'error'); return; }
  if (!LP_KIRIM_URL) { lp_kirimShowMsg('⚠️ URL pengiriman belum dikonfigurasi.', 'error'); return; }

  // Loading state
  if (btn)   { btn.disabled = true; }
  if (label) { label.textContent = '⏳ Mengirim...'; }
  if (msg)   { msg.style.display = 'none'; }

  var data = {
    title:   judul.trim(),
    date:    new Date().toLocaleDateString('id-ID'),
    author:  penulis.trim() || 'Anonim',
    content: isi.trim(),
    url:     window.location.href
  };

  fetch(LP_KIRIM_URL, {
    method: 'POST',
    body: JSON.stringify(data)
  }).then(function() {
    lp_kirimShowMsg('✅ Artikel berhasil dikirim ke redaksi!', 'success');
    // Reset form
    var judulEl   = document.getElementById('lp-kirim-judul');
    var penulisEl = document.getElementById('lp-kirim-penulis');
    var isiEl     = document.getElementById('lp-kirim-isi');
    var counter   = document.getElementById('lp-kirim-charcount');
    if (judulEl)   judulEl.value = '';
    if (penulisEl) penulisEl.value = '';
    if (isiEl)     isiEl.value = '';
    if (counter)   counter.textContent = '0 / 5000';
    if (btn)   { btn.disabled = false; }
    if (label) { label.textContent = '📨 Kirim Artikel'; }
  }).catch(function(e) {
    // Coba via no-cors (tidak bisa baca respons, tapi data terkirim)
    fetch(LP_KIRIM_URL, {
      method: 'POST',
      mode: 'no-cors',
      body: JSON.stringify(data)
    }).then(function() {
      lp_kirimShowMsg('✅ Artikel terkirim! (mode no-cors)', 'success');
      var judulEl   = document.getElementById('lp-kirim-judul');
      var penulisEl = document.getElementById('lp-kirim-penulis');
      var isiEl     = document.getElementById('lp-kirim-isi');
      if (judulEl)   judulEl.value = '';
      if (penulisEl) penulisEl.value = '';
      if (isiEl)     isiEl.value = '';
    }).catch(function() {
      lp_kirimShowMsg('❌ Gagal mengirim. Cek koneksi internet Anda.', 'error');
    }).finally(function() {
      if (btn)   { btn.disabled = false; }
      if (label) { label.textContent = '📨 Kirim Artikel'; }
    });
  });
}

function lp_kirimShowMsg(text, type) {
  var msg = document.getElementById('lp-kirim-msg');
  if (!msg) return;
  msg.textContent = text;
  msg.style.display = 'block';
  if (type === 'success') {
    msg.style.background = 'rgba(74,222,128,0.12)';
    msg.style.color = '#166534';
    msg.style.border = '1px solid rgba(74,222,128,0.35)';
  } else {
    msg.style.background = 'rgba(239,68,68,0.1)';
    msg.style.color = '#991b1b';
    msg.style.border = '1px solid rgba(239,68,68,0.25)';
  }
  // Auto-hide pesan sukses setelah 5 detik
  if (type === 'success') {
    setTimeout(function() {
      if (msg) msg.style.display = 'none';
    }, 5000);
  }
}

// Char counter untuk textarea kirim artikel
document.addEventListener('DOMContentLoaded', function() {
  var isiEl   = document.getElementById('lp-kirim-isi');
  var counter = document.getElementById('lp-kirim-charcount');
  if (isiEl && counter) {
    isiEl.addEventListener('input', function() {
      counter.textContent = isiEl.value.length + ' / 5000';
    });
  }
});
// ── /FORM KIRIM ARTIKEL ─────────────────────────────────────

// ── DELETE ────────────────────────────────────────────────
function lp_deleteFromEditor() {
  if (!lp_editId) return;
  const a = lp_articles.find(x => x.id === lp_editId);
  if (!a) return;
  if (!confirm('Hapus artikel "' + a.title + '"?\nTindakan ini tidak dapat dibatalkan.')) return;
  const idToDelete = lp_editId;
  lp_editId = null;
  lp_closeEditor();
  lp_deleteArticleFromFirestore(idToDelete).then(function() {
    // localStorage sudah diupdate di dalam lp_deleteArticleFromFirestore
    lp_renderPortal();
    // Google Sheets: sync sudah dilakukan background
  });
}

function lp_deleteArticle(id) {
  const a = lp_articles.find(x => x.id === id);
  if (!a) return;
  if (!confirm('Hapus artikel "' + a.title + '"? Tindakan ini tidak dapat dibatalkan.')) return;
  lp_deleteArticleFromFirestore(id).then(function() {
    // localStorage sudah diupdate di dalam lp_deleteArticleFromFirestore
    lp_renderPortal();
  });
}

// ── HELPERS ───────────────────────────────────────────────
function lp_esc(str) {
  if (!str) return '';
  return str.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');
}
function lp_formatDate(ts) {
  const d = new Date(ts);
  const months = ['Jan','Feb','Mar','Apr','Mei','Jun','Jul','Ags','Sep','Okt','Nov','Des'];
  return `${d.getDate()} ${months[d.getMonth()]} ${d.getFullYear()}`;
}
function lp_formatDateTime(ts) {
  const d = new Date(ts);
  const months = ['Jan','Feb','Mar','Apr','Mei','Jun','Jul','Ags','Sep','Okt','Nov','Des'];
  const hh = String(d.getHours()).padStart(2,'0');
  const mm = String(d.getMinutes()).padStart(2,'0');
  return `${d.getDate()} ${months[d.getMonth()]} ${d.getFullYear()} · ${hh}.${mm} WIB`;
}
function lp_readTime(html) {
  const text = html ? html.replace(/<[^>]+>/g,'') : '';
  return Math.max(1, Math.ceil(text.split(/\s+/).length / 200));
}
function lp_catIcon(cat) {
  const icons = { hukum:'⚖️', mediasi:'🤝', finansial:'💰', digital:'📱', regulasi:'🏛️', opini:'✍️' };
  return icons[cat] || '📰';
}
function lp_showEditorMsg(msg, type) {
  const el = document.getElementById('lp-editor-msg');
  if (!el) return;
  el.style.display = 'block';
  el.style.background = type === 'error' ? 'rgba(220,53,69,0.15)' : 'rgba(34,197,94,0.15)';
  el.style.color = type === 'error' ? '#f87171' : '#22c55e';
  el.style.border = `1px solid ${type === 'error' ? 'rgba(220,53,69,0.3)' : 'rgba(34,197,94,0.3)'}`;
  el.textContent = msg;
  setTimeout(() => { el.style.display = 'none'; }, 4000);
}

// lp_init dipanggil langsung di dalam showPage di atas

// ════════════════════════════════════════════════════════
// INSIGHT — STATISTIK ARTIKEL (SIDEBAR KONTEN)
// ════════════════════════════════════════════════════════
const LP_STATS_KEY  = 'lp_stats_v1';
const LP_READS_KEY  = 'lp_reads_v1';
const LP_VIEWS_KEY  = 'lp_views_v1';

// Baca stats dari localStorage
function lpStatsGet() {
  try { return JSON.parse(localStorage.getItem(LP_STATS_KEY)) || {}; } catch(e) { return {}; }
}
function lpStatsSave(s) {
  try { localStorage.setItem(LP_STATS_KEY, JSON.stringify(s)); } catch(e) {}
}

// Tambah jumlah pembaca artikel
function lpTrackRead(articleId) {
  const s = lpStatsGet();
  if (!s.reads) s.reads = {};
  s.reads[articleId] = (s.reads[articleId] || 0) + 1;
  s.totalReads = (s.totalReads || 0) + 1;

  // Track daily
  const today = new Date().toISOString().slice(0,10);
  if (!s.daily) s.daily = {};
  s.daily[today] = (s.daily[today] || 0) + 1;

  // Track per-minute read time (estimasi)
  lpStatsSave(s);
}

// Track page view
function lpTrackView() {
  const s = lpStatsGet();
  const today = new Date().toISOString().slice(0,10);
  if (!s.views) s.views = {};
  s.views[today] = (s.views[today] || 0) + 1;
  s.totalViews = (s.totalViews || 0) + 1;
  lpStatsSave(s);
}

// Render insight di sidebar
function lp_renderInsight() {
  const s = lpStatsGet();
  const totalArt = lp_articles.length;
  const totalReads = s.totalReads || 0;
  const today = new Date().toISOString().slice(0,10);
  const todayReads = (s.daily && s.daily[today]) || 0;

  // Hitung rata-rata waktu baca dari artikel yang ada
  const avgMin = totalArt > 0
    ? Math.round(lp_articles.reduce((a,b) => a + lp_readTime(b.body), 0) / totalArt)
    : 0;

  const setEl = (id, v) => { const el = document.getElementById(id); if(el) el.textContent = v; };
  setEl('ins-total-art', totalArt);
  setEl('ins-total-reads', totalReads.toLocaleString('id-ID'));
  setEl('ins-today-reads', todayReads);
  setEl('ins-avg-time', avgMin + 'm');

  // Bar chart per kategori
  const catChart = document.getElementById('lp-cat-chart');
  if (catChart) {
    const cats = Object.entries(LP_CAT_LABELS);
    const maxCount = Math.max(1, ...cats.map(([k]) => lp_articles.filter(a => a.cat === k).length));
    catChart.innerHTML = cats.map(([key, label]) => {
      const count = lp_articles.filter(a => a.cat === key).length;
      const pct = Math.round((count / maxCount) * 100);
      const icon = label.split(' ')[0];
      const name = label.split(' ').slice(1).join(' ');
      return `<div class="lp-cat-bar-row">
        <div class="lp-cat-bar-label">${icon} ${name}</div>
        <div class="lp-cat-bar-track"><div class="lp-cat-bar-fill" style="width:${pct}%"></div></div>
        <div class="lp-cat-bar-count">${count}</div>
      </div>`;
    }).join('');
  }

  // Mini sparkline 7 hari
  const weekCanvas = document.getElementById('lp-week-chart');
  if (weekCanvas) {
    const days7 = [];
    for (let i = 6; i >= 0; i--) {
      const d = new Date(); d.setDate(d.getDate() - i);
      const key = d.toISOString().slice(0,10);
      days7.push({ label: d.toLocaleDateString('id-ID',{weekday:'short'}), val: (s.daily && s.daily[key]) || 0 });
    }
    drawMiniChart(weekCanvas, days7.map(d=>d.val), days7.map(d=>d.label), '#b8973a');
  }
}

// ── CANVAS MINI CHART ─────────────────────────────────────
function drawMiniChart(canvas, data, labels, color) {
  const ctx = canvas.getContext('2d');
  const W = canvas.offsetWidth || 260;
  const H = 80;
  canvas.width = W;
  canvas.height = H;
  ctx.clearRect(0, 0, W, H);

  const maxV = Math.max(1, ...data);
  const padL = 8, padR = 8, padT = 8, padB = 20;
  const chartW = W - padL - padR;
  const chartH = H - padT - padB;
  const step = chartW / Math.max(1, data.length - 1);

  // Grid lines
  ctx.strokeStyle = 'rgba(92,87,73,0.15)';
  ctx.lineWidth = 1;
  [0.25, 0.5, 0.75, 1].forEach(f => {
    const y = padT + chartH * (1 - f);
    ctx.beginPath(); ctx.moveTo(padL, y); ctx.lineTo(W - padR, y); ctx.stroke();
  });

  // Area fill
  ctx.beginPath();
  data.forEach((v, i) => {
    const x = padL + i * step;
    const y = padT + chartH * (1 - v / maxV);
    i === 0 ? ctx.moveTo(x, y) : ctx.lineTo(x, y);
  });
  ctx.lineTo(padL + (data.length - 1) * step, padT + chartH);
  ctx.lineTo(padL, padT + chartH);
  ctx.closePath();
  const grad = ctx.createLinearGradient(0, padT, 0, padT + chartH);
  grad.addColorStop(0, color + '55');
  grad.addColorStop(1, color + '05');
  ctx.fillStyle = grad;
  ctx.fill();

  // Line
  ctx.beginPath();
  ctx.strokeStyle = color;
  ctx.lineWidth = 2;
  ctx.lineJoin = 'round';
  data.forEach((v, i) => {
    const x = padL + i * step;
    const y = padT + chartH * (1 - v / maxV);
    i === 0 ? ctx.moveTo(x, y) : ctx.lineTo(x, y);
  });
  ctx.stroke();

  // Dots & labels
  ctx.fillStyle = color;
  data.forEach((v, i) => {
    const x = padL + i * step;
    const y = padT + chartH * (1 - v / maxV);
    ctx.beginPath(); ctx.arc(x, y, 3, 0, Math.PI * 2); ctx.fill();
    // Day label
    ctx.fillStyle = 'rgba(92,87,73,0.6)';
    ctx.font = '9px DM Mono, monospace';
    ctx.textAlign = 'center';
    ctx.fillText(labels[i] || '', x, H - 4);
    ctx.fillStyle = color;
  });
}

// ════════════════════════════════════════════════════════
// SISTEM AUTH PENGGUNA (Daftar / Login)
// Menyimpan akun di localStorage sebagai storage sisi klien
// Untuk integrasi nyata, data bisa disinkronkan via Apps Script
// ════════════════════════════════════════════════════════
const LP_USERS_KEY = 'lp_users_v1';
const LP_SESSION_USER_KEY = 'lp_user_session';

// Ambil semua user terdaftar
function lp_getUsers() {
  try { return JSON.parse(localStorage.getItem(LP_USERS_KEY)) || {}; } catch(e) { return {}; }
}
function lp_saveUsers(u) {
  try { localStorage.setItem(LP_USERS_KEY, JSON.stringify(u)); } catch(e) {}
}

// Cek apakah ada user yang sedang login
function lp_isLoggedIn() {
  try { return !!sessionStorage.getItem(LP_SESSION_USER_KEY); } catch(e) { return false; }
}
function lp_getLoggedInUser() {
  try { return JSON.parse(sessionStorage.getItem(LP_SESSION_USER_KEY)); } catch(e) { return null; }
}

// Hash sederhana untuk password (tidak untuk produksi)
function lp_hashPw(pw) {
  let h = 0;
  for (let i = 0; i < pw.length; i++) { h = ((h << 5) - h) + pw.charCodeAt(i); h |= 0; }
  return 'lp_' + Math.abs(h).toString(36);
}

// Tampilkan / sembunyikan auth box
function lp_showAuthBox() {
  const box = document.getElementById('lp-auth-box');
  if (box) {
    box.style.display = box.style.display === 'none' || box.style.display === '' ? 'block' : 'none';
    if (box.style.display === 'block') box.scrollIntoView({ behavior:'smooth', block:'nearest' });
  }
}
function lp_hideAuthBox() {
  const box = document.getElementById('lp-auth-box');
  if (box) box.style.display = 'none';
}

function lp_switchAuthTab(tab) {
  const loginForm = document.getElementById('lp-auth-login-form');
  const regForm = document.getElementById('lp-auth-register-form');
  const loginTab = document.getElementById('lp-auth-tab-login');
  const regTab = document.getElementById('lp-auth-tab-register');
  if (tab === 'login') {
    loginForm.style.display = '';
    regForm.style.display = 'none';
    loginTab.style.background = 'var(--ink)'; loginTab.style.color = 'var(--gold-pale)';
    regTab.style.background = 'var(--cream-2)'; regTab.style.color = 'var(--ink-3)';
  } else {
    loginForm.style.display = 'none';
    regForm.style.display = '';
    regTab.style.background = 'var(--ink)'; regTab.style.color = 'var(--gold-pale)';
    loginTab.style.background = 'var(--cream-2)'; loginTab.style.color = 'var(--ink-3)';
  }
}

function lp_doLogin() {
  const email = (document.getElementById('lp-login-email').value || '').trim().toLowerCase();
  const pw = (document.getElementById('lp-login-pw').value || '');
  const errEl = document.getElementById('lp-login-err');
  if (!email || !pw) { lp_showAuthErr(errEl, '⚠️ Email dan password wajib diisi.'); return; }
  const users = lp_getUsers();
  const user = users[email];
  if (!user) { lp_showAuthErr(errEl, '❌ Email tidak terdaftar. Silakan daftar terlebih dahulu.'); return; }
  if (user.pw !== lp_hashPw(pw)) { lp_showAuthErr(errEl, '❌ Password salah. Coba lagi.'); return; }
  // Berhasil login
  try { sessionStorage.setItem(LP_SESSION_USER_KEY, JSON.stringify({ email, name: user.name })); } catch(e) {}
  lp_hideAuthBox();
  lp_updateUserBar();
  lp_renderPortalWithOwnerCheck();
  lp_showPortalToast(`👋 Selamat datang, ${user.name}!`);
}

function lp_doRegister() {
  const name = (document.getElementById('lp-reg-name').value || '').trim();
  const email = (document.getElementById('lp-reg-email').value || '').trim().toLowerCase();
  const pw = (document.getElementById('lp-reg-pw').value || '');
  const pw2 = (document.getElementById('lp-reg-pw2').value || '');
  const errEl = document.getElementById('lp-reg-err');
  if (!name || !email || !pw || !pw2) { lp_showAuthErr(errEl, '⚠️ Semua field wajib diisi.'); return; }
  if (!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)) { lp_showAuthErr(errEl, '❌ Format email tidak valid.'); return; }
  if (pw.length < 6) { lp_showAuthErr(errEl, '❌ Password minimal 6 karakter.'); return; }
  if (pw !== pw2) { lp_showAuthErr(errEl, '❌ Konfirmasi password tidak cocok.'); return; }
  const users = lp_getUsers();
  if (users[email]) { lp_showAuthErr(errEl, '❌ Email sudah terdaftar. Silakan masuk.'); return; }
  // Simpan user baru
  users[email] = { name, email, pw: lp_hashPw(pw), createdAt: Date.now() };
  lp_saveUsers(users);
  // Kirim ke Google Sheets jika tersedia (via Apps Script)
  if (lp_sheetsReady) {
    lp_gasJsonpAction({ action: 'registerUser', user: { name, email, createdAt: Date.now() } });
  }
  // Auto login
  try { sessionStorage.setItem(LP_SESSION_USER_KEY, JSON.stringify({ email, name })); } catch(e) {}
  lp_hideAuthBox();
  lp_updateUserBar();
  lp_renderPortalWithOwnerCheck();
  lp_showPortalToast(`🎉 Akun berhasil dibuat! Selamat datang, ${name}!`);
}

function lp_logout() {
  try { sessionStorage.removeItem(LP_SESSION_USER_KEY); } catch(e) {}
  lp_updateUserBar();
  lp_renderPortalWithOwnerCheck();
  lp_showPortalToast('👋 Anda telah keluar.');
}

function lp_showAuthErr(el, msg) {
  if (!el) return;
  el.textContent = msg;
  el.style.display = 'block';
  el.style.color = msg.startsWith('🎉') ? '#22c55e' : '#ef4444';
  setTimeout(() => { if (el) el.style.display = 'none'; }, 4000);
}

function lp_updateUserBar() {
  const statusBar = document.getElementById('lp-user-status-bar');
  const authBtnWrap = document.getElementById('lp-auth-btn-wrap');
  const greeting = document.getElementById('lp-user-greeting');
  const user = lp_getLoggedInUser();
  if (user) {
    if (statusBar) { statusBar.style.display = 'flex'; }
    if (authBtnWrap) authBtnWrap.style.display = 'none';
    if (greeting) greeting.textContent = `👤 ${user.name}`;
  } else {
    if (statusBar) statusBar.style.display = 'none';
    if (authBtnWrap) authBtnWrap.style.display = '';
  }
}

function lp_showPortalToast(msg) {
  const old = document.getElementById('lp-portal-toast');
  if (old) old.remove();
  const toast = document.createElement('div');
  toast.id = 'lp-portal-toast';
  toast.textContent = msg;
  toast.style.cssText = `
    position:fixed; bottom:2rem; left:50%; transform:translateX(-50%);
    background:var(--ink); color:var(--gold-pale);
    font-family:'DM Mono',monospace; font-size:0.72rem; letter-spacing:0.06em;
    padding:0.75rem 1.5rem; border-radius:8px;
    box-shadow:0 8px 32px rgba(15,14,11,0.35);
    border:1px solid rgba(184,151,58,0.3);
    z-index:9999; opacity:1; transition:opacity 0.4s;
    white-space:nowrap; max-width:90vw;
  `;
  document.body.appendChild(toast);
  setTimeout(() => { toast.style.opacity = '0'; setTimeout(() => toast.remove(), 400); }, 2800);
}

// ── /SISTEM AUTH ──────────────────────────────────────────

// ════════════════════════════════════════════════════════
// DASHBOARD OWNER — AKSES TERSEMBUNYI
// ════════════════════════════════════════════════════════
const DASH_PW_HASH = 'lp2024novrizal'; // Kata sandi dashboard owner
const DASH_SESSION_KEY = 'lp_dash_session';

// ── OWNER SESSION CHECK ───────────────────────────────────
// Cek apakah sesi pemilik web aktif (login via dashboard)
function lp_isOwner() {
  try { return sessionStorage.getItem(DASH_SESSION_KEY) === '1'; } catch(e) { return false; }
}

function dashLogin() {
  const pw = document.getElementById('dash-pw-input').value;
  const err = document.getElementById('dash-pw-err');
  if (pw === DASH_PW_HASH) {
    try { sessionStorage.setItem(DASH_SESSION_KEY, '1'); } catch(e) {}
    err.style.display = 'none';
    document.getElementById('dash-login-gate').style.display = 'none';
    document.getElementById('dash-content').style.display = 'block';
    // Tampilkan menu dashboard di nav
    const navLi = document.getElementById('nav-dashboard-li');
    if (navLi) navLi.style.display = '';
    // Refresh portal konten agar tombol tulis & edit muncul
    lp_initialized = false;
    lp_renderPortalWithOwnerCheck();
    dashRender();
    lpTrackView();
  } else {
    err.style.display = 'block';
    document.getElementById('dash-pw-input').value = '';
    document.getElementById('dash-pw-input').focus();
    document.getElementById('dash-pw-input').style.borderColor = '#f87171';
    setTimeout(() => { document.getElementById('dash-pw-input').style.borderColor = ''; }, 2000);
  }
}

function dashLogout() {
  try { sessionStorage.removeItem(DASH_SESSION_KEY); } catch(e) {}
  document.getElementById('dash-login-gate').style.display = 'flex';
  document.getElementById('dash-content').style.display = 'none';
  document.getElementById('nav-dashboard-li').style.display = 'none';
  document.getElementById('dash-pw-input').value = '';
  // Refresh portal konten agar tombol tulis & edit disembunyikan
  lp_initialized = false;
  lp_renderPortalWithOwnerCheck();
}

function lp_updateFirebaseBanner() {
  var dot = document.getElementById('dash-fb-dot');
  var title = document.getElementById('dash-fb-status-title');
  var desc = document.getElementById('dash-fb-status-desc');
  var guide = document.getElementById('dash-fb-setup-guide');
  var label = document.getElementById('dash-fb-status-label');
  if (!dot) return;

  if (!lp_sheetsReady) {
    // Belum dikonfigurasi
    dot.style.background = '#f59e0b';
    dot.style.animation = 'pulse 2s ease-in-out infinite';
    if (title) title.textContent = 'Tersimpan di Browser ✔ (Sheets Opsional)';
    if (desc) desc.textContent = 'Artikel sudah tersimpan permanen di browser ini dan tidak hilang saat refresh. Hubungkan Google Sheets untuk backup cloud multi-perangkat.';
    if (guide) guide.style.display = '';
    if (label) label.textContent = '📊 Database: Browser (localStorage)';
  } else {
    // Cek koneksi ke Google Sheets via JSONP (sama seperti sistem load utama)
    // Set status menunggu dulu
    dot.style.background = '#f59e0b';
    dot.style.animation = 'pulse 1.5s ease-in-out infinite';
    if (title) title.textContent = 'Menghubungkan ke Google Sheets...';
    if (label) label.textContent = '📊 Database: Menghubungkan...';

    var cbName = 'lp_dashCheckCallback_' + Date.now();
    var checkScript = document.createElement('script');
    var timeoutCheck = setTimeout(function() {
      var s = document.getElementById('lp-dash-check-script');
      if (s && s.parentNode) s.parentNode.removeChild(s);
      if (window[cbName]) delete window[cbName];
      dot.style.background = '#f59e0b';
      dot.style.animation = 'pulse 1.5s ease-in-out infinite';
      if (title) title.textContent = 'Menghubungkan ke Google Sheets...';
      if (desc) desc.textContent = 'Sedang menyambung ke Google Sheets. Pastikan URL deployment sudah benar.';
      if (guide) guide.style.display = '';
      if (label) label.textContent = '📊 Database: Menghubungkan...';
    }, 8000);

    window[cbName] = function() {
      clearTimeout(timeoutCheck);
      var s = document.getElementById('lp-dash-check-script');
      if (s && s.parentNode) s.parentNode.removeChild(s);
      delete window[cbName];
      dot.style.background = '#22c55e';
      dot.style.animation = 'pulse 2s ease-in-out infinite';
      if (title) title.textContent = 'Tersimpan: Browser + Google Sheets ✔';
      if (desc) desc.textContent = 'Artikel tersimpan langsung di browser (tidak hilang saat refresh) dan disinkron ke Google Sheets sebagai backup cloud.';
      if (guide) guide.style.display = 'none';
      if (label) label.textContent = '📊 Database: localStorage + Sheets ✔';
    };

    checkScript.id = 'lp-dash-check-script';
    checkScript.src = LP_SHEETS_URL + '?action=getAll&callback=' + cbName + '&t=' + Date.now();
    checkScript.onerror = function() {
      clearTimeout(timeoutCheck);
      var s = document.getElementById('lp-dash-check-script');
      if (s && s.parentNode) s.parentNode.removeChild(s);
      if (window[cbName]) delete window[cbName];
      dot.style.background = '#f59e0b';
      if (title) title.textContent = 'Menghubungkan ke Google Sheets...';
      if (desc) desc.textContent = 'Sedang menyambung ke Google Sheets. Pastikan URL deployment sudah benar.';
      if (guide) guide.style.display = '';
      if (label) label.textContent = '📊 Database: Menghubungkan...';
    };
    document.head.appendChild(checkScript);
  }
}

function dashCheckSession() {
  try {
    if (sessionStorage.getItem(DASH_SESSION_KEY) === '1') {
      document.getElementById('dash-login-gate').style.display = 'none';
      document.getElementById('dash-content').style.display = 'block';
      const navLi = document.getElementById('nav-dashboard-li');
      if (navLi) navLi.style.display = '';
      dashRender();
    }
  } catch(e) {}
}

function dashRender() {
  const s = lpStatsGet();
  const now = new Date();
  const months = ['Jan','Feb','Mar','Apr','Mei','Jun','Jul','Ags','Sep','Okt','Nov','Des'];
  const days = ['Minggu','Senin','Selasa','Rabu','Kamis','Jumat','Sabtu'];

  // Header date
  const dateEl = document.getElementById('dash-report-date');
  if (dateEl) dateEl.textContent = `Laporan per ${days[now.getDay()]}, ${now.getDate()} ${months[now.getMonth()]} ${now.getFullYear()}`;
  const lastUpEl = document.getElementById('dash-last-update');
  if (lastUpEl) lastUpEl.textContent = `Update: ${String(now.getHours()).padStart(2,'0')}.${String(now.getMinutes()).padStart(2,'0')} WIB`;

  // KPI
  const totalViews = s.totalViews || 0;
  const totalReads = s.totalReads || 0;
  const totalArt   = lp_articles.length;
  const today = now.toISOString().slice(0,10);
  const todayViews = (s.views && s.views[today]) || 0;

  // Estimasi share (tidak ada tracking nyata, pakai dummy berbasis views)
  const estShares = Math.floor(totalViews * 0.07);
  const estConsult = Math.floor(totalViews * 0.04);

  const avgMin = totalArt > 0
    ? Math.round(lp_articles.reduce((a,b) => a + lp_readTime(b.body), 0) / totalArt)
    : 0;

  const setEl = (id,v) => { const el=document.getElementById(id); if(el) el.textContent=v; };
  setEl('d-total-views', totalViews.toLocaleString('id-ID'));
  setEl('d-total-art', totalArt);
  setEl('d-total-reads', totalReads.toLocaleString('id-ID'));
  setEl('d-avg-time', avgMin + ' menit');
  setEl('d-share-count', estShares.toLocaleString('id-ID'));
  setEl('d-consult-count', estConsult.toLocaleString('id-ID'));

  const todayPct = todayViews > 0 ? '+' + todayViews + ' hari ini' : 'Belum ada hari ini';
  setEl('d-views-trend', todayPct);
  if (totalArt > 0) {
    const last = lp_articles.reduce((a,b) => b.createdAt > a.createdAt ? b : a);
    setEl('d-art-trend', lp_formatDate(last.createdAt));
  }
  setEl('d-reads-trend', totalReads > 0 ? 'Total sesi baca tercatat' : 'Belum ada data');

  // Potensi iklan
  const monthlyEst = Math.max(totalViews * 4, 100); // estimasi bulanan 4x sesi aktual
  const bannerRev  = Math.floor(monthlyEst / 1000 * 15000); // CPM Rp 15.000
  const sponsoredRev = totalArt > 0 ? 500000 : 0;
  const inreadRev  = Math.floor(totalReads * 200);
  const total = bannerRev + sponsoredRev + inreadRev;
  const fmtRp = n => 'Rp ' + n.toLocaleString('id-ID');
  setEl('dap-monthly', monthlyEst.toLocaleString('id-ID') + ' est.');
  setEl('dap-banner', fmtRp(bannerRev));
  setEl('dap-sponsored', fmtRp(sponsoredRev));
  setEl('dap-inread', fmtRp(inreadRev));
  setEl('dap-total', fmtRp(total) + '/bln');

  // Top articles table
  dashRenderTopArticles(s);
  dashRenderTable(s);

  // Render charts
  setTimeout(() => {
    dashDrawTrafficChart(s);
    dashDrawCatPie();
  }, 100);
}

function dashRenderTopArticles(s) {
  const container = document.getElementById('d-top-articles');
  if (!container) return;
  const reads = (s && s.reads) || {};
  const sorted = [...lp_articles]
    .map(a => ({ ...a, readCount: reads[a.id] || Math.floor(Math.random() * 50 + 5) }))
    .sort((a,b) => b.readCount - a.readCount)
    .slice(0, 5);

  if (sorted.length === 0) {
    container.innerHTML = '<div style="color:var(--ink-3); font-size:0.88rem; font-style:italic; text-align:center; padding:1rem;">Belum ada artikel.</div>';
    return;
  }
  const medals = ['🥇','🥈','🥉','4️⃣','5️⃣'];
  container.innerHTML = sorted.map((a, i) => `
    <div class="d-top-item">
      <div class="d-top-rank">${medals[i]}</div>
      <div class="d-top-info">
        <div class="d-top-title">${lp_esc(a.title)}</div>
        <div class="d-top-meta">${LP_CAT_LABELS[a.cat]||a.cat} · ${lp_formatDateTime(a.createdAt)}</div>
      </div>
      <div class="d-top-reads">${a.readCount} baca</div>
    </div>`).join('');
}

function dashRenderTable(s) {
  const tbody = document.getElementById('d-article-tbody');
  if (!tbody) return;
  const reads = (s && s.reads) || {};
  const sorted = [...lp_articles].sort((a,b) => b.createdAt - a.createdAt);
  if (sorted.length === 0) {
    tbody.innerHTML = '<tr><td colspan="7" style="text-align:center; color:var(--ink-3); font-style:italic; padding:1.5rem;">Belum ada artikel yang diterbitkan.</td></tr>';
    return;
  }
  tbody.innerHTML = sorted.map((a, i) => {
    const readCount = reads[a.id] || 0;
    return `<tr>
      <td style="font-family:'DM Mono',monospace; font-size:0.65rem; color:var(--ink-3);">${i+1}</td>
      <td><strong>${lp_esc(a.title.length > 50 ? a.title.slice(0,50)+'…' : a.title)}</strong></td>
      <td><span class="d-table-cat">${LP_CAT_LABELS[a.cat]||a.cat}</span></td>
      <td style="font-size:0.85rem; color:var(--ink-3);">${lp_esc(a.author||'Novrizal, S.I.Kom., S.H., CPM')}</td>
      <td style="font-family:'DM Mono',monospace; font-size:0.65rem; color:var(--ink-3); white-space:nowrap;">${lp_formatDateTime(a.createdAt)}</td>
      <td class="d-table-reads">${readCount}</td>
      <td style="font-family:'DM Mono',monospace; font-size:0.65rem; color:var(--ink-3);">${lp_readTime(a.body)}m</td>
    </tr>`;
  }).join('');
}

function dashDrawTrafficChart(s) {
  const canvas = document.getElementById('d-traffic-chart');
  if (!canvas) return;
  const days30 = [];
  const months = ['Jan','Feb','Mar','Apr','Mei','Jun','Jul','Ags','Sep','Okt','Nov','Des'];
  for (let i = 29; i >= 0; i--) {
    const d = new Date(); d.setDate(d.getDate() - i);
    const key = d.toISOString().slice(0,10);
    const views = (s.views && s.views[key]) || 0;
    const reads = (s.daily && s.daily[key]) || 0;
    days30.push({
      label: (i % 5 === 0) ? `${d.getDate()}/${d.getMonth()+1}` : '',
      views, reads
    });
  }

  const W = canvas.parentElement.offsetWidth - 48;
  const H = 180;
  canvas.width = W > 0 ? W : 600;
  canvas.height = H;
  const ctx = canvas.getContext('2d');
  ctx.clearRect(0,0,canvas.width, H);

  const padL=40, padR=16, padT=12, padB=30;
  const cW = canvas.width - padL - padR;
  const cH = H - padT - padB;
  const maxV = Math.max(1, ...days30.map(d=>d.views), ...days30.map(d=>d.reads));
  const stepX = cW / (days30.length - 1);

  // Grid
  ctx.strokeStyle = 'rgba(92,87,73,0.12)';
  ctx.lineWidth = 1;
  [0.25,0.5,0.75,1].forEach(f => {
    const y = padT + cH*(1-f);
    ctx.beginPath(); ctx.moveTo(padL, y); ctx.lineTo(canvas.width-padR, y); ctx.stroke();
    const val = Math.round(maxV*f);
    ctx.fillStyle = 'rgba(92,87,73,0.5)';
    ctx.font = '9px DM Mono, monospace';
    ctx.textAlign = 'right';
    ctx.fillText(val, padL-4, y+3);
  });

  // Draw line helper
  function drawLine(data, color, dotR) {
    ctx.beginPath();
    ctx.strokeStyle = color;
    ctx.lineWidth = 2;
    ctx.lineJoin = 'round';
    data.forEach((v,i) => {
      const x = padL + i * stepX;
      const y = padT + cH * (1 - v/maxV);
      i===0 ? ctx.moveTo(x,y) : ctx.lineTo(x,y);
    });
    ctx.stroke();
    // Dots only for notable
    ctx.fillStyle = color;
    data.forEach((v,i) => {
      if (v > 0) {
        const x = padL + i * stepX;
        const y = padT + cH * (1 - v/maxV);
        ctx.beginPath(); ctx.arc(x,y,dotR,0,Math.PI*2); ctx.fill();
      }
    });
  }

  // Area for views
  ctx.beginPath();
  days30.forEach((d,i) => {
    const x = padL + i*stepX;
    const y = padT + cH*(1 - d.views/maxV);
    i===0 ? ctx.moveTo(x,y) : ctx.lineTo(x,y);
  });
  ctx.lineTo(padL+(days30.length-1)*stepX, padT+cH);
  ctx.lineTo(padL, padT+cH);
  ctx.closePath();
  const grad = ctx.createLinearGradient(0,padT,0,padT+cH);
  grad.addColorStop(0,'rgba(184,151,58,0.25)'); grad.addColorStop(1,'rgba(184,151,58,0.02)');
  ctx.fillStyle = grad; ctx.fill();

  drawLine(days30.map(d=>d.views), '#b8973a', 3);
  drawLine(days30.map(d=>d.reads), '#22c55e', 2.5);

  // X labels
  ctx.fillStyle = 'rgba(92,87,73,0.55)'; ctx.font = '9px DM Mono,monospace'; ctx.textAlign='center';
  days30.forEach((d,i) => {
    if (d.label) ctx.fillText(d.label, padL+i*stepX, H-6);
  });

  // Legend
  [[' Pengunjung','#b8973a'],[' Pembaca','#22c55e']].forEach(([label,color],i) => {
    ctx.fillStyle = color;
    ctx.fillRect(padL + i*100, 0, 10, 8);
    ctx.fillStyle='rgba(92,87,73,0.7)';
    ctx.textAlign='left';
    ctx.font='10px Crimson Pro,serif';
    ctx.fillText(label, padL+10+i*100, 8);
  });
}

function dashDrawCatPie() {
  const canvas = document.getElementById('d-cat-pie');
  if (!canvas) return;
  const W = canvas.parentElement.offsetWidth - 48;
  const H = 180;
  canvas.width = W > 0 ? W : 260;
  canvas.height = H;
  const ctx = canvas.getContext('2d');
  ctx.clearRect(0,0,canvas.width,H);

  const cats = Object.entries(LP_CAT_LABELS);
  const counts = cats.map(([k]) => lp_articles.filter(a=>a.cat===k).length);
  const total = counts.reduce((a,b)=>a+b,0);
  if (total === 0) {
    ctx.fillStyle='rgba(92,87,73,0.4)'; ctx.font='14px Crimson Pro,serif';
    ctx.textAlign='center'; ctx.fillText('Belum ada artikel', canvas.width/2, H/2);
    return;
  }

  const colors = ['#b8973a','#d4b05a','#e0d6c2','#5c5749','#2a2720','#22c55e'];
  const cx = Math.min(canvas.width/2, 90), cy = H/2, r = 65;
  let angle = -Math.PI/2;

  counts.forEach((count, i) => {
    if (count === 0) return;
    const slice = (count/total) * Math.PI * 2;
    ctx.beginPath();
    ctx.moveTo(cx,cy);
    ctx.arc(cx,cy,r,angle,angle+slice);
    ctx.closePath();
    ctx.fillStyle = colors[i % colors.length];
    ctx.fill();
    ctx.strokeStyle='rgba(245,240,232,0.8)'; ctx.lineWidth=2; ctx.stroke();
    angle += slice;
  });

  // Legend
  const legX = cx*2 + 12;
  cats.forEach(([k,label], i) => {
    const count = counts[i];
    if (count === 0) return;
    const y = 20 + i * 26;
    ctx.fillStyle = colors[i % colors.length];
    ctx.fillRect(legX, y-8, 10, 10);
    ctx.fillStyle = 'rgba(15,14,11,0.7)';
    ctx.font = '11px Crimson Pro,serif';
    ctx.textAlign = 'left';
    ctx.fillText(label + ' (' + count + ')', legX+14, y+1);
  });
}

function dashExportPDF() {
  window.print();
}

// (showPage diperluas langsung di fungsi utama — tidak ada override di sini)

// Auto-track halaman awal + baca URL hash untuk deep-link artikel
window.addEventListener('load', () => {
  lpTrackView();

  // Cek apakah ada hash #artikel=ID di URL (format link share)
  const hash = window.location.hash;

  if (hash && hash.startsWith('#artikel=')) {
    const articleId = decodeURIComponent(hash.slice('#artikel='.length));
    showPage('konten');
    setTimeout(() => {
      lp_init();
      // Tunggu sampai Sheets selesai load, lalu buka artikel
      // Batas: 60 percobaan x 300ms = 18 detik (cukup untuk Sheets response)
      let attempts = 0;
      const maxAttempts = 60;
      const tryOpen = setInterval(() => {
        attempts++;
        const art = lp_articles.find(a => a.id === articleId);
        if (art) {
          clearInterval(tryOpen);
          lp_openRead(articleId);
          // OG tags sudah diupdate di dalam lp_openRead
        } else if (attempts >= maxAttempts) {
          clearInterval(tryOpen);
          // Artikel tidak ditemukan — tampilkan pesan ke user
          const featuredWrap = document.getElementById('lp-featured-wrap');
          if (featuredWrap) {
            featuredWrap.innerHTML = '<div style="text-align:center;padding:3rem;color:var(--ink-3);font-family:DM Mono,monospace;font-size:0.8rem;letter-spacing:0.08em;">⚠️ Artikel tidak ditemukan. Mungkin sudah dihapus atau link tidak valid.<br><br><button onclick="lp_renderPortal()" style="margin-top:1rem;background:var(--ink);color:var(--gold-pale);border:none;border-radius:5px;padding:0.65rem 1.25rem;font-family:DM Mono,monospace;font-size:0.7rem;cursor:pointer;">← Lihat Semua Artikel</button></div>';
          }
          console.warn('Artikel tidak ditemukan setelah ' + maxAttempts + ' percobaan:', articleId);
        }
      }, 300);
    }, 100);
  }
});

// ── SCROLL ANIMATIONS ────────────────────────────────────
const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) entry.target.classList.add('visible');
  });
}, { threshold: 0.1, rootMargin: '0px 0px -40px 0px' });

document.querySelectorAll('.fade-up').forEach((el, i) => {
  el.style.transitionDelay = (i % 4) * 0.08 + 's';
  observer.observe(el);
});

// ── HAMBURGER ────────────────────────────────────────────
function closeMenu() {
  const menu = document.querySelector('.nav-menu');
  const btn = document.getElementById('hamburger-btn');
  if (menu) menu.classList.remove('open');
  if (btn) btn.classList.remove('open');
}

document.addEventListener('click', function(e) {
  const nav = document.querySelector('nav');
  const menu = nav?.querySelector('.nav-menu');
  if (menu?.classList.contains('open') && !nav.contains(e.target)) {
    closeMenu();
  }
});
</script>
</body>
</html>
