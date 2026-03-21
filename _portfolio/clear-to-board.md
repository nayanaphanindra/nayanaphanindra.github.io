---
layout: portfolio_item
title: "Clear to Board"
type: "Portfolio · Instructional Design"
tools: "HTML / CSS / JS · Articulate Storyline 360"
year: "2025"
excerpt: "A performance-based compliance simulation for Port State Control Officers — designed to bridge the gap between knowing a maritime regulation and executing a judgment under pressure."
---

<div style="background:#0d1f3c;margin:-2rem -1rem 3rem -1rem;padding:3.5rem 2rem 3rem;border-radius:4px;">
  <span style="font-size:0.78rem;font-weight:700;letter-spacing:0.14em;text-transform:uppercase;color:#5dcaa5;margin-bottom:1rem;display:block;">Portfolio · Instructional Design</span>
  <h1 style="font-family:'Cormorant Garamond',Georgia,serif;font-size:clamp(2.2rem,5vw,3.5rem);font-weight:700;color:#fff;line-height:1.15;margin-bottom:1.25rem;">Clear to Board</h1>
  <p style="font-size:1rem;color:rgba(255,255,255,0.65);font-style:italic;line-height:1.7;max-width:60ch;margin:0;">A performance-based compliance simulation for Port State Control Officers — designed to bridge the gap between knowing a maritime regulation and executing a judgment under pressure.</p>
</div>

<div style="margin-bottom:3.5rem;padding-bottom:3.5rem;border-bottom:1px solid var(--line);">
  <span style="font-size:0.75rem;font-weight:800;letter-spacing:0.18em;text-transform:uppercase;color:var(--accent);margin-bottom:1.5rem;display:block;">The Problem</span>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1rem;">Most compliance training is designed for the trainer's convenience, not the learner's performance.</p>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1rem;">We have all seen it: a 20-slide deck followed by a five-question quiz. If the learner can recognise the correct answer written in plain English, we check a box and say they are trained. But recognition is not the same as application. In the real world, there are no multiple-choice bubbles floating over a hazard.</p>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1.5rem;">For a Port State Control Officer, the task is not reciting SOLAS II-2 or MARPOL regulations. It is spotting a violation on a noisy, crowded deck with four minutes on the clock before a ship is cleared to sail.</p>
  <div style="background:#0d1f3c;border-radius:6px;padding:2rem 2.25rem;margin:1.5rem 0;">
    <p style="font-family:'Cormorant Garamond',Georgia,serif;font-size:1.15rem;font-style:italic;color:rgba(255,255,255,0.88);line-height:1.8;margin:0;">Traditional eLearning conflates these tasks. <strong style="color:#5dcaa5;font-style:normal;font-weight:600;">Knowing a rule and executing a judgment under pressure are not the same skill.</strong> The design has to treat them differently.</p>
  </div>
</div>

<div style="margin-bottom:3.5rem;padding-bottom:3.5rem;border-bottom:1px solid var(--line);">
  <span style="font-size:0.75rem;font-weight:800;letter-spacing:0.18em;text-transform:uppercase;color:var(--accent);margin-bottom:1.5rem;display:block;">Design Approach</span>
  <h2 style="font-family:'Cormorant Garamond',Georgia,serif;font-size:1.75rem;font-weight:400;color:var(--ink);margin-bottom:1rem;line-height:1.3;">Anchored to one question: what does the learner need to DO?</h2>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1.5rem;">The specific performance requirement is: observe, judge, and decide — within a time constraint that mirrors the real job. Every design decision flows from that requirement.</p>
  <div style="display:grid;grid-template-columns:1fr 1fr;gap:2rem;margin-top:1.5rem;">
    <div style="padding:1.75rem;border:1.5px solid var(--line);border-radius:4px;background:var(--paper-2);">
      <span style="font-size:0.7rem;font-weight:800;letter-spacing:0.16em;text-transform:uppercase;color:var(--accent);margin-bottom:0.6rem;display:block;">Octalysis — Core Drive 6</span>
      <h3 style="font-size:1rem;font-weight:700;color:var(--ink);margin-bottom:0.75rem;line-height:1.4;">Scarcity and Impatience</h3>
      <p style="font-size:0.93rem;color:var(--ink-soft);line-height:1.8;margin:0;">The 4-minute mission timer simulates the cognitive load of a real inspection. If you cannot find the violation under pressure, you are not yet ready for the real task.</p>
    </div>
    <div style="padding:1.75rem;border:1.5px solid var(--line);border-radius:4px;background:var(--paper-2);">
      <span style="font-size:0.7rem;font-weight:800;letter-spacing:0.16em;text-transform:uppercase;color:var(--accent);margin-bottom:0.6rem;display:block;">Octalysis — Core Drive 1</span>
      <h3 style="font-size:1rem;font-weight:700;color:var(--ink);margin-bottom:0.75rem;line-height:1.4;">Epic Meaning and Calling</h3>
      <p style="font-size:0.93rem;color:var(--ink-soft);line-height:1.8;margin:0;">The learner is not a student. They are a Port Officer ensuring vessel safety. Every Clear or Flag decision carries the weight of a real-world consequence.</p>
    </div>
  </div>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-top:2rem;margin-bottom:1rem;">One design decision worth flagging explicitly: <strong style="color:var(--ink);font-weight:600;">the timer is not rewarding speed. It is replicating pressure.</strong> Those are different things, and the scoring logic reflects that distinction.</p>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);">A learner who finishes in two minutes but misses one active violation receives an automatic Detained outcome — regardless of their other correct calls. In high-stakes compliance, partial accuracy does not offset a missed safety deficiency.</p>
</div>

<div style="margin-bottom:3.5rem;padding-bottom:3.5rem;border-bottom:1px solid var(--line);">
  <span style="font-size:0.75rem;font-weight:800;letter-spacing:0.18em;text-transform:uppercase;color:var(--accent);margin-bottom:1.5rem;display:block;">Build Decisions</span>
  <h2 style="font-family:'Cormorant Garamond',Georgia,serif;font-size:1.75rem;font-weight:400;color:var(--ink);margin-bottom:1rem;line-height:1.3;">Architecture over artifact: why I prototyped in code first</h2>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1rem;">I chose to hand-code this project in HTML/CSS/JS as a functional prototype before moving to Articulate Storyline 360 for SCORM-compliant production.</p>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1rem;">The reason: I needed to validate the consequence logic — the brain of the simulation — before investing in production. Building the logic-test first meant I could confirm the decision-making flow was sound before touching the authoring tool.</p>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1.5rem;">The HTML prototype also served a second purpose: it is the demo artefact itself. It runs in any browser, requires no LMS, no Storyline licence, no SCORM player. For a portfolio piece shown in a live conversation, that is a feature, not a workaround.</p>
  <a href="https://drive.google.com/file/d/1eWqngdlwOAUBupK_ra6EfjsTm0gdjITv/view?usp=sharing" target="_blank" rel="noopener" style="font-size:0.82rem;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:var(--accent);border-bottom:2px solid var(--accent-lt);padding-bottom:2px;text-decoration:none;margin-top:1rem;display:inline-block;">View full design document and Octalysis mapping (PDF) →</a>
</div>

<div style="margin-bottom:3.5rem;padding-bottom:3.5rem;border-bottom:1px solid var(--line);">
  <span style="font-size:0.75rem;font-weight:800;letter-spacing:0.18em;text-transform:uppercase;color:var(--accent);margin-bottom:1.5rem;display:block;">Try the Prototype</span>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1.5rem;">The simulation runs directly below. Launch it to experience the inspection scenario — or open it fullscreen for the intended experience.</p>
  <div style="border:1.5px solid var(--line);border-radius:8px;overflow:hidden;margin:1.5rem 0;">
    <div style="background:#0d1f3c;padding:0.65rem 1.25rem;display:flex;align-items:center;justify-content:space-between;">
      <span style="font-size:0.78rem;color:rgba(255,255,255,0.45);letter-spacing:0.06em;font-family:sans-serif;">clear to board · html/css/js prototype</span>
      <span style="font-size:0.78rem;color:rgba(255,255,255,0.45);font-family:sans-serif;">4 min · port state control simulation</span>
    </div>
    <div id="ctb-collapsed" style="display:flex;align-items:center;justify-content:space-between;padding:1.25rem 1.5rem;background:var(--paper-2);gap:1rem;">
      <div style="font-size:0.95rem;color:var(--ink-soft);line-height:1.6;">
        <strong style="color:var(--ink);font-weight:600;">Clear to Board — Live Prototype</strong><br>
        A deck inspection simulation. Find the violations before time runs out.
      </div>
      <button onclick="document.getElementById('ctb-collapsed').style.display='none';document.getElementById('ctb-frame').style.display='block';" style="background:var(--accent);color:#fff;font-size:0.78rem;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;padding:0.6rem 1.25rem;border-radius:4px;border:none;cursor:pointer;font-family:sans-serif;white-space:nowrap;">Launch simulation →</button>
    </div>
    <div id="ctb-frame" style="display:none;">
      <iframe src="https://nayanaphanindra.github.io/prototype/clear-to-board.html" title="Clear to Board simulation" allowfullscreen style="width:100%;height:560px;border:none;display:block;"></iframe>
      <div style="background:#0d1f3c;padding:0.6rem 1.25rem;display:flex;align-items:center;justify-content:space-between;gap:1rem;">
        <span style="font-size:0.75rem;color:rgba(255,255,255,0.35);font-family:sans-serif;font-style:italic;">Experiencing issues? Try fullscreen for best results.</span>
        <div style="display:flex;gap:0.5rem;">
          <button onclick="document.getElementById('ctb-fs').style.display='flex';document.getElementById('ctb-fs-iframe').src='https://nayanaphanindra.github.io/prototype/clear-to-board.html';document.body.style.overflow='hidden';" style="background:none;border:1px solid rgba(255,255,255,0.2);color:rgba(255,255,255,0.6);font-size:0.72rem;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;padding:0.35rem 0.85rem;border-radius:4px;cursor:pointer;font-family:sans-serif;">Fullscreen</button>
          <button onclick="document.getElementById('ctb-frame').style.display='none';document.getElementById('ctb-collapsed').style.display='flex';" style="background:none;border:1px solid rgba(255,255,255,0.2);color:rgba(255,255,255,0.6);font-size:0.72rem;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;padding:0.35rem 0.85rem;border-radius:4px;cursor:pointer;font-family:sans-serif;">Collapse</button>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="ctb-fs" style="display:none;position:fixed;top:0;left:0;right:0;bottom:0;z-index:9999;background:#0d1f3c;flex-direction:column;">
  <div style="background:#0a1829;padding:0.65rem 1.5rem;display:flex;align-items:center;justify-content:space-between;flex-shrink:0;">
    <span style="font-size:0.78rem;color:rgba(255,255,255,0.45);font-family:sans-serif;">Clear to Board · Port State Control Simulation</span>
    <button onclick="document.getElementById('ctb-fs').style.display='none';document.getElementById('ctb-fs-iframe').src='';document.body.style.overflow='';" style="background:none;border:1px solid rgba(255,255,255,0.2);color:rgba(255,255,255,0.6);font-size:0.72rem;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;padding:0.35rem 0.85rem;border-radius:4px;cursor:pointer;font-family:sans-serif;">Exit Fullscreen</button>
  </div>
  <iframe id="ctb-fs-iframe" src="" title="Clear to Board fullscreen" allowfullscreen style="flex:1;width:100%;border:none;"></iframe>
</div>

<div style="margin-bottom:3.5rem;padding-bottom:3.5rem;border-bottom:1px solid var(--line);">
  <span style="font-size:0.75rem;font-weight:800;letter-spacing:0.18em;text-transform:uppercase;color:var(--accent);margin-bottom:1.5rem;display:block;">The Vision</span>
  <h2 style="font-family:'Cormorant Garamond',Georgia,serif;font-size:1.75rem;font-weight:400;color:var(--ink);margin-bottom:1rem;line-height:1.3;">From snippet to system</h2>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1rem;">The current demo is a standalone performance test. The full architecture is designed to lead into a Captain's Debrief — instead of a percentage score, learners receive a detailed breakdown of their professional judgment, mapping hits and misses directly back to the specific regulations they will apply on the job.</p>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);">This is how I approach every project: big-picture performance first, tool selection second. If the content does not help a learner do something differently tomorrow, it does not belong in the course today.</p>
</div>

<div style="margin-bottom:3.5rem;padding-bottom:3.5rem;border-bottom:1px solid var(--line);">
  <span style="font-size:0.75rem;font-weight:800;letter-spacing:0.18em;text-transform:uppercase;color:var(--accent);margin-bottom:1.5rem;display:block;">Behind the Build</span>
  <h2 style="font-family:'Cormorant Garamond',Georgia,serif;font-size:1.75rem;font-weight:400;color:var(--ink);margin-bottom:1rem;line-height:1.3;">Designing without SME access</h2>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1rem;">Here is the part most portfolio pieces leave out.</p>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1rem;">I had no maritime background and no subject matter expert to consult when I started this project. I had never been on a cargo vessel, and could not have told you the difference between SOLAS and MARPOL before this build began. This is the no-SME-access challenge — you need enough subject matter credibility to design meaningfully, but no practitioner to interview, validate against, or challenge your assumptions.</p>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1.5rem;">This is not a limitation unique to this project. It is the normal condition of much ID work. The skill is not knowing everything — it is knowing how to get to <strong style="color:var(--ink);font-weight:600;">enough</strong>, responsibly.</p>
  <div style="background:var(--paper-2);border-left:4px solid var(--accent);padding:1.5rem 2rem;border-radius:0 4px 4px 0;margin-bottom:1.5rem;">
    <p style="font-size:0.98rem;line-height:1.85;color:var(--ink-soft);margin:0 0 1rem 0;"><strong style="color:var(--ink);font-weight:600;">Sourcing the regulations</strong> — I started with three primary sources chosen deliberately. The SafetyCulture PSC checklist told me where violations actually cluster in practice. The Nautilus Shipping PSC guide gave me the inspector's workflow — documents first, then physical inspection — which became the three-zone structure of the module. A real Washington State government inspection document gave me the specific, nameable violations that make the debrief consequence statements feel credible rather than invented.</p>
    <p style="font-size:0.98rem;line-height:1.85;color:var(--ink-soft);margin:0 0 1rem 0;"><strong style="color:var(--ink);font-weight:600;">Where AI came in</strong> — Once I had the source documents, I used Claude as a research processing tool. Maritime regulations are dense and cross-referenced. What would have taken days of solo reading took hours: I fed in the source material, asked targeted questions about specific regulation clauses, and used the responses to build a violation map — each item paired with its regulation reference, visual manifestation on a vessel, and real-world consequence if missed.</p>
    <p style="font-size:0.98rem;line-height:1.85;color:var(--ink-soft);margin:0 0 1rem 0;"><strong style="color:var(--ink);font-weight:600;">What AI did and did not do</strong> — It processed and synthesised content I had already identified and verified as credible. It did not source the regulations — I did that. It did not make design decisions — I did that. What it did was compress the time between having a pile of complex documents and having a structured content map to build from.</p>
    <p style="font-size:0.98rem;line-height:1.85;color:var(--ink-soft);margin:0;"><strong style="color:var(--ink);font-weight:600;">How I validated</strong> — Every regulation reference AI surfaced, I cross-checked against the original source documents before it went into the module. Every consequence statement was checked for plausibility. The validation step is where instructional design discipline matters most when using AI as a research tool. AI can surface content at speed; it cannot guarantee accuracy at the level of specificity that a real inspection consequence requires. The designer has to own that responsibility.</p>
  </div>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);">Working without SME access and being honest about it is a stronger position than pretending expertise you do not have. It is also closer to how most of us actually work.</p>
</div>

<div style="margin-bottom:3.5rem;padding-bottom:3.5rem;border-bottom:1px solid var(--line);">
  <span style="font-size:0.75rem;font-weight:800;letter-spacing:0.18em;text-transform:uppercase;color:var(--accent);margin-bottom:1.5rem;display:block;">Appendix</span>
  <h2 style="font-family:'Cormorant Garamond',Georgia,serif;font-size:1.75rem;font-weight:400;color:var(--ink);margin-bottom:1rem;line-height:1.3;">Source documents</h2>
  <p style="font-size:1rem;line-height:1.85;color:var(--ink-soft);margin-bottom:1.5rem;">All primary reference material used during content development. All publicly available.</p>
  <div style="padding:1.25rem 1.5rem;border:1.5px solid var(--line);border-radius:4px;background:var(--paper);margin-bottom:1rem;">
    <span style="font-size:0.72rem;font-weight:800;letter-spacing:0.14em;text-transform:uppercase;color:var(--accent);margin-bottom:0.4rem;display:block;">Source 01</span>
    <h3 style="font-size:0.95rem;font-weight:700;color:var(--ink);margin-bottom:0.4rem;line-height:1.4;">SafetyCulture — Port State Control (PSC) Inspection Checklist</h3>
    <p style="font-size:0.88rem;color:var(--ink-soft);line-height:1.7;margin-bottom:0.5rem;">Structured inventory of most commonly cited deficiency categories in PSC inspections — fire safety, lifesaving equipment, documentation, ISM compliance.</p>
    <a href="https://safetyculture.com/checklists/port-state-control-psc-inspection" target="_blank" rel="noopener" style="font-size:0.8rem;color:var(--accent);font-weight:600;text-decoration:underline;">safetyculture.com — PSC Inspection Checklist →</a>
  </div>
  <div style="padding:1.25rem 1.5rem;border:1.5px solid var(--line);border-radius:4px;background:var(--paper);margin-bottom:1rem;">
    <span style="font-size:0.72rem;font-weight:800;letter-spacing:0.14em;text-transform:uppercase;color:var(--accent);margin-bottom:0.4rem;display:block;">Source 02</span>
    <h3 style="font-size:0.95rem;font-weight:700;color:var(--ink);margin-bottom:0.4rem;line-height:1.4;">Nautilus Shipping — Understanding Port State Control</h3>
    <p style="font-size:0.88rem;color:var(--ink-soft);line-height:1.7;margin-bottom:0.5rem;">Overview of the PSC inspection process including the standard sequence — document review followed by physical walkthrough — which formed the structural basis for the three-zone module design.</p>
    <a href="https://www.nautilusshipping.com/news-and-insights/understanding-port-state-control-psc-keeping-ships-safe-and-compliant" target="_blank" rel="noopener" style="font-size:0.8rem;color:var(--accent);font-weight:600;text-decoration:underline;">nautilusshipping.com — Understanding PSC →</a>
  </div>
  <div style="padding:1.25rem 1.5rem;border:1.5px solid var(--line);border-radius:4px;background:var(--paper);margin-bottom:1rem;">
    <span style="font-size:0.72rem;font-weight:800;letter-spacing:0.14em;text-transform:uppercase;color:var(--accent);margin-bottom:0.4rem;display:block;">Source 03</span>
    <h3 style="font-size:0.95rem;font-weight:700;color:var(--ink);margin-bottom:0.4rem;line-height:1.4;">Washington State Dept. of Ecology — Cargo and Passenger Vessel Boarding Checklist</h3>
    <p style="font-size:0.88rem;color:var(--ink-soft);line-height:1.7;margin-bottom:0.5rem;">Real government inspection document covering crew certification, STCW, deck condition, fire safety, environmental compliance. Used to ground violation types and consequence statements in actual regulatory language.</p>
    <a href="https://apps.ecology.wa.gov/publications/documents/ecy05038.pdf" target="_blank" rel="noopener" style="font-size:0.8rem;color:var(--accent);font-weight:600;text-decoration:underline;">apps.ecology.wa.gov — ecy05038.pdf →</a>
  </div>
  <div style="padding:1.25rem 1.5rem;border:1.5px solid var(--line);border-radius:4px;background:var(--paper);margin-bottom:1rem;">
    <span style="font-size:0.72rem;font-weight:800;letter-spacing:0.14em;text-transform:uppercase;color:var(--accent);margin-bottom:0.4rem;display:block;">Source 04</span>
    <h3 style="font-size:0.95rem;font-weight:700;color:var(--ink);margin-bottom:0.4rem;line-height:1.4;">International Maritime Organization — Port State Control Overview</h3>
    <p style="font-size:0.88rem;color:var(--ink-soft);line-height:1.7;margin-bottom:0.5rem;">IMO overview of the PSC regime, covering the regulatory framework, regional MoUs, and conventions PSC officers inspect against — SOLAS, MARPOL, STCW, MLC 2006.</p>
    <a href="https://www.imo.org/en/OurWork/IIIS/Pages/Port%20State%20Control.aspx" target="_blank" rel="noopener" style="font-size:0.8rem;color:var(--accent);font-weight:600;text-decoration:underline;">imo.org — Port State Control →</a>
  </div>
  <div style="background:#0d1f3c;border-radius:6px;padding:2.5rem;margin-top:2rem;text-align:center;">
    <p style="font-family:'Cormorant Garamond',Georgia,serif;font-size:1.25rem;font-style:italic;color:rgba(255,255,255,0.88);line-height:1.75;margin:0;">If the content does not help a learner do something differently tomorrow,<br>it does not belong in the course today.</p>
  </div>
</div>
