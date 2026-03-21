---
layout: portfolio_item
title: "Clear to Board"
type: "Portfolio · Instructional Design"
tools: "HTML / CSS / JS · Articulate Storyline 360"
year: "2025"
excerpt: "A performance-based compliance simulation for Port State Control Officers — designed to bridge the gap between knowing a maritime regulation and executing a judgment under pressure."
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
.port-section h2 {
  font-family: 'Cormorant Garamond', Georgia, serif;
  font-size: 1.75rem;
  font-weight: 400;
  color: var(--ink);
  margin-bottom: 1rem;
  line-height: 1.3;
}
.port-section p {
  font-size: 1rem;
  line-height: 1.85;
  color: var(--ink-soft);
  margin-bottom: 1rem;
  max-width: none;
}
.port-section p strong { color: var(--ink); font-weight: 600; }
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
.insight-block {
  background: #0d1f3c;
  border-radius: 6px;
  padding: 2rem 2.25rem;
  margin: 1.5rem 0;
}
.insight-block p {
  font-family: 'Cormorant Garamond', Georgia, serif;
  font-size: 1.15rem;
  font-style: italic;
  color: rgba(255,255,255,0.88);
  line-height: 1.8;
  margin: 0;
  max-width: none;
}
.insight-block p strong {
  color: #5dcaa5;
  font-style: normal;
  font-weight: 600;
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
.appendix-item {
  padding: 1.25rem 1.5rem;
  border: 1.5px solid var(--line);
  border-radius: 4px;
  background: var(--paper);
  margin-bottom: 1rem;
  transition: border-color 0.2s;
}
.appendix-item:hover { border-color: var(--accent); }
.appendix-item .a-num {
  font-size: 0.72rem;
  font-weight: 800;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 0.4rem;
  display: block;
}
.appendix-item h3 {
  font-family: var(--font-sans, sans-serif);
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 0.4rem;
  line-height: 1.4;
}
.appendix-item p {
  font-size: 0.88rem;
  color: var(--ink-soft);
  line-height: 1.7;
  margin-bottom: 0.5rem;
}
.appendix-item a {
  font-size: 0.8rem;
  color: var(--accent);
  font-weight: 600;
  word-break: break-all;
  text-decoration: underline;
  text-underline-offset: 2px;
}
.closing-quote {
  background: #0d1f3c;
  border-radius: 6px;
  padding: 2.5rem;
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
  .proto-frame iframe { height: 400px; }
}
</style>

<div class="port-hero-band">
  <span class="port-type">Portfolio · Instructional Design</span>
  <h1>Clear to Board</h1>
  <p class="port-subtitle">A performance-based compliance simulation for Port State Control Officers — designed to bridge the gap between knowing a maritime regulation and executing a judgment under pressure.</p>
</div>


<div class="port-section">
  <span class="port-section-label">The Problem</span>
  <p>Test paragraph.</p>
</div>


<div class="port-section">
  <span class="port-section-label">The Problem</span>
  <p>Most compliance training is designed for the trainer's convenience, not the learner's performance.</p>
  <p>We have all seen it: a 20-slide deck followed by a five-question quiz. If the learner can recognise the correct answer written in plain English, we check a box and say they are trained. But recognition is not the same as application. In the real world, there are no multiple-choice bubbles floating over a hazard.</p>
  <p>For a Port State Control Officer, the task is not reciting SOLAS II-2 or MARPOL regulations. It is spotting a violation on a noisy, crowded deck with four minutes on the clock before a ship is cleared to sail.</p>
  <div class="insight-block">
    <p>Traditional eLearning conflates these tasks. <strong>Knowing a rule and executing a judgment under pressure are not the same skill.</strong> The design has to treat them differently.</p>
  </div>
</div>

<div class="port-section">
  <span class="port-section-label">Design Approach</span>
  <h2>Anchored to one question: what does the learner need to DO?</h2>
  <p>The specific performance requirement is: observe, judge, and decide within a time constraint that mirrors the real job. Every design decision flows from that requirement.</p>
  <div class="process-grid">
    <div class="process-step">
      <span class="step-number">Octalysis — Core Drive 6</span>
      <h3>Scarcity and Impatience</h3>
      <p>The 4-minute mission timer simulates the cognitive load of a real inspection. If you cannot find the violation under pressure, you are not yet ready for the real task.</p>
    </div>
    <div class="process-step">
      <span class="step-number">Octalysis — Core Drive 1</span>
      <h3>Epic Meaning and Calling</h3>
      <p>The learner is not a student. They are a Port Officer ensuring vessel safety. Every Clear or Flag decision carries the weight of a real-world consequence.</p>
    </div>
  </div>
  <p style="margin-top:2rem;">One design decision worth flagging explicitly: <strong>the timer is not rewarding speed. It is replicating pressure.</strong> Those are different things, and the scoring logic reflects that distinction.</p>
  <p>A learner who finishes in two minutes but misses one active violation receives an automatic Detained outcome regardless of their other correct calls. In high-stakes compliance, partial accuracy does not offset a missed safety deficiency.</p>
</div>

<div class="port-section">
  <span class="port-section-label">Build Decisions</span>
  <h2>Architecture over artifact: why I prototyped in code first</h2>
  <p>I chose to hand-code this project in HTML/CSS/JS as a functional prototype before moving to Articulate Storyline 360 for SCORM-compliant production.</p>
  <p>The reason: I needed to validate the consequence logic before investing in production. Building the logic-test first meant I could confirm the decision-making flow was sound before touching the authoring tool.</p>
  <p>The HTML prototype also served a second purpose: it is the demo artefact itself. It runs in any browser, requires no LMS, no Storyline licence, no SCORM player. For a portfolio piece shown in a live conversation, that is a feature, not a workaround.</p>
  <a href="https://drive.google.com/file/d/1eWqngdlwOAUBupK_ra6EfjsTm0gdjITv/view?usp=sharing" target="_blank" rel="noopener" class="card-link">View full design document and Octalysis mapping (PDF) →</a>
</div>

<div class="port-section">
  <span class="port-section-label">Try the Prototype</span>
  <p>Click the image below to launch the live simulation in a new tab.</p>
  <a href="https://nayanaphanindra.github.io/prototype/clear-to-board.html" target="_blank" rel="noopener" style="display:block;border:1.5px solid var(--line);border-radius:8px;overflow:hidden;margin:1.5rem 0;text-decoration:none;">
    <div style="background:#0d1f3c;padding:0.65rem 1.25rem;display:flex;align-items:center;justify-content:space-between;">
      <span style="font-size:0.78rem;color:rgba(255,255,255,0.45);font-family:sans-serif;">clear to board · html/css/js prototype</span>
      <span style="font-size:0.78rem;color:rgba(255,255,255,0.45);font-family:sans-serif;">4 min · port state control simulation</span>
    </div>
    <img src="/assets/images/clear-to-board-preview.png" alt="Clear to Board prototype preview" style="width:100%;display:block;" />
    <div style="background:#0d1f3c;padding:0.85rem 1.25rem;display:flex;align-items:center;justify-content:space-between;">
      <span style="font-size:0.78rem;color:rgba(255,255,255,0.38);font-family:sans-serif;font-style:italic;">Click to launch the simulation in a new tab</span>
      <span style="font-size:0.75rem;color:#5dcaa5;font-family:sans-serif;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;">Launch →</span>
    </div>
  </a>
</div>

<div class="port-section">
  <span class="port-section-label">The Vision</span>
  <h2>From snippet to system</h2>
  <p>The current demo is a standalone performance test. The full architecture is designed to lead into a Captain's Debrief — instead of a percentage score, learners receive a detailed breakdown of their professional judgment, mapping hits and misses directly back to the specific regulations they will apply on the job.</p>
  <p>This is how I approach every project: big-picture performance first, tool selection second. If the content does not help a learner do something differently tomorrow, it does not belong in the course today.</p>
</div>

<div class="port-section">
  <span class="port-section-label">Behind the Build</span>
  <h2>Designing without SME access</h2>
  <p>Here is the part most portfolio pieces leave out.</p>
  <p>I had no maritime background and no subject matter expert to consult when I started this project. I had never been on a cargo vessel, and could not have told you the difference between SOLAS and MARPOL before this build began. This is the no-SME-access challenge — you need enough subject matter credibility to design meaningfully, but no practitioner to interview, validate against, or challenge your assumptions.</p>
  <p>This is not a limitation unique to this project. It is the normal condition of much ID work. The skill is not knowing everything — it is knowing how to get to <strong>enough</strong>, responsibly.</p>
  <div class="reflection-block">
    <p><strong>Sourcing the regulations</strong> — I started with three primary sources chosen deliberately. The SafetyCulture PSC checklist told me where violations actually cluster in practice. The Nautilus Shipping PSC guide gave me the inspector's workflow — documents first, then physical inspection — which became the three-zone structure of the module. A real Washington State government inspection document gave me the specific, nameable violations that make the debrief consequence statements feel credible rather than invented.</p>
    <p><strong>Where AI came in</strong> — Once I had the source documents, I used Claude as a research processing tool. Maritime regulations are dense and cross-referenced. What would have taken days of solo reading took hours: I fed in the source material, asked targeted questions about specific regulation clauses, and used the responses to build a violation map.</p>
    <p><strong>What AI did and did not do</strong> — It processed and synthesised content I had already identified and verified as credible. It did not source the regulations — I did that. It did not make design decisions — I did that. What it did was compress the time between having a pile of complex documents and having a structured content map to build from.</p>
    <p><strong>How I validated</strong> — Every regulation reference AI surfaced, I cross-checked against the original source documents before it went into the module. Every consequence statement was checked for plausibility. The validation step is where instructional design discipline matters most when using AI as a research tool.</p>
  </div>
  <p>Working without SME access and being honest about it is a stronger position than pretending expertise you do not have. It is also closer to how most of us actually work.</p>
</div>

<div class="port-section">
  <span class="port-section-label">Appendix</span>
  <h2>Source documents</h2>
  <p>All primary reference material used during content development. All publicly available.</p>
  <div class="appendix-item">
    <span class="a-num">Source 01</span>
    <h3>SafetyCulture — Port State Control Inspection Checklist</h3>
    <p>Structured inventory of most commonly cited deficiency categories — fire safety, lifesaving equipment, documentation, ISM compliance.</p>
    <a href="https://safetyculture.com/checklists/port-state-control-psc-inspection" target="_blank" rel="noopener">safetyculture.com — PSC Inspection Checklist →</a>
  </div>
  <div class="appendix-item">
    <span class="a-num">Source 02</span>
    <h3>Nautilus Shipping — Understanding Port State Control</h3>
    <p>Overview of the PSC inspection process including the standard sequence which formed the structural basis for the three-zone module design.</p>
    <a href="https://www.nautilusshipping.com/news-and-insights/understanding-port-state-control-psc-keeping-ships-safe-and-compliant" target="_blank" rel="noopener">nautilusshipping.com — Understanding PSC →</a>
  </div>
  <div class="appendix-item">
    <span class="a-num">Source 03</span>
    <h3>Washington State Dept. of Ecology — Vessel Boarding Checklist</h3>
    <p>Real government inspection document used to ground violation types and consequence statements in actual regulatory language.</p>
    <a href="https://apps.ecology.wa.gov/publications/documents/ecy05038.pdf" target="_blank" rel="noopener">apps.ecology.wa.gov — ecy05038.pdf →</a>
  </div>
  <div class="appendix-item">
    <span class="a-num">Source 04</span>
    <h3>International Maritime Organization — Port State Control Overview</h3>
    <p>IMO overview of the PSC regime, covering the regulatory framework and conventions PSC officers inspect against.</p>
    <a href="https://www.imo.org/en/OurWork/IIIS/Pages/Port%20State%20Control.aspx" target="_blank" rel="noopener">imo.org — Port State Control →</a>
  </div>
  <div class="closing-quote">
    <p>If the content does not help a learner do something differently tomorrow,<br>it does not belong in the course today.</p>
  </div>
</div>
