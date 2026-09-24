---
layout: page
permalink: /publications/
title: Publications
description: Peer-reviewed papers, in reverse chronological order.
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,500;0,600;0,700;1,500&display=swap');

  :root {
    --global-theme-color: #005A43;
    --global-hover-color: #00432f;
  }

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
  .timeline-entry { position: relative; padding-bottom: 2.6rem; }
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

  .pub-entry { display: flex; gap: 1.4rem; align-items: flex-start; flex-wrap: wrap; }
  .pub-thumb {
    flex: 0 0 200px;
    width: 200px;
    height: 122px;
    border-radius: 10px;
    overflow: hidden;
    background: #0b1f18;
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.12);
  }
  .pub-thumb video, .pub-thumb img { width: 100%; height: 100%; object-fit: cover; display: block; }
  .pub-body { flex: 1 1 320px; min-width: 240px; }
  .pub-row { display: flex; align-items: flex-start; justify-content: space-between; gap: 1rem; flex-wrap: nowrap; }
  .pub-title { font-weight: 700; font-size: 1.05rem; margin: 0; line-height: 1.4; flex: 1 1 auto; min-width: 0; }
  .pub-title a { color: #16211d; text-decoration: none; }
  .pub-title a:hover { color: #005A43; }
  .venue-tag {
    display: inline-block;
    flex: 0 0 auto;
    border: 1px solid #005A43;
    color: #005A43;
    font-family: 'Courier New', monospace;
    font-size: 0.72rem;
    letter-spacing: 0.03em;
    padding: 0.15rem 0.6rem;
    border-radius: 999px;
    white-space: nowrap;
    margin-top: 0.15rem;
  }
  .pub-authors { color: #5a5a5a; font-size: 0.92rem; margin: 0.45rem 0 0.5rem; }
  .pub-links { font-size: 0.88rem; }
  .pub-links a {
    color: #005A43;
    text-decoration: underline;
    text-decoration-color: rgba(0, 90, 67, 0.4);
    margin-right: 1.1rem;
  }
  .pub-links a:hover { text-decoration-color: #005A43; }
</style>

<span class="eyebrow">Selected Work</span>

<div class="timeline">

  <div class="timeline-entry">
    <div class="pub-entry">
      <div class="pub-thumb">
        <video class="lazy-video" muted loop playsinline preload="none" src="https://protea-secure.github.io/PROTEA/assets/videos/iros.mp4"></video>
      </div>
      <div class="pub-body">
        <div class="pub-row">
          <p class="pub-title"><a href="https://arxiv.org/pdf/2601.07186" target="_blank" rel="noopener">PROTEA: Securing Robot Task Planning and Execution</a></p>
          <span class="venue-tag">IROS 2026</span>
        </div>
        <p class="pub-authors"><strong>Zainab Altaweel</strong>, Mohaiminul Al Nahian, Jake Juettner, Adnan Siraj Rakin, Shiqi Zhang</p>
        <p class="pub-links">
          <a href="https://arxiv.org/pdf/2601.07186" target="_blank" rel="noopener">Paper</a>
          <a href="https://protea-secure.github.io/PROTEA/" target="_blank" rel="noopener">Project page</a>
        </p>
      </div>
    </div>
  </div>

  <div class="timeline-entry">
    <div class="pub-entry">
      <div class="pub-thumb">
        <video class="lazy-video" muted loop playsinline preload="none" src="https://mutrap.github.io/MuTRAP/generated_plans_videos/Robotroj_Malicous.mp4"></video>
      </div>
      <div class="pub-body">
        <div class="pub-row">
          <p class="pub-title"><a href="https://arxiv.org/pdf/2504.17070" target="_blank" rel="noopener">MuTRAP: Multi-trigger Trojans Attacking Robot Task Planning Systems</a></p>
          <span class="venue-tag">IROS 2026</span>
        </div>
        <p class="pub-authors">Mohaiminul Al Nahian*, <strong>Zainab Altaweel*</strong>, David Reitano, Sabbir Ahmed, Shiqi Zhang, Adnan Siraj Rakin &middot; *equal contribution</p>
        <p class="pub-links">
          <a href="https://arxiv.org/pdf/2504.17070" target="_blank" rel="noopener">Paper</a>
          <a href="https://mutrap.github.io/MuTRAP/" target="_blank" rel="noopener">Project page</a>
        </p>
      </div>
    </div>
  </div>

  <div class="timeline-entry">
    <div class="pub-entry">
      <div class="pub-thumb">
        <video class="lazy-video" muted loop playsinline preload="none" src="https://vap-tamp.github.io/vap-tamp/videos/IROS26_3741_VI_i.mp4"></video>
      </div>
      <div class="pub-body">
        <div class="pub-row">
          <p class="pub-title"><a href="https://arxiv.org/pdf/2604.26988" target="_blank" rel="noopener">Robot Planning and Situation Handling with Active Perception</a></p>
          <span class="venue-tag">IROS 2026</span>
        </div>
        <p class="pub-authors">Austine Oloo, <strong>Zainab Altaweel</strong>, Yohei Hayamizu, Peiqi Liu, Yan Ding, Saeid Amiri, Hao Yang, Andy Kaminski, Chad Esselink, Chris Paxton, Xiaohan Zhang, Shiqi Zhang</p>
        <p class="pub-links">
          <a href="https://arxiv.org/pdf/2604.26988" target="_blank" rel="noopener">Paper</a>
          <a href="https://vap-tamp.github.io/vap-tamp/" target="_blank" rel="noopener">Project page</a>
        </p>
      </div>
    </div>
  </div>

  <div class="timeline-entry">
    <div class="pub-entry">
      <div class="pub-thumb">
        <img src="/assets/img/publications/woofs-to-words-overview.png" alt="From Woofs to Words system overview figure" loading="lazy">
      </div>
      <div class="pub-body">
        <div class="pub-row">
          <p class="pub-title"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/41198" target="_blank" rel="noopener">From Woofs to Words: Towards Intelligent Robotic Guide Dogs with Verbal Communication</a></p>
          <span class="venue-tag">AAAI 2026</span>
        </div>
        <p class="pub-authors">Yohei Hayamizu*, David DeFazio*, Hrudayangam Mehta*, <strong>Zainab Altaweel</strong>, Jacqueline Choe, Chao Lin, Jake Juettner, Furui Xiao, Jeremy Blackburn, Shiqi Zhang &middot; *equal contribution</p>
        <p class="pub-links">
          <a href="https://ojs.aaai.org/index.php/AAAI/article/view/41198" target="_blank" rel="noopener">Paper</a>
          <a href="https://sites.google.com/view/woofs-words" target="_blank" rel="noopener">Project page</a>
        </p>
      </div>
    </div>
  </div>

  <div class="timeline-entry">
    <div class="pub-entry">
      <div class="pub-thumb">
        <img src="https://bu-air-lab.github.io/llm-grop/Overview.jpg" alt="LLM-GROP overview figure" loading="lazy">
      </div>
      <div class="pub-body">
        <div class="pub-row">
          <p class="pub-title"><a href="https://doi.org/10.1177/02783649251378196" target="_blank" rel="noopener">LLM-GROP: Visually Grounded Robot Task and Motion Planning with Large Language Models</a></p>
          <span class="venue-tag">IJRR 2025</span>
        </div>
        <p class="pub-authors">Xiaohan Zhang*, Yan Ding*, Yohei Hayamizu*, <strong>Zainab Altaweel*</strong>, Yifeng Zhu, Yuke Zhu, Peter Stone, Chris Paxton, Shiqi Zhang &middot; *equal contribution</p>
        <p class="pub-links">
          <a href="https://doi.org/10.1177/02783649251378196" target="_blank" rel="noopener">Paper</a>
          <a href="https://bu-air-lab.github.io/llm-grop/" target="_blank" rel="noopener">Project page</a>
        </p>
      </div>
    </div>
  </div>

  <div class="timeline-entry">
    <div class="pub-entry">
      <div class="pub-thumb">
        <img src="https://figures.semanticscholar.org/1880e89ddb71c5c3c84d89207ff8ad7dd21b05dc/4-Figure1-1.png" alt="Neural network architecture figure from the EMG hand gestures paper" loading="lazy">
      </div>
      <div class="pub-body">
        <div class="pub-row">
          <p class="pub-title"><a href="https://pdfs.semanticscholar.org/1880/e89ddb71c5c3c84d89207ff8ad7dd21b05dc.pdf" target="_blank" rel="noopener">Using Deep Neural Networks in Classifying Electromyography Signals for Hand Gestures</a></p>
          <span class="venue-tag">IJ-AI 2024</span>
        </div>
        <p class="pub-authors">Ahmed M Al-Khazzar, <strong>Zainab Altaweel</strong>, Jabbar S Hussain</p>
        <p class="pub-links">
          <a href="https://pdfs.semanticscholar.org/1880/e89ddb71c5c3c84d89207ff8ad7dd21b05dc.pdf" target="_blank" rel="noopener">Paper</a>
        </p>
      </div>
    </div>
  </div>

  <div class="timeline-entry">
    <div class="pub-entry">
      <div class="pub-thumb">
        <img src="https://figures.semanticscholar.org/d7af8c1eadaf3228fc9cae6c4c37a76716fc26fe/3-Figure1-1.png" alt="Hardware architecture figure from the Smart Parking paper" loading="lazy">
      </div>
      <div class="pub-body">
        <div class="pub-row">
          <p class="pub-title"><a href="https://ieeexplore.ieee.org/abstract/document/9221069" target="_blank" rel="noopener">Smart Parking for Disabled Parking Improvement Using RFID and Database Authentication</a></p>
          <span class="venue-tag">WF-IoT 2020</span>
        </div>
        <p class="pub-authors"><strong>Zainab Al Taweel</strong>, Lavanya Challagundla, Alexander Pagan, Abdel-shakour Abuzneid</p>
        <p class="pub-links">
          <a href="https://ieeexplore.ieee.org/abstract/document/9221069" target="_blank" rel="noopener">Paper</a>
        </p>
      </div>
    </div>
  </div>

</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    var videos = document.querySelectorAll('video.lazy-video');
    if (!('IntersectionObserver' in window)) {
      videos.forEach(function (v) { v.play().catch(function () {}); });
      return;
    }
    var observer = new IntersectionObserver(
      function (entries) {
        entries.forEach(function (entry) {
          var v = entry.target;
          if (entry.isIntersecting) {
            v.play().catch(function () {});
          } else {
            v.pause();
          }
        });
      },
      { threshold: 0.25 }
    );
    videos.forEach(function (v) { observer.observe(v); });
  });
</script>
