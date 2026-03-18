---
layout: portfolio_item
title: "HEARD: A Framework for Angry Parent Calls"
type: "Portfolio · Instructional Design"
tools: "Articulate Rise 360, Storyline 360, HTML / CSS / JS"
year: "2025"
excerpt: "A microlearning module for academic coordinators at an edtech provider — built to turn difficult calls into retained families."
---

<style>
.port-hero-band {
  background: #0d1f3c;
  margin: -2rem -1rem 3rem -1rem;
  padding: 3.5rem 2rem 3rem;
  border-radius: 4px;
}
.port-hero-band .port-type {
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: #5dcaa5;
  margin-bottom: 1rem;
  display: block;
}
.port-hero-band h1 {
  font-family: 'Cormorant Garamond', Georgia, serif;
  font-size: clamp(2.2rem, 5vw, 3.5rem);
  font-weight: 700;
  color: #fff;
  line-height: 1.15;
  margin-bottom: 1.25rem;
}
.port-hero-band .port-subtitle {
  font-size: 1rem;
  color: rgba(255,255,255,0.65);
  font-style: italic;
  line-height: 1.7;
  max-width: 60ch;
  margin: 0;
}
.port-section {
  margin-bottom: 3.5rem;
  padding-bottom: 3.5rem;
  border-bottom: 1px solid var(--line);
}
.port-section:last-child { border-bottom: none; }
.port-section-label {
  font-size: 0.75rem;
  font-weight: 800;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 1.5rem;
  display: block;
}
.port-section p {
  font-size: 1rem;
  line-height: 1.85;
  color: var(--ink-soft);
  margin-bottom: 1rem;
  max-width: none;
}
.port-section p strong { color: var(--accent); font-weight: 700; }
.process-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  margin-top: 1.5rem;
}
.process-step {
  padding: 1.75rem;
  border: 1.5px solid var(--line);
  border-radius: 4px;
  background: var(--paper-2);
}
.process-step .step-number {
  font-size: 0.7rem;
  font-weight: 800;
  letter-spacing: 0.16em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 0.6rem;
  display: block;
}
.process-step h3 {
  font-family: var(--font-sans, sans-serif);
  font-size: 1rem;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 0.75rem;
  line-height: 1.4;
}
.process-step p {
  font-size: 0.93rem !important;
  color: var(--ink-soft);
  line-height: 1.8;
  margin: 0 !important;
}
.course-snapshot {
  border: 1.5px solid var(--line);
  border-radius: 8px;
  overflow: hidden;
  margin: 1.5rem 0;
}
.snapshot-topbar {
  background: #0d1f3c;
  padding: 0.65rem 1.25rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.snapshot-topbar span {
  font-size: 0.78rem;
  color: rgba(255,255,255,0.45);
  letter-spacing: 0.06em;
  font-family: sans-serif;
}
.snapshot-img-wrap {
  position: relative;
  display: block;
  overflow: hidden;
  background: var(--paper-2);
}
.snapshot-img-wrap img {
  width: 100%;
  display: block;
  transition: transform 0.35s ease, opacity 0.35s ease;
}
.snapshot-img-wrap:hover img { transform: scale(1.02); opacity: 0.88; }
.snapshot-overlay {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  background: rgba(13,31,60,0.5);
  opacity: 0;
  transition: opacity 0.35s ease;
}
.snapshot-img-wrap:hover .snapshot-overlay { opacity: 1; }
.snapshot-overlay-btn {
  background: #5dcaa5;
  color: #0d1f3c;
  padding: 0.8rem 2.25rem;
  border-radius: 30px;
  font-size: 0.95rem;
  font-family: sans-serif;
  font-weight: 700;
}
.snapshot-caption {
  padding: 0.85rem 1.25rem;
  background: #0d1f3c;
  font-size: 0.78rem;
  color: rgba(255,255,255,0.38);
  font-family: sans-serif;
  font-style: italic;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.snapshot-caption a {
  color: #5dcaa5;
  font-style: normal;
  font-weight: 700;
  text-decoration: none;
  letter-spacing: 0.08em;
  font-size: 0.75rem;
  text-transform: uppercase;
}
.snapshot-caption a:hover { text-decoration: underline; }
.deliverables-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
  margin-top: 1.5rem;
}
.deliverable-card {
  border: 1.5px solid var(--line);
  border-radius: 4px;
  padding: 1.25rem 1.25rem 1.1rem;
  background: var(--paper);
  transition: border-color 0.2s, box-shadow 0.2s;
}
.deliverable-card:hover {
  border-color: var(--accent);
  box-shadow: 0 4px 16px rgba(15,118,110,0.08);
}
.deliverable-card .d-type {
  font-size: 0.72rem;
  font-weight: 800;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--ink);
  margin-bottom: 0.5rem;
  display: block;
  line-height: 1.4;
}
.deliverable-card .d-format {
  font-size: 0.82rem;
  color: var(--accent);
  font-weight: 600;
}
.deliverable-card a.d-format {
  text-decoration: underline;
  text-underline-offset: 2px;
}
.deliverable-card a.d-format:hover { color: var(--accent-dk); }
.reflection-block {
  background: var(--paper-2);
  border-left: 4px solid var(--accent);
  padding: 1.5rem 2rem;
  border-radius: 0 4px 4px 0;
  margin-bottom: 1.5rem;
}
.reflection-block p {
  font-size: 0.98rem !important;
  line-height: 1.85;
  color: var(--ink-soft);
  margin: 0 0 1rem 0 !important;
}
.reflection-block p:last-child { margin: 0 !important; }
.closing-quote {
  background: #0d1f3c;
  border-radius: 6px;
  padding: 2.5rem;
  margin-top: 2rem;
  text-align: center;
}
.closing-quote p {
  font-family: 'Cormorant Garamond', Georgia, serif;
  font-size: 1.25rem !important;
  font-style: italic;
  color: rgba(255,255,255,0.88) !important;
  line-height: 1.75;
  margin: 0 !important;
  max-width: none !important;
}
@media (max-width: 640px) {
  .process-grid { grid-template-columns: 1fr; }
  .deliverables-grid { grid-template-columns: 1fr 1fr; }
  .port-hero-band { margin: -1rem -0.5rem 2rem; padding: 2.5rem 1.25rem 2rem; }
}
</style>

<div class="port-hero-band">
  <span class="port-type">Portfolio · Instructional Design</span>
  <h1>HEARD: A Framework for Angry Parent Calls</h1>
  <p class="port-subtitle">A microlearning module for academic coordinators at an edtech provider — built to turn difficult calls into retained families.</p>
</div>

<div class="port-section">
  <span class="port-section-label">The Brief</span>
  <p>XYZ is an edtech provider connecting students with tutors across India. Academic Coordinators are the first — and often only — point of contact when a parent has a problem. The brief was straightforward: refund requests were rising, and the pattern pointed to one place. Not the product. The calls.</p>
</div>

<div class="port-section">
  <span class="port-section-label">The Challenge</span>
  <p>The coordinators weren't failing because they didn't care. They were failing because no one had ever given them a method. When a parent's voice goes sharp, instinct takes over — and instinct usually means interrupt, explain, apologise vaguely, or escalate.</p>
  <p>The design challenge wasn't just building a course. It was building a framework from scratch — <strong>teachable in under eight minutes, applicable on a live call, and memorable under pressure.</strong></p>
</div>

<div class="port-section">
  <span class="port-section-label">My Process</span>
  <div class="process-grid">
    <div class="process-step">
      <span class="step-number">01 – Analysis</span>
      <h3>Finding the real gap</h3>
      <p>Refund logs and escalation records told a consistent story: no structured call-handling guidance existed. The gap wasn't motivation — it was training.</p>
    </div>
    <div class="process-step">
      <span class="step-number">02 – Design</span>
      <h3>Building the HEARD framework</h3>
      <p>Developed the framework from scratch. Five steps, each with one rule. Tell–Show–Do–Consolidate structure. Guided scenario before independent simulation.</p>
    </div>
    <div class="process-step">
      <span class="step-number">03 – Development</span>
      <h3>Rise + custom build</h3>
      <p>Rise 360 course shell. Storyline 360 branching simulation. Two custom HTML/JS components where Rise's native tools weren't good enough.</p>
    </div>
    <div class="process-step">
      <span class="step-number">04 – Review</span>
      <h3>Storyboard-first workflow</h3>
      <p>Full storyboard produced for SME sign-off before any build began. Every screen, every word, every branching path documented and approved.</p>
    </div>
  </div>
</div>

<div class="port-section">
  <span class="port-section-label">A Snapshot of the Course</span>
  <p style="margin-bottom:1rem;">Click on the course screenshot to view a snapshot.</p>
  <div class="course-snapshot">
    <div class="snapshot-topbar">
      <span>≡ &nbsp; microlearning · articulate rise 360</span>
      <span>8 min · HEARD framework</span>
    </div>
    <a href="https://nayanapsychologist-spec.github.io/storyline-simulation/story.html" target="_blank" rel="noopener" class="snapshot-img-wrap">
        <img src="{{ '/assets/images/heard-rise.png' | relative_url }}" alt="HEARD Framework — Rise 360 course preview" />
        <div class="snapshot-overlay">
          <span class="snapshot-overlay-btn">Launch course →</span>
        </div>
      </a>
      <div class="snapshot-caption">
        <span>Click the image to experience the course</span>
        <a href="https://nayanapsychologist-spec.github.io/heard-training/" target="_blank" rel="noopener">Launch course →</a>
    </div>
  </div>
</div>

<div class="port-section">
  <span class="port-section-label">Deliverables</span>
  <p>Click the format label on any card to open the document.</p>
  <div class="deliverables-grid">
    <div class="deliverable-card">
      <span class="d-type">Pitch Deck</span>
      <a href="https://docs.google.com/presentation/d/1eCL6ygnjJuZnIhReg-PhUhSkIbCgqRhR/edit?slide=id.p1#slide=id.p1" target="_blank" rel="noopener" class="d-format">PowerPoint · v2 ↗</a>
    </div>
    <div class="deliverable-card">
      <span class="d-type">Executive Summary</span>
      <a href="https://docs.google.com/document/d/1YQwA-XxeC4p9BlVbZEWXracedP-aSjYy/edit" target="_blank" rel="noopener" class="d-format">Word ↗</a>
    </div>
    <div class="deliverable-card">
      <span class="d-type">Module Storyboard</span>
      <a href="https://docs.google.com/document/d/13HWfHVVWAGE2I9RlpK5BzQtvKeBBbmva/edit" target="_blank" rel="noopener" class="d-format">Word · SME reviewed ↗</a>
    </div>
    <div class="deliverable-card">
      <span class="d-type">Animated Stat Block</span>
      <span class="d-format">HTML / CSS / JS</span>
    </div>
    <div class="deliverable-card">
      <span class="d-type">Custom Quiz</span>
      <span class="d-format">HTML / CSS / JS</span>
    </div>
    <div class="deliverable-card">
      <span class="d-type">Rise 360 Course</span>
      <span class="d-format">Articulate Rise</span>
    </div>
    <div class="deliverable-card">
      <span class="d-type">HEARD Reference Card</span>
      <a href="https://drive.google.com/file/d/1fsiTfeU7lcBVt4DohgEbegJKbrI_zWmq/view" target="_blank" rel="noopener" class="d-format">PDF · A5 landscape ↗</a>
    </div>
    <div class="deliverable-card">
      <span class="d-type">Process Document</span>
      <a href="https://docs.google.com/document/d/17CZSkVAfwg-zaez_SZqll8CWF83pkjki/edit" target="_blank" rel="noopener" class="d-format">Word · ID Portfolio ↗</a>
    </div>
    <div class="deliverable-card">
      <span class="d-type">Slide Layout Reference</span>
      <span class="d-format">HTML · Visual design guide</span>
    </div>
  </div>
</div>

<div class="port-section">
  <span class="port-section-label">Reflection</span>
  <div class="reflection-block">
    <p>The part of this project I'm most satisfied with is the quiz. It would have been easier to accept Rise's native functionality. It was better to build around it — and the result is a more honest learning interaction.</p>
    <p>If I were to revisit this, I'd push for structured call observation before the framework design phase. The HEARD framework works well — but direct data from real coordinator calls would sharpen the scenario writing and the wrong-path feedback considerably. That's the gap between a well-designed course and a precisely calibrated one.</p>
  </div>
  <div class="closing-quote">
    <p>A parent who feels heard rarely asks for a refund.<br>A coordinator who knows HEARD rarely needs to offer one.</p>
  </div>
</div>
