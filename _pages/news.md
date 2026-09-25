---
layout: page
permalink: /news/
title: News
description: Recent updates, presentations, and media coverage.
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

  html[data-theme="dark"] .timeline-year { color: #3ECF8E; }
  html[data-theme="dark"] .news-tag { border-color: #3ECF8E; color: #3ECF8E; }

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
  .timeline-year {
    font-family: 'Lora', Georgia, serif;
    font-weight: 700;
    font-size: 1.3rem;
    color: #005A43;
    margin: 2.2rem 0 0.9rem -2.1rem;
    padding-left: 2.1rem;
  }
  .timeline-year:first-child { margin-top: 0; }
  .timeline-entry { position: relative; padding-bottom: 2.2rem; }
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
  .news-date {
    display: block;
    font-size: 0.78rem;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #8a8a8a;
    margin-bottom: 0.25rem;
  }
  .news-title { font-weight: 700; font-size: 1.02rem; margin: 0 0 0.35rem; }
  .news-body { color: #4a4a4a; font-size: 0.95rem; line-height: 1.55; margin: 0; }
  .news-tag {
    display: inline-block;
    border: 1px solid #005A43;
    color: #005A43;
    font-family: 'Courier New', monospace;
    font-size: 0.68rem;
    letter-spacing: 0.03em;
    padding: 0.1rem 0.5rem;
    border-radius: 999px;
    margin-left: 0.5rem;
    vertical-align: middle;
  }
  .more-note {
    margin-top: 2rem;
    padding-left: 0.1rem;
    color: #8a8a8a;
    font-size: 0.88rem;
    font-style: italic;
  }
</style>

<span class="eyebrow">Updates</span>

<div class="timeline">

  <p class="timeline-year">2025</p>

  <div class="timeline-entry">
    <span class="news-date">June 2025</span>
    <p class="news-title">Presented at the RSS 2025 Workshop on Reliable Robotics<span class="news-tag">Workshop Talk</span></p>
    <p class="news-body">Presented the poster <strong>"Attacking LLM-based Robot Intelligence for Long-horizon Tasks"</strong> at the RSS 2025 Workshop on Reliable Robotics: Safety and Security in the Face of Generative AI, in Los Angeles, CA.</p>
  </div>

  <div class="timeline-entry">
    <span class="news-date">May 2025</span>
    <p class="news-title">Featured in Binghamton University's Watson GROWS coverage<span class="news-tag">Media</span></p>
    <p class="news-body">Featured in Binghamton University News' coverage of Watson GROWS, which highlighted her robotics research at the poster/demo competition in the Rotunda of the Innovative Technologies Complex. <a href="https://www.binghamton.edu/news/story/5533/watson-grows-puts-spotlight-on-graduate-student-research" target="_blank" rel="noopener">Read the article</a>.</p>
  </div>

  <div class="timeline-entry">
    <span class="news-date">March 2025</span>
    <p class="news-title">Presented at the AAAI 2025 Workshop on Datasets and Evaluators of AI Safety<span class="news-tag">Workshop Talk</span></p>
    <p class="news-body">Presented <strong>"Safety First: a Dataset of Harmful Task Plans for Robots"</strong> at the AAAI 2025 Workshop on Datasets and Evaluators of AI Safety.</p>
  </div>

</div>

<p class="more-note">More updates coming soon.</p>
