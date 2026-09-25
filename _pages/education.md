---
layout: page
permalink: /education/
title: Education
description: Academic background and training.
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,500;0,600;0,700;1,500&display=swap');

  :root {
    --global-theme-color: #005A43;
    --global-hover-color: #00432f;
  }

  html[data-theme="dark"] {
    --global-theme-color: #3ECF8E;
    --global-hover-color: #3ECF8E;
  }

  html[data-theme="dark"] .role-org { color: #3ECF8E; }
  html[data-theme="dark"] .honor-badge { border-color: #3ECF8E; color: #3ECF8E; }

  h1.post-title, h2 { font-family: 'Lora', Georgia, serif; }
  .post-title { font-weight: 700; }
  .post-header .desc { color: #5a5a5a; font-weight: 400; }

  .eyebrow {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: #005A43;
    color: #fff;
    font-family: 'Courier New', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    padding: 0.28rem 0.75rem;
    border-radius: 4px;
    margin-bottom: 1.1rem;
  }

  .timeline { position: relative; margin: 1.5rem 0 1rem; padding-left: 2.1rem; }
  .timeline::before {
    content: "";
    position: absolute;
    left: 6px;
    top: 6px;
    bottom: 6px;
    width: 2px;
    background: rgba(0, 90, 67, 0.25);
  }
  .timeline-entry { position: relative; padding-bottom: 2.4rem; }
  .timeline-entry:last-child { padding-bottom: 0; }
  .timeline-entry::before {
    content: "";
    position: absolute;
    left: -2.1rem;
    top: 0.4rem;
    width: 11px;
    height: 11px;
    background: #005A43;
    transform: rotate(45deg);
    border: 2px solid #fff;
    box-shadow: 0 0 0 2px rgba(0, 90, 67, 0.35);
  }

  .role-title { font-weight: 700; font-size: 1.05rem; margin: 0 0 0.15rem; }
  .role-org { color: #005A43; font-weight: 600; }
  .role-meta {
    display: block;
    font-size: 0.78rem;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #8a8a8a;
    margin: 0.15rem 0 0.6rem;
  }
  .duty-list { margin: 0; padding-left: 1.1rem; color: #4a4a4a; font-size: 0.95rem; line-height: 1.6; }
  .duty-list li { margin-bottom: 0.25rem; }
  .honor-badge {
    display: inline-block;
    border: 1px solid #005A43;
    color: #005A43;
    font-size: 0.78rem;
    padding: 0.1rem 0.55rem;
    border-radius: 999px;
    margin-top: 0.5rem;
  }
</style>

<span class="eyebrow">Academic Background</span>

<div class="timeline">

  <div class="timeline-entry">
    <p class="role-title">Ph.D. in Computer Science &middot; <span class="role-org">Binghamton University</span></p>
    <span class="role-meta">Binghamton, NY &middot; Started Aug 2023 &middot; GPA 4.0/4.0</span>
    <ul class="duty-list">
      <li>Ph.D. researcher in the AIR Lab (Autonomous Intelligence &amp; Robotics Lab), advised by Prof. Shiqi Zhang.</li>
      <li>Research focus: reinforcement learning for humanoid robot locomotion, including policy training and analysis of robustness and adversarial failure modes.</li>
      <li>Research focus: security and safety of robot task planning, including attacks and defense mechanisms against harmful plan generation.</li>
      <li>Research focus: LLM-based pipelines for structured decision-making and sequential task execution with state tracking.</li>
    </ul>
  </div>

  <div class="timeline-entry">
    <p class="role-title">M.S. in Computer Engineering &middot; <span class="role-org">University of Bridgeport</span></p>
    <span class="role-meta">Bridgeport, CT &middot; Awarded May 2020 &middot; GPA 3.97/4.0</span>
    <ul class="duty-list">
      <li>Fulbright Foreign Student Program Scholar (2018&ndash;2020).</li>
      <li>Awarded Academic Achievement in Computer Engineering.</li>
      <li>Thesis: "Speech Signal Enhancement Based on Sequence to Sequence Model with a Novel Attention Mechanism," supervised by Prof. Ausif Mahmood &mdash; designed and implemented a deep learning model for speech signal enhancement using Python and Keras.</li>
    </ul>
  </div>

  <div class="timeline-entry">
    <p class="role-title">Pre-Academic English Language Course &middot; <span class="role-org">Drexel University</span></p>
    <span class="role-meta">Philadelphia, PA &middot; Awarded Aug 2018</span>
    <ul class="duty-list">
      <li>Six-week intensive pre-academic English language course.</li>
    </ul>
  </div>

  <div class="timeline-entry">
    <p class="role-title">B.S. in Computer Engineering &middot; <span class="role-org">Al-Nahrain University</span></p>
    <span class="role-meta">Baghdad, Iraq &middot; Awarded Jul 2014</span>
    <ul class="duty-list">
      <li>First-ranked student, College of Engineering Award.</li>
    </ul>
  </div>

</div>
