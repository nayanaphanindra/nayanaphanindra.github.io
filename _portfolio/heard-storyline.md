---
layout: portfolio_item
title: "When It All Goes Wrong"
type: "Portfolio · Instructional Design"
tools: "Articulate Storyline 360"
year: "2025"
excerpt: "A branching scenario module for academic coordinators at an edtech provider — built to simulate high-stakes parent calls under pressure."
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
  font-size: 0.93rem;
  color: var(--ink-soft);
  line-height: 1.8;
  margin: 0;
}
.course-snapshot {
  background: #1a1a2e;
  border-radius: 8px;
  overflow: hidden;
  margin: 1.5rem 0;
}
.snapshot-topbar {
  background: #111128;
  padding: 0.6rem 1.25rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.snapshot-topbar span {
  font-size: 0.78rem;
  color: rgba(255,255,255,0.4);
  letter-spacing: 0.08em;
  font-family: sans-serif;
}
.snapshot-img-wrap {
  position: relative;
  background: #111128;
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 320px;
  padding: 2rem;
}
.snapshot-card {
  background: rgba(255,255,255,0.93);
  border-radius: 6px;
  padding: 2.5rem 2rem;
  max-width: 360px;
  text-align: center;
  box-shadow: 0 8px 40px rgba(0,0,0,0.4);
}
.snapshot-card .sc-label {
  font-size: 0.72rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #4a5568;
  margin-bottom: 0.75rem;
  font-family: sans-serif;
}
.snapshot-card h2 {
  font-family: 'Cormorant Garamond', Georgia, serif;
  font-size: 1.9rem;
  font-weight: 700;
  color: #0d1f3c;
  line-height: 1.2;
  margin-bottom: 0.75rem;
}
.snapshot-card .sc-sub {
  font-size: 0.88rem;
  color: #4a5568;
  margin-bottom: 0.5rem;
  font-family: sans-serif;
}
.snapshot-card .sc-meta {
  font-size: 0.8rem;
  color: #718096;
  margin-bottom: 1.5rem;
  font-family: sans-serif;
}
.snapshot-btn {
  display: inline-block;
  background: #0d1f3c;
  color: #fff;
  padding: 0.65rem 2rem;
  border-radius: 30px;
  font-size: 0.9rem;
  font-family: sans-serif;
  font-weight: 600;
}
.snapshot-caption {
  padding: 0.75rem 1.25rem;
  background: #111128;
  font-size: 0.78rem;
  color: rgba(255,255,255,0.35);
  font-family: sans-serif;
  font-style: italic;
}
.reflection-block {
  background: var(--paper-2);
  border-left: 4px solid var(--accent);
  padding: 1.5rem 2rem;
  border-radius: 0 4px 4px 0;
  margin-bottom: 1.5rem;
}
.reflection-block p {
  font-size: 0.98rem;
  line-height: 1.85;
  color: var(--ink-soft);
  margin: 0 0 1rem 0;
}
.reflection-block p:last-child { margin: 0; }
.closing-quote {
  background: #0d1f3c;
  border-radius: 6px;
  padding: 2.5rem 2.5rem;
  margin-top: 2rem;
  text-align: center;
}
.closing-quote p {
  font-family: 'Cormorant Garamond', Georgia, serif;
  font-size: 1.25rem;
  font-style: italic;
  color: rgba(255,255,255,0.88);
  line-height: 1.75;
  margin: 0;
  max-width: none;
}
@media (max-width: 640px) {
  .process-grid { grid-template-columns: 1fr; }
  .port-hero-band { margin: -1rem -0.5rem 2rem; padding: 2.5rem 1.25rem 2rem; }
}
</style>

<div class="port-hero-band">
  <span class="port-type">Portfolio · Instructional Design</span>
  <h1>When It All Goes Wrong</h1>
  <p class="port-subtitle">A branching scenario module for academic coordinators at an edtech provider — built to simulate high-stakes parent calls under pressure.</p>
</div>

<div class="port-section">
  <span class="port-section-label">The Brief</span>
  <p>Academic coordinators at edtech companies are the first point of contact when something goes wrong. With board exams three weeks away, a parent discovers her son's tutor taught the wrong syllabus all term. The coordinator has 10 minutes to de-escalate, commit to a plan, and close the call with trust intact.</p>
  <p>The brief: build a short scenario that puts coordinators inside that call — not just reading about it.</p>
</div>

<div class="port-section">
  <span class="port-section-label">The Challenge</span>
  <p>Most customer-handling training tells people what to do. It doesn't make them practise doing it under pressure, with a distressed parent waiting for an answer.</p>
  <p>The design challenge was to create a simulation realistic enough to feel uncomfortable — and structured enough that the feedback actually teaches something when a choice goes wrong.</p>
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
      <p>Developed the application of the framework to this situation. Simulation demonstration as a complement to the previously developed Rise 360 Module.</p>
    </div>
    <div class="process-step">
      <span class="step-number">03 – Development</span>
      <h3>Articulate Storyline</h3>
      <p>A sample of Storyline branching scenario built to simulate the pressure of a live parent call with three high-stakes decision points.</p>
    </div>
    <div class="process-step">
      <span class="step-number">04 – Review</span>
      <h3>Storyboard-first workflow</h3>
      <p>Model storyboard produced before final production to validate the branching logic and feedback language with stakeholders.</p>
    </div>
  </div>
</div>

<div class="port-section">
  <img src="/assets/images/heard-storyline.png" />
  <span class="port-section-label">A Snapshot of the Course</span>
  <div class="course-snapshot"><div class="port-section">
  <span class="port-section-label">A Snapshot of the Course</span>
  <p style="margin-bottom:1rem;">Click on the course screenshot to view a snapshot.</p>
  <div class="course-snapshot">
    <div class="snapshot-topbar">
      <span>≡ &nbsp; microlearning · articulate rise 360</span>
      <span>8 min · HEARD framework</span>
    </div>
    <a href="https://nayanapsychologist-spec.github.io/heard-training/" target="_blank" rel="noopener" class="snapshot-img-wrap">
      <img src="/assets/images/heard-rise.png" alt="HEARD Framework — Rise 360 course preview" />
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
    <div class="snapshot-caption">Click on the course screenshot to access it</div>
  </div>
</div>

<div class="port-section">
  <span class="port-section-label">Reflection</span>
  <div class="reflection-block">
    <p>The hardest part of this project wasn't the branching logic or the script — it was the slides. Storyline's "blank canvas" is total freedom until you're staring at a misaligned text box, wondering why it doesn't match your vision. Getting the layout right — consistent spacing, character placement, and button styling — required more iteration than any other part of the build.</p>
    <p>I realised that small details, like a 4px corner radius versus a pill-shaped button, significantly impact the learner's immersion. If I were to do this again, I'd nail the visual details of a single "master" slide before duplicating. Building structure first and styling later forced me to revisit alignment decisions far too many times.</p>
  </div>
  <div class="closing-quote">
    <p>Visual design in e-learning isn't decoration.<br>It's the difference between a course that feels credible<br>and one that feels like a draft.</p>
  </div>
</div>
