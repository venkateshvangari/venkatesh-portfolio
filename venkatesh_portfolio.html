<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Venkatesh Vangari — Senior DevOps & Cloud Platform Engineer</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,400&display=swap" rel="stylesheet"/>
<style>
/* ===================== RESET & BASE ===================== */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

:root {
  --indigo: #3d2fa9;
  --indigo-light: #5b4fcf;
  --pink: #f0137a;
  --cyan: #00e5ff;
  --amber: #ffb300;
  --bg: #06060f;
  --bg2: #0b0b1a;
  --bg3: #10102a;
  --surface: rgba(255,255,255,0.035);
  --border: rgba(255,255,255,0.07);
  --text: #e8e8f8;
  --muted: #8080aa;
  --font-head: 'Syne', sans-serif;
  --font-body: 'DM Sans', sans-serif;
}

html { scroll-behavior: smooth; }

body {
  background: var(--bg);
  color: var(--text);
  font-family: var(--font-body);
  font-size: 16px;
  line-height: 1.7;
  overflow-x: hidden;
  cursor: none;
}

/* ===================== NOISE OVERLAY ===================== */
body::before {
  content: '';
  position: fixed;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='1'/%3E%3C/svg%3E");
  opacity: 0.03;
  pointer-events: none;
  z-index: 9999;
}

/* ===================== SCROLLBAR ===================== */
::-webkit-scrollbar { width: 5px; }
::-webkit-scrollbar-track { background: var(--bg); }
::-webkit-scrollbar-thumb { background: linear-gradient(var(--indigo-light), var(--pink)); border-radius: 10px; }

/* ===================== CUSTOM CURSOR ===================== */
#cursor-dot {
  width: 8px; height: 8px;
  background: var(--cyan);
  border-radius: 50%;
  position: fixed; top: 0; left: 0;
  pointer-events: none;
  z-index: 99999;
  transform: translate(-50%, -50%);
  transition: transform 0.08s, background 0.3s;
  box-shadow: 0 0 8px var(--cyan), 0 0 16px var(--cyan);
}
#cursor-ring {
  width: 32px; height: 32px;
  border: 1.5px solid rgba(0,229,255,0.5);
  border-radius: 50%;
  position: fixed; top: 0; left: 0;
  pointer-events: none;
  z-index: 99998;
  transform: translate(-50%, -50%);
  transition: transform 0.18s cubic-bezier(0.23,1,0.32,1), width 0.3s, height 0.3s, border-color 0.3s;
}

/* ===================== LOADER ===================== */
#loader {
  position: fixed; inset: 0;
  background: var(--bg);
  display: flex; flex-direction: column;
  align-items: center; justify-content: center;
  z-index: 99997;
  transition: opacity 0.6s ease, visibility 0.6s ease;
}
#loader.hidden { opacity: 0; visibility: hidden; pointer-events: none; }
.loader-initials {
  font-family: var(--font-head);
  font-size: clamp(4rem, 12vw, 9rem);
  font-weight: 800;
  letter-spacing: -0.02em;
  background: linear-gradient(135deg, var(--indigo-light), var(--pink), var(--cyan));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-size: 300% 300%;
  animation: gradShift 2s ease infinite;
}
.loader-bar-wrap {
  margin-top: 2.5rem;
  width: clamp(200px, 40vw, 360px);
  height: 3px;
  background: rgba(255,255,255,0.07);
  border-radius: 10px;
  overflow: hidden;
}
.loader-bar {
  height: 100%;
  width: 0%;
  background: linear-gradient(90deg, var(--indigo-light), var(--pink), var(--cyan), var(--amber));
  background-size: 300% 100%;
  animation: loadProgress 1.9s cubic-bezier(0.4,0,0.2,1) forwards, gradShift 2s ease infinite;
  border-radius: 10px;
}
@keyframes loadProgress { from { width: 0%; } to { width: 100%; } }
@keyframes gradShift {
  0%,100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}

/* ===================== PARTICLE CANVAS ===================== */
#particle-canvas {
  position: fixed; inset: 0;
  z-index: 0;
  pointer-events: none;
}

/* ===================== NAVBAR ===================== */
nav {
  position: fixed; top: 0; left: 0; right: 0;
  z-index: 1000;
  padding: 1.1rem 4vw;
  display: flex; align-items: center; justify-content: space-between;
  backdrop-filter: blur(18px) saturate(1.4);
  background: rgba(6,6,15,0.55);
  border-bottom: 1px solid var(--border);
  transform: translateY(-100%);
  animation: slideDown 0.8s 2.2s cubic-bezier(0.23,1,0.32,1) forwards;
}
@keyframes slideDown { to { transform: translateY(0); } }
.nav-logo {
  font-family: var(--font-head);
  font-size: 1.15rem;
  font-weight: 700;
  letter-spacing: 0.03em;
  color: #fff;
  text-decoration: none;
}
.nav-logo span { color: var(--cyan); }
.nav-links { display: flex; gap: 2.2rem; list-style: none; }
.nav-links a {
  font-size: 0.82rem;
  font-weight: 500;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--muted);
  text-decoration: none;
  position: relative;
  transition: color 0.3s;
}
.nav-links a::after {
  content: '';
  position: absolute; bottom: -3px; left: 0; right: 100%;
  height: 1px;
  background: linear-gradient(90deg, var(--cyan), var(--pink));
  transition: right 0.35s cubic-bezier(0.23,1,0.32,1);
}
.nav-links a:hover { color: #fff; }
.nav-links a:hover::after { right: 0; }

/* ===================== SECTIONS WRAPPER ===================== */
main { position: relative; z-index: 1; }
section { padding: 7rem 6vw; }
.section-label {
  display: inline-flex; align-items: center; gap: 0.6rem;
  font-size: 0.72rem;
  font-weight: 600;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--cyan);
  margin-bottom: 1rem;
}
.section-label::before {
  content: '';
  display: inline-block;
  width: 24px; height: 1px;
  background: var(--cyan);
}
.section-title {
  font-family: var(--font-head);
  font-size: clamp(2rem, 4vw, 3.5rem);
  font-weight: 800;
  letter-spacing: -0.02em;
  line-height: 1.1;
  margin-bottom: 1rem;
}

/* ===================== HERO ===================== */
#hero {
  min-height: 100vh;
  display: flex; align-items: center;
  padding-top: 7rem;
  overflow: hidden;
  position: relative;
}
.hero-glow {
  position: absolute;
  width: 70vw; height: 70vw;
  top: -20%; right: -20%;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(61,47,169,0.18) 0%, transparent 70%);
  pointer-events: none;
}
.hero-glow2 {
  position: absolute;
  width: 50vw; height: 50vw;
  bottom: -10%; left: -10%;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(240,19,122,0.12) 0%, transparent 70%);
  pointer-events: none;
}
.hero-inner {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
  width: 100%;
}
.hero-left { opacity: 0; animation: fadeUp 1s 2.4s cubic-bezier(0.23,1,0.32,1) forwards; }
.hero-right { opacity: 0; animation: fadeUp 1s 2.6s cubic-bezier(0.23,1,0.32,1) forwards; }
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}
.hero-availability {
  display: inline-flex; align-items: center; gap: 0.6rem;
  padding: 0.4rem 1rem;
  border: 1px solid rgba(0,229,255,0.25);
  border-radius: 100px;
  background: rgba(0,229,255,0.06);
  font-size: 0.78rem;
  font-weight: 500;
  color: var(--cyan);
  margin-bottom: 1.5rem;
  letter-spacing: 0.04em;
}
.hero-availability::before {
  content: '';
  width: 7px; height: 7px;
  background: var(--cyan);
  border-radius: 50%;
  box-shadow: 0 0 8px var(--cyan);
  animation: pulse 2s infinite;
}
@keyframes pulse {
  0%,100% { opacity: 1; transform: scale(1); }
  50% { opacity: 0.5; transform: scale(0.8); }
}
.hero-name {
  font-family: var(--font-head);
  font-size: clamp(2.8rem, 6vw, 5.5rem);
  font-weight: 800;
  letter-spacing: -0.03em;
  line-height: 1.0;
  margin-bottom: 1rem;
}
.hero-name .gradient-text {
  background: linear-gradient(135deg, #fff 0%, var(--indigo-light) 35%, var(--pink) 70%, var(--amber) 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.hero-role {
  font-size: clamp(1rem, 1.8vw, 1.3rem);
  font-weight: 400;
  color: var(--muted);
  margin-bottom: 1.5rem;
  letter-spacing: 0.01em;
}
.hero-role strong { color: var(--text); font-weight: 500; }
.hero-desc {
  font-size: 0.97rem;
  color: var(--muted);
  max-width: 520px;
  line-height: 1.8;
  margin-bottom: 2.5rem;
}
.hero-btns { display: flex; gap: 1rem; flex-wrap: wrap; }
.btn-primary {
  display: inline-flex; align-items: center; gap: 0.5rem;
  padding: 0.8rem 1.8rem;
  background: linear-gradient(135deg, var(--indigo-light), var(--pink));
  color: #fff; font-weight: 600; font-size: 0.88rem;
  letter-spacing: 0.04em;
  text-decoration: none; border-radius: 6px;
  transition: transform 0.3s, box-shadow 0.3s;
  box-shadow: 0 4px 20px rgba(240,19,122,0.3);
}
.btn-primary:hover { transform: translateY(-2px); box-shadow: 0 8px 32px rgba(240,19,122,0.45); }
.btn-secondary {
  display: inline-flex; align-items: center; gap: 0.5rem;
  padding: 0.8rem 1.8rem;
  border: 1px solid var(--border);
  background: var(--surface);
  color: var(--text); font-weight: 500; font-size: 0.88rem;
  text-decoration: none; border-radius: 6px;
  transition: border-color 0.3s, background 0.3s, transform 0.3s;
  backdrop-filter: blur(8px);
}
.btn-secondary:hover { border-color: rgba(0,229,255,0.4); background: rgba(0,229,255,0.05); transform: translateY(-2px); }

/* Hero Right: Stats card */
.hero-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 16px;
  padding: 2.2rem;
  backdrop-filter: blur(16px);
  position: relative;
  overflow: hidden;
}
.hero-card::before {
  content: '';
  position: absolute; inset: 0;
  background: linear-gradient(135deg, rgba(61,47,169,0.1), rgba(240,19,122,0.06));
  pointer-events: none;
}
.stat-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1.5rem; margin-bottom: 1.8rem; }
.stat-item { text-align: center; }
.stat-num {
  font-family: var(--font-head);
  font-size: 2.2rem;
  font-weight: 800;
  background: linear-gradient(135deg, var(--cyan), var(--indigo-light));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height: 1.1;
}
.stat-label { font-size: 0.78rem; color: var(--muted); margin-top: 0.2rem; letter-spacing: 0.04em; }
.hero-contacts { display: flex; flex-direction: column; gap: 0.6rem; }
.contact-row {
  display: flex; align-items: center; gap: 0.6rem;
  font-size: 0.82rem; color: var(--muted);
}
.contact-row svg { color: var(--cyan); flex-shrink: 0; }
.contact-row a { color: var(--muted); text-decoration: none; transition: color 0.3s; }
.contact-row a:hover { color: var(--cyan); }

/* ===================== ABOUT ===================== */
#about { background: var(--bg2); }
.about-inner {
  display: grid;
  grid-template-columns: 1fr 1.6fr;
  gap: 5rem;
  align-items: start;
}
.about-left-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 16px;
  padding: 2rem;
  position: sticky; top: 100px;
}
.profile-avatar {
  width: 80px; height: 80px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--indigo-light), var(--pink));
  display: flex; align-items: center; justify-content: center;
  font-family: var(--font-head);
  font-size: 1.8rem;
  font-weight: 800;
  color: #fff;
  margin-bottom: 1rem;
  box-shadow: 0 0 24px rgba(91,79,207,0.4);
}
.about-left-card h3 {
  font-family: var(--font-head);
  font-size: 1.2rem;
  font-weight: 700;
  margin-bottom: 0.2rem;
}
.about-left-card p { font-size: 0.82rem; color: var(--muted); margin-bottom: 1.4rem; }
.pill-row { display: flex; flex-wrap: wrap; gap: 0.5rem; }
.pill {
  padding: 0.25rem 0.75rem;
  border-radius: 100px;
  font-size: 0.73rem;
  font-weight: 500;
  letter-spacing: 0.04em;
  border: 1px solid;
}
.pill-indigo { border-color: rgba(91,79,207,0.4); color: var(--indigo-light); background: rgba(91,79,207,0.08); }
.pill-pink { border-color: rgba(240,19,122,0.4); color: var(--pink); background: rgba(240,19,122,0.08); }
.pill-cyan { border-color: rgba(0,229,255,0.3); color: var(--cyan); background: rgba(0,229,255,0.07); }
.pill-amber { border-color: rgba(255,179,0,0.3); color: var(--amber); background: rgba(255,179,0,0.07); }

.about-right p { font-size: 1rem; color: var(--muted); line-height: 1.9; margin-bottom: 1.2rem; }
.about-right p strong { color: var(--text); }

/* ===================== SKILLS ===================== */
#skills { background: var(--bg); }
.skills-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 1.2rem; margin-top: 3rem; }
.skill-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 12px;
  padding: 1.4rem 1.6rem;
  transition: border-color 0.3s, transform 0.3s, box-shadow 0.3s;
  position: relative;
  overflow: hidden;
}
.skill-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0; height: 2px;
  opacity: 0;
  transition: opacity 0.3s;
}
.skill-card:hover { transform: translateY(-3px); border-color: rgba(0,229,255,0.2); }
.skill-card:hover::before { opacity: 1; }
.sc-1::before { background: linear-gradient(90deg, var(--indigo-light), var(--cyan)); }
.sc-2::before { background: linear-gradient(90deg, var(--pink), var(--amber)); }
.sc-3::before { background: linear-gradient(90deg, var(--cyan), var(--indigo-light)); }
.sc-4::before { background: linear-gradient(90deg, var(--amber), var(--pink)); }
.sc-5::before { background: linear-gradient(90deg, var(--indigo-light), var(--pink)); }
.sc-6::before { background: linear-gradient(90deg, var(--cyan), var(--amber)); }
.sc-7::before { background: linear-gradient(90deg, var(--pink), var(--cyan)); }
.sc-8::before { background: linear-gradient(90deg, var(--amber), var(--indigo-light)); }
.sc-9::before { background: linear-gradient(90deg, var(--indigo-light), var(--amber)); }
.sc-10::before { background: linear-gradient(90deg, var(--cyan), var(--pink)); }

.skill-category {
  font-family: var(--font-head);
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--cyan);
  margin-bottom: 0.8rem;
  display: flex; align-items: center; gap: 0.5rem;
}
.skill-category .icon { font-size: 1rem; }
.skill-tags { display: flex; flex-wrap: wrap; gap: 0.4rem; }
.skill-tag {
  font-size: 0.74rem;
  padding: 0.2rem 0.65rem;
  background: rgba(255,255,255,0.04);
  border: 1px solid var(--border);
  border-radius: 4px;
  color: var(--text);
  transition: background 0.2s, border-color 0.2s;
}
.skill-tag:hover { background: rgba(0,229,255,0.08); border-color: rgba(0,229,255,0.3); }

/* ===================== EXPERIENCE ===================== */
#experience { background: var(--bg2); }
.exp-list { margin-top: 3rem; display: flex; flex-direction: column; gap: 2rem; }
.exp-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 16px;
  padding: 2.2rem 2.4rem;
  position: relative;
  overflow: hidden;
  transition: border-color 0.3s, transform 0.3s;
}
.exp-card:hover { border-color: rgba(91,79,207,0.3); transform: translateX(4px); }
.exp-card::after {
  content: '';
  position: absolute; top: 0; left: 0; bottom: 0; width: 3px;
  background: linear-gradient(var(--indigo-light), var(--pink));
  opacity: 0;
  transition: opacity 0.3s;
}
.exp-card:hover::after { opacity: 1; }
.exp-header { display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; gap: 1rem; margin-bottom: 0.5rem; }
.exp-title {
  font-family: var(--font-head);
  font-size: 1.2rem;
  font-weight: 700;
  color: #fff;
}
.exp-company { font-size: 0.95rem; color: var(--cyan); font-weight: 500; margin-bottom: 0.2rem; }
.exp-loc { font-size: 0.82rem; color: var(--muted); }
.exp-date {
  font-size: 0.78rem;
  font-weight: 600;
  letter-spacing: 0.06em;
  padding: 0.3rem 0.9rem;
  border-radius: 100px;
  background: rgba(91,79,207,0.12);
  border: 1px solid rgba(91,79,207,0.25);
  color: var(--indigo-light);
  white-space: nowrap;
}
.exp-date.current { background: rgba(0,229,255,0.08); border-color: rgba(0,229,255,0.25); color: var(--cyan); }
.exp-bullets { margin-top: 1.2rem; display: flex; flex-direction: column; gap: 0.55rem; }
.exp-bullet {
  display: flex; gap: 0.7rem;
  font-size: 0.9rem;
  color: var(--muted);
  line-height: 1.65;
}
.exp-bullet::before {
  content: '▸';
  color: var(--pink);
  flex-shrink: 0;
  margin-top: 0.05rem;
}
.exp-tags { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-top: 1.4rem; }
.exp-tag {
  font-size: 0.7rem;
  padding: 0.15rem 0.6rem;
  background: rgba(255,255,255,0.03);
  border: 1px solid var(--border);
  border-radius: 4px;
  color: var(--muted);
}

/* ===================== CERTIFICATIONS & EDUCATION ===================== */
#cedu { background: var(--bg); }
.cedu-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; margin-top: 3rem; }
.ce-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 16px;
  padding: 2rem;
  position: relative;
  overflow: hidden;
  transition: border-color 0.3s, transform 0.3s;
}
.ce-card:hover { transform: translateY(-4px); border-color: rgba(0,229,255,0.25); }
.ce-icon {
  width: 48px; height: 48px;
  border-radius: 12px;
  display: flex; align-items: center; justify-content: center;
  font-size: 1.4rem;
  margin-bottom: 1.2rem;
}
.ce-icon-aws { background: rgba(255,179,0,0.1); border: 1px solid rgba(255,179,0,0.2); }
.ce-icon-edu { background: rgba(91,79,207,0.1); border: 1px solid rgba(91,79,207,0.2); }
.ce-card h3 {
  font-family: var(--font-head);
  font-size: 1.05rem;
  font-weight: 700;
  color: #fff;
  margin-bottom: 0.3rem;
}
.ce-card p { font-size: 0.88rem; color: var(--muted); line-height: 1.6; }
.ce-card .ce-meta { font-size: 0.78rem; color: var(--amber); margin-top: 0.5rem; font-weight: 500; }
.ce-card .ce-meta.blue { color: var(--indigo-light); }

/* ===================== CONTACT ===================== */
#contact {
  background: var(--bg2);
  text-align: center;
}
.contact-inner { max-width: 640px; margin: 0 auto; }
.contact-inner .section-label { justify-content: center; }
.contact-inner .section-title { margin-bottom: 1rem; }
.contact-inner p { color: var(--muted); margin-bottom: 2.5rem; font-size: 1rem; }
.contact-links { display: flex; justify-content: center; flex-wrap: wrap; gap: 1rem; }
.contact-link {
  display: inline-flex; align-items: center; gap: 0.6rem;
  padding: 0.85rem 1.6rem;
  border-radius: 8px;
  font-size: 0.88rem; font-weight: 500;
  text-decoration: none;
  transition: transform 0.3s, box-shadow 0.3s;
}
.cl-email { background: linear-gradient(135deg, var(--indigo-light), var(--pink)); color: #fff; box-shadow: 0 4px 20px rgba(91,79,207,0.3); }
.cl-email:hover { transform: translateY(-2px); box-shadow: 0 8px 32px rgba(91,79,207,0.5); }
.cl-linkedin { background: var(--surface); border: 1px solid var(--border); color: var(--text); }
.cl-linkedin:hover { transform: translateY(-2px); border-color: rgba(0,229,255,0.35); }
.cl-phone { background: var(--surface); border: 1px solid var(--border); color: var(--text); }
.cl-phone:hover { transform: translateY(-2px); border-color: rgba(255,179,0,0.35); }

/* ===================== FOOTER ===================== */
footer {
  padding: 2rem 6vw;
  border-top: 1px solid var(--border);
  display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 1rem;
  font-size: 0.78rem; color: var(--muted);
  background: var(--bg);
  position: relative; z-index: 1;
}
footer span { color: var(--indigo-light); }

/* ===================== SCROLL REVEAL ===================== */
.reveal {
  opacity: 0;
  transform: translateY(28px);
  transition: opacity 0.7s cubic-bezier(0.23,1,0.32,1), transform 0.7s cubic-bezier(0.23,1,0.32,1);
}
.reveal.visible { opacity: 1; transform: translateY(0); }

/* ===================== RESPONSIVE ===================== */
@media (max-width: 900px) {
  .hero-inner { grid-template-columns: 1fr; }
  .hero-right { display: none; }
  .about-inner { grid-template-columns: 1fr; }
  .about-left-card { position: static; }
  .cedu-grid { grid-template-columns: 1fr; }
  .nav-links { display: none; }
}
@media (max-width: 600px) {
  section { padding: 5rem 5vw; }
  .skills-grid { grid-template-columns: 1fr; }
}
</style>
</head>
<body>

<!-- CURSORS -->
<div id="cursor-dot"></div>
<div id="cursor-ring"></div>

<!-- LOADER -->
<div id="loader">
  <div class="loader-initials">VV</div>
  <div class="loader-bar-wrap"><div class="loader-bar"></div></div>
</div>

<!-- PARTICLE CANVAS -->
<canvas id="particle-canvas"></canvas>

<!-- NAVBAR -->
<nav>
  <a href="#hero" class="nav-logo">Venkatesh<span>.</span></a>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#cedu">Education</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<main>
<!-- ======= HERO ======= -->
<section id="hero">
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>
  <div class="hero-inner">
    <div class="hero-left">
      <div class="hero-availability">🟢 Open to New Opportunities</div>
      <h1 class="hero-name">
        <span class="gradient-text">Venkatesh</span><br/>
        <span class="gradient-text">Vangari</span>
      </h1>
      <p class="hero-role"><strong>Senior DevOps &amp; Cloud Platform Engineer</strong></p>
      <p class="hero-desc">
        5+ years designing, automating, and operating enterprise-scale cloud platforms on <strong>AWS &amp; Azure</strong>. Expert in CI/CD pipelines, Kubernetes, Infrastructure as Code, and secure cloud-native architecture for regulated industries.
      </p>
      <div class="hero-btns">
        <a href="#contact" class="btn-primary">
          <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
          Get In Touch
        </a>
        <a href="#experience" class="btn-secondary">
          <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><rect x="2" y="7" width="20" height="14" rx="2"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/></svg>
          View Experience
        </a>
      </div>
    </div>
    <div class="hero-right">
      <div class="hero-card">
        <div class="stat-grid">
          <div class="stat-item">
            <div class="stat-num">5+</div>
            <div class="stat-label">Years Experience</div>
          </div>
          <div class="stat-item">
            <div class="stat-num">3+</div>
            <div class="stat-label">Companies</div>
          </div>
          <div class="stat-item">
            <div class="stat-num">AWS</div>
            <div class="stat-label">Certified SA</div>
          </div>
          <div class="stat-item">
            <div class="stat-num">50+</div>
            <div class="stat-label">Tools &amp; Tech</div>
          </div>
        </div>
        <div class="hero-contacts">
          <div class="contact-row">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
            <a href="mailto:Venkatesh.v9191@gmail.com">Venkatesh.v9191@gmail.com</a>
          </div>
          <div class="contact-row">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07A19.5 19.5 0 0 1 4.69 12a19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 3.6 1.22h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 8.91A16 16 0 0 0 15 15.91l.81-.82a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
            <a href="tel:2134337125">(213) 433-7125</a>
          </div>
          <div class="contact-row">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
            <a href="http://linkedin.com/in/venkatesh-vangar14" target="_blank">linkedin.com/in/venkatesh-vangar14</a>
          </div>
          <div class="contact-row">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
            <span>Illinois, USA</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ======= ABOUT ======= -->
<section id="about">
  <div class="about-inner reveal">
    <div class="about-left-card">
      <div class="profile-avatar">VV</div>
      <h3>Venkatesh Vangari</h3>
      <p>Senior DevOps / Cloud Platform Engineer</p>
      <div class="pill-row">
        <span class="pill pill-cyan">AWS</span>
        <span class="pill pill-indigo">Azure</span>
        <span class="pill pill-pink">Kubernetes</span>
        <span class="pill pill-amber">Terraform</span>
        <span class="pill pill-cyan">CI/CD</span>
        <span class="pill pill-indigo">Docker</span>
        <span class="pill pill-pink">Python</span>
        <span class="pill pill-amber">IaC</span>
      </div>
    </div>
    <div class="about-right">
      <div class="section-label">About Me</div>
      <h2 class="section-title">Building the Infrastructure<br/>That Scales Teams</h2>
      <p>
        I'm a <strong>Results-driven Senior DevOps / Cloud Platform Engineer</strong> with 5 years of experience designing, automating, and operating enterprise-scale cloud platforms on <strong>AWS and Azure</strong> in regulated environments.
      </p>
      <p>
        My expertise spans <strong>CI/CD pipeline engineering</strong> (Jenkins, GitLab CI, Azure DevOps), <strong>Infrastructure as Code</strong> (Terraform, Ansible, CloudFormation, ARM Templates), <strong>container orchestration</strong> (Docker, Kubernetes/EKS/AKS), and <strong>configuration management</strong> (Ansible, Puppet, Chef).
      </p>
      <p>
        I have a proven track record of building automated CI/CD pipelines from scratch, migrating on-premises workloads to cloud, implementing serverless architectures, and enforcing <strong>security &amp; compliance guardrails</strong>. I collaborate closely with development, QA, and platform teams using <strong>Agile/Scrum</strong> methodologies.
      </p>
    </div>
  </div>
</section>

<!-- ======= SKILLS ======= -->
<section id="skills">
  <div class="section-label reveal">Technical Arsenal</div>
  <h2 class="section-title reveal">Skills &amp; Technologies</h2>
  <div class="skills-grid">

    <div class="skill-card sc-1 reveal">
      <div class="skill-category"><span class="icon">☁️</span> Cloud Platforms</div>
      <div class="skill-tags">
        <span class="skill-tag">AWS EC2</span><span class="skill-tag">S3</span><span class="skill-tag">RDS</span><span class="skill-tag">Lambda</span><span class="skill-tag">EKS</span><span class="skill-tag">ELB</span><span class="skill-tag">CloudFront</span><span class="skill-tag">VPC</span><span class="skill-tag">Route 53</span><span class="skill-tag">IAM</span><span class="skill-tag">DynamoDB</span><span class="skill-tag">Redshift</span><span class="skill-tag">SNS</span><span class="skill-tag">SQS</span><span class="skill-tag">CloudTrail</span><span class="skill-tag">Azure VMs</span><span class="skill-tag">AKS</span><span class="skill-tag">Azure SQL</span><span class="skill-tag">Key Vault</span><span class="skill-tag">Azure AD</span><span class="skill-tag">GCP</span>
      </div>
    </div>

    <div class="skill-card sc-2 reveal">
      <div class="skill-category"><span class="icon">🔁</span> CI/CD Tools</div>
      <div class="skill-tags">
        <span class="skill-tag">Jenkins</span><span class="skill-tag">GitLab CI</span><span class="skill-tag">Azure DevOps</span><span class="skill-tag">GitHub Actions</span><span class="skill-tag">Bamboo</span><span class="skill-tag">Hudson</span><span class="skill-tag">TeamCity</span><span class="skill-tag">Octopus Deploy</span><span class="skill-tag">XLRelease</span><span class="skill-tag">IBM uDeploy</span>
      </div>
    </div>

    <div class="skill-card sc-3 reveal">
      <div class="skill-category"><span class="icon">🏗️</span> IaC &amp; Config Mgmt</div>
      <div class="skill-tags">
        <span class="skill-tag">Terraform</span><span class="skill-tag">AWS CDK</span><span class="skill-tag">CloudFormation</span><span class="skill-tag">ARM Templates</span><span class="skill-tag">Ansible</span><span class="skill-tag">Ansible Tower</span><span class="skill-tag">Puppet</span><span class="skill-tag">Chef</span><span class="skill-tag">Vagrant</span>
      </div>
    </div>

    <div class="skill-card sc-4 reveal">
      <div class="skill-category"><span class="icon">🐳</span> Containers &amp; Orchestration</div>
      <div class="skill-tags">
        <span class="skill-tag">Docker</span><span class="skill-tag">Docker Swarm</span><span class="skill-tag">ECR</span><span class="skill-tag">Kubernetes</span><span class="skill-tag">EKS</span><span class="skill-tag">AKS</span><span class="skill-tag">OpenShift</span><span class="skill-tag">Helm</span><span class="skill-tag">Kustomize</span>
      </div>
    </div>

    <div class="skill-card sc-5 reveal">
      <div class="skill-category"><span class="icon">📦</span> Build &amp; Version Control</div>
      <div class="skill-tags">
        <span class="skill-tag">Maven</span><span class="skill-tag">Gradle</span><span class="skill-tag">Ant</span><span class="skill-tag">Git</span><span class="skill-tag">GitHub</span><span class="skill-tag">GitLab</span><span class="skill-tag">Bitbucket</span><span class="skill-tag">SVN</span><span class="skill-tag">JFrog Artifactory</span><span class="skill-tag">Nexus</span>
      </div>
    </div>

    <div class="skill-card sc-6 reveal">
      <div class="skill-category"><span class="icon">📊</span> Monitoring &amp; Logging</div>
      <div class="skill-tags">
        <span class="skill-tag">Prometheus</span><span class="skill-tag">Grafana</span><span class="skill-tag">CloudWatch</span><span class="skill-tag">ELK Stack</span><span class="skill-tag">Splunk</span><span class="skill-tag">Nagios</span><span class="skill-tag">Datadog</span><span class="skill-tag">SonarQube</span>
      </div>
    </div>

    <div class="skill-card sc-7 reveal">
      <div class="skill-category"><span class="icon">💻</span> Scripting &amp; Languages</div>
      <div class="skill-tags">
        <span class="skill-tag">Python</span><span class="skill-tag">Bash / Shell</span><span class="skill-tag">PowerShell</span><span class="skill-tag">YAML</span><span class="skill-tag">Groovy</span><span class="skill-tag">Perl</span><span class="skill-tag">C#</span>
      </div>
    </div>

    <div class="skill-card sc-8 reveal">
      <div class="skill-category"><span class="icon">🗄️</span> Databases</div>
      <div class="skill-tags">
        <span class="skill-tag">MySQL</span><span class="skill-tag">PostgreSQL</span><span class="skill-tag">Oracle</span><span class="skill-tag">DynamoDB</span><span class="skill-tag">MongoDB</span><span class="skill-tag">Redshift</span><span class="skill-tag">Azure SQL</span>
      </div>
    </div>

    <div class="skill-card sc-9 reveal">
      <div class="skill-category"><span class="icon">🔐</span> Networking &amp; Security</div>
      <div class="skill-tags">
        <span class="skill-tag">VPC</span><span class="skill-tag">Subnets</span><span class="skill-tag">Route 53</span><span class="skill-tag">IAM</span><span class="skill-tag">Security Groups</span><span class="skill-tag">Load Balancers</span><span class="skill-tag">HTTPS/TLS</span><span class="skill-tag">VPN</span><span class="skill-tag">Azure Key Vault</span><span class="skill-tag">Zero Trust</span>
      </div>
    </div>

    <div class="skill-card sc-10 reveal">
      <div class="skill-category"><span class="icon">🖥️</span> Operating Systems &amp; Middleware</div>
      <div class="skill-tags">
        <span class="skill-tag">RHEL 6/7/8/9</span><span class="skill-tag">Ubuntu</span><span class="skill-tag">Windows Server</span><span class="skill-tag">Solaris</span><span class="skill-tag">Apache Tomcat</span><span class="skill-tag">Nginx</span><span class="skill-tag">JBoss</span><span class="skill-tag">WebLogic</span><span class="skill-tag">IIS</span>
      </div>
    </div>

  </div>
</section>

<!-- ======= EXPERIENCE ======= -->
<section id="experience">
  <div class="section-label reveal">Career Journey</div>
  <h2 class="section-title reveal">Professional Experience</h2>
  <div class="exp-list">

    <!-- Fifth Third Bank -->
    <div class="exp-card reveal">
      <div class="exp-header">
        <div>
          <div class="exp-title">Cloud Platform Engineer</div>
          <div class="exp-company">Fifth Third Bank</div>
          <div class="exp-loc">📍 Chicago, IL</div>
        </div>
        <div class="exp-date current">Jul 2024 – Present</div>
      </div>
      <div class="exp-bullets">
        <div class="exp-bullet">Supported 3+ development teams leading CI/CD pipelines, release cycles, and production deployments across multiple environments on AWS.</div>
        <div class="exp-bullet">Designed and enhanced AWS Landing Zone architecture with standardized networking, IAM, security baselines, and multi-account structure for scalable enterprise financial workloads.</div>
        <div class="exp-bullet">Built and maintained IaC using Terraform, AWS CDK, CloudFormation, Helm, and Kustomize for consistent, repeatable cloud provisioning and drift detection.</div>
        <div class="exp-bullet">Implemented automated CI/CD pipelines using Jenkins and GitLab CI, enabling secure and reliable application delivery with auto-triggered build, test, and deploy stages.</div>
        <div class="exp-bullet">Containerized legacy applications and deployed microservices on Amazon EKS with automated scaling, rolling updates, and self-healing workload patterns.</div>
        <div class="exp-bullet">Implemented serverless and event-driven workflows using AWS Lambda, Step Functions, and SNS, reducing operational overhead.</div>
        <div class="exp-bullet">Implemented full-stack observability using CloudWatch, Prometheus, Grafana, ELK, and Splunk supporting SLA tracking and incident response.</div>
        <div class="exp-bullet">Enforced security best practices: least-privilege IAM, encryption at rest/transit, network isolation, and compliance guardrails for regulated environments.</div>
      </div>
      <div class="exp-tags">
        <span class="exp-tag">AWS</span><span class="exp-tag">Terraform</span><span class="exp-tag">CDK</span><span class="exp-tag">CloudFormation</span><span class="exp-tag">Jenkins</span><span class="exp-tag">GitLab CI</span><span class="exp-tag">EKS</span><span class="exp-tag">Docker</span><span class="exp-tag">Helm</span><span class="exp-tag">Python</span><span class="exp-tag">Bash</span><span class="exp-tag">Prometheus</span><span class="exp-tag">Grafana</span><span class="exp-tag">ELK</span><span class="exp-tag">Splunk</span>
      </div>
    </div>

    <!-- Monocept -->
    <div class="exp-card reveal">
      <div class="exp-header">
        <div>
          <div class="exp-title">DevOps / Azure Engineer</div>
          <div class="exp-company">Monocept</div>
          <div class="exp-loc">📍 Hyderabad, India</div>
        </div>
        <div class="exp-date">Aug 2021 – Jul 2023</div>
      </div>
      <div class="exp-bullets">
        <div class="exp-bullet">Designed and maintained cloud infrastructure on AWS and Microsoft Azure, ensuring high availability, scalability, and security across environments.</div>
        <div class="exp-bullet">Built and automated CI/CD pipelines using Jenkins and Azure DevOps (with XLR orchestration) enabling reliable build, test, and deployment workflows from scratch.</div>
        <div class="exp-bullet">Implemented IaC using Terraform and Ansible; configured Ansible Tower to automate build/configuration of new servers, making them production-ready within 30 minutes of OS installation.</div>
        <div class="exp-bullet">Managed Kubernetes clusters (EKS/AKS), containerized workloads, deployments, scaling, and troubleshooting; developed Docker images and deployed using Docker Swarm.</div>
        <div class="exp-bullet">Migrated on-premises databases and applications to Azure cloud; integrated structured/unstructured data into Azure SQL Data Warehouse and monitored Azure Data Pipelines.</div>
        <div class="exp-bullet">Managed JFrog Artifactory and Sonatype Nexus for artifact and dependency management; integrated with Maven/Gradle build pipelines.</div>
      </div>
      <div class="exp-tags">
        <span class="exp-tag">AWS</span><span class="exp-tag">Azure</span><span class="exp-tag">Terraform</span><span class="exp-tag">Ansible</span><span class="exp-tag">Puppet</span><span class="exp-tag">Chef</span><span class="exp-tag">Jenkins</span><span class="exp-tag">Azure DevOps</span><span class="exp-tag">Docker</span><span class="exp-tag">Kubernetes</span><span class="exp-tag">Helm</span><span class="exp-tag">XLR</span><span class="exp-tag">Git</span><span class="exp-tag">Splunk</span><span class="exp-tag">ELK</span>
      </div>
    </div>

    <!-- Ajackus -->
    <div class="exp-card reveal">
      <div class="exp-header">
        <div>
          <div class="exp-title">Linux System Administrator</div>
          <div class="exp-company">Ajackus</div>
          <div class="exp-loc">📍 Mumbai, India</div>
        </div>
        <div class="exp-date">Jun 2020 – Aug 2021</div>
      </div>
      <div class="exp-bullets">
        <div class="exp-bullet">Managed and optimized Linux servers (RHEL 7/8/9), improving system stability, security, and performance through hardening using IPTables and security group policies.</div>
        <div class="exp-bullet">Automated system administration using Shell, Bash, and Python scripts, reducing manual effort and increasing operational efficiency.</div>
        <div class="exp-bullet">Configured Apache, Tomcat, MySQL, DNS, SSH, NFS, and firewall rules ensuring secure and reliable services; experienced with IIS and Windows Server 2008/2012.</div>
        <div class="exp-bullet">Built and maintained Jenkins CI pipelines integrated with Maven/Gradle; managed Nexus Artifactory for artifact and dependency management.</div>
        <div class="exp-bullet">Managed AWS cloud services: EC2, S3, EBS, AMI, ELB, Auto Scaling, VPC; performed system configuration, network configuration, and user/group account management.</div>
      </div>
      <div class="exp-tags">
        <span class="exp-tag">Linux (RHEL)</span><span class="exp-tag">AWS</span><span class="exp-tag">Jenkins</span><span class="exp-tag">Maven</span><span class="exp-tag">Nexus</span><span class="exp-tag">Nagios</span><span class="exp-tag">Apache</span><span class="exp-tag">Tomcat</span><span class="exp-tag">Bash</span><span class="exp-tag">Python</span><span class="exp-tag">Docker</span>
      </div>
    </div>

  </div>
</section>

<!-- ======= CERTIFICATIONS & EDUCATION ======= -->
<section id="cedu">
  <div class="section-label reveal">Credentials</div>
  <h2 class="section-title reveal">Certifications &amp; Education</h2>
  <div class="cedu-grid">

    <div class="ce-card reveal">
      <div class="ce-icon ce-icon-aws">🏅</div>
      <h3>AWS Certified Solutions Architect</h3>
      <p>Associate-level certification validating expertise in designing distributed systems and deploying scalable, highly available, and fault-tolerant applications on Amazon Web Services.</p>
      <div class="ce-meta">Amazon Web Services · AWS Certification</div>
    </div>

    <div class="ce-card reveal">
      <div class="ce-icon ce-icon-edu">🎓</div>
      <h3>Master of Science – Computer Technology</h3>
      <p>Graduate studies in Computer Technology covering advanced topics in systems, cloud computing, and modern software engineering practices.</p>
      <div class="ce-meta blue">Eastern Illinois University · Charleston, IL, USA</div>
    </div>

    <div class="ce-card reveal">
      <div class="ce-icon ce-icon-edu">🎓</div>
      <h3>Bachelor of Technology</h3>
      <p>Undergraduate engineering degree with a foundation in computer science, programming, networking, and software development principles.</p>
      <div class="ce-meta blue">CMR Institute of Technology · Hyderabad, India</div>
    </div>

  </div>
</section>

<!-- ======= CONTACT ======= -->
<section id="contact">
  <div class="contact-inner reveal">
    <div class="section-label">Let's Connect</div>
    <h2 class="section-title">Open to Exciting<br/>Opportunities</h2>
    <p>Whether you have a challenging DevOps role, cloud platform project, or just want to talk infrastructure — I'd love to hear from you.</p>
    <div class="contact-links">
      <a href="mailto:Venkatesh.v9191@gmail.com" class="contact-link cl-email">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
        Send Email
      </a>
      <a href="http://linkedin.com/in/venkatesh-vangar14" target="_blank" class="contact-link cl-linkedin">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
        LinkedIn
      </a>
      <a href="tel:2134337125" class="contact-link cl-phone">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07A19.5 19.5 0 0 1 4.69 12a19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 3.6 1.22h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 8.91A16 16 0 0 0 15 15.91l.81-.82a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
        (213) 433-7125
      </a>
    </div>
  </div>
</section>
</main>

<footer>
  <span>Venkatesh Vangari</span>
  <div>Built with ❤️ · Illinois, USA · 2025</div>
</footer>

<script>
/* ========== LOADER ========== */
window.addEventListener('load', () => {
  setTimeout(() => {
    document.getElementById('loader').classList.add('hidden');
  }, 2100);
});

/* ========== CUSTOM CURSOR ========== */
const dot = document.getElementById('cursor-dot');
const ring = document.getElementById('cursor-ring');
let mx = 0, my = 0, rx = 0, ry = 0;

document.addEventListener('mousemove', e => {
  mx = e.clientX; my = e.clientY;
  dot.style.left = mx + 'px';
  dot.style.top = my + 'px';
});

function animRing() {
  rx += (mx - rx) * 0.12;
  ry += (my - ry) * 0.12;
  ring.style.left = rx + 'px';
  ring.style.top = ry + 'px';
  requestAnimationFrame(animRing);
}
animRing();

document.querySelectorAll('a, button, .skill-card, .exp-card').forEach(el => {
  el.addEventListener('mouseenter', () => {
    ring.style.width = '48px'; ring.style.height = '48px';
    ring.style.borderColor = 'rgba(240,19,122,0.7)';
    dot.style.transform = 'translate(-50%,-50%) scale(1.8)';
  });
  el.addEventListener('mouseleave', () => {
    ring.style.width = '32px'; ring.style.height = '32px';
    ring.style.borderColor = 'rgba(0,229,255,0.5)';
    dot.style.transform = 'translate(-50%,-50%) scale(1)';
  });
});

/* ========== PARTICLE CANVAS ========== */
const canvas = document.getElementById('particle-canvas');
const ctx = canvas.getContext('2d');
let W, H, particles = [];
const COLORS = ['#5b4fcf','#f0137a','#00e5ff','#ffb300'];
const N = 90;

function resize() {
  W = canvas.width = window.innerWidth;
  H = canvas.height = window.innerHeight;
}
window.addEventListener('resize', resize);
resize();

class Particle {
  constructor() { this.reset(); }
  reset() {
    this.x = Math.random() * W;
    this.y = Math.random() * H;
    this.vx = (Math.random() - 0.5) * 0.5;
    this.vy = (Math.random() - 0.5) * 0.5;
    this.r = Math.random() * 2 + 1;
    this.color = COLORS[Math.floor(Math.random() * COLORS.length)];
    this.alpha = Math.random() * 0.5 + 0.2;
  }
  update() {
    this.x += this.vx; this.y += this.vy;
    if (this.x < 0 || this.x > W || this.y < 0 || this.y > H) this.reset();
  }
  draw() {
    ctx.save();
    ctx.globalAlpha = this.alpha;
    ctx.fillStyle = this.color;
    ctx.shadowColor = this.color;
    ctx.shadowBlur = 6;
    ctx.beginPath();
    ctx.arc(this.x, this.y, this.r, 0, Math.PI * 2);
    ctx.fill();
    ctx.restore();
  }
}

for (let i = 0; i < N; i++) particles.push(new Particle());

function drawConnections() {
  const maxDist = 130;
  for (let i = 0; i < N; i++) {
    for (let j = i + 1; j < N; j++) {
      const dx = particles[i].x - particles[j].x;
      const dy = particles[i].y - particles[j].y;
      const d = Math.sqrt(dx * dx + dy * dy);
      if (d < maxDist) {
        ctx.save();
        ctx.globalAlpha = (1 - d / maxDist) * 0.15;
        ctx.strokeStyle = particles[i].color;
        ctx.lineWidth = 0.6;
        ctx.beginPath();
        ctx.moveTo(particles[i].x, particles[i].y);
        ctx.lineTo(particles[j].x, particles[j].y);
        ctx.stroke();
        ctx.restore();
      }
    }
  }
}

function loop() {
  ctx.clearRect(0, 0, W, H);
  particles.forEach(p => { p.update(); p.draw(); });
  drawConnections();
  requestAnimationFrame(loop);
}
loop();

/* ========== SCROLL REVEAL ========== */
const reveals = document.querySelectorAll('.reveal');
const io = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.classList.add('visible');
      io.unobserve(e.target);
    }
  });
}, { threshold: 0.12 });
reveals.forEach(el => io.observe(el));
</script>
</body>
</html>
