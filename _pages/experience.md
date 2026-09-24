---
layout: page
permalink: /experience/
title: Experience
description: Research, teaching, and industry roles, in reverse chronological order.
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
  .tech-line { margin: 0.6rem 0 0; font-size: 0.88rem; color: #5a5a5a; }
  .tech-line strong { color: #005A43; }
</style>

<span class="eyebrow">Career Timeline</span>

<div class="timeline">

  <div class="timeline-entry">
    <p class="role-title">Graduate Teaching Assistant &middot; <span class="role-org">Binghamton University</span></p>
    <span class="role-meta">Department of Computer Science &middot; Binghamton, NY &middot; Aug 2023&ndash;Present</span>
    <ul class="duty-list">
      <li>Serve as a Graduate Teaching Assistant in the Department of Computer Science while pursuing a Ph.D. in the AIR Lab.</li>
    </ul>
  </div>

  <div class="timeline-entry">
    <p class="role-title">Software Developer &middot; <span class="role-org">Kubtec Medical Imaging</span></p>
    <span class="role-meta">Stratford, CT (Remote) &middot; Sep 2020&ndash;Jun 2023</span>
    <ul class="duty-list">
      <li>Integrated new hardware components into the imaging software, including X-ray sources, optical cameras, and detectors.</li>
      <li>Developed new features for the imaging software, such as retrieving images from a PACS server and licensing advanced features.</li>
      <li>Built new projects, including a Windows application to test the hardware components of the system.</li>
      <li>Resolved customer-reported issues.</li>
      <li>Documented the development process for new projects, including user needs, Software Requirement Specifications (SRS), Software Design Specifications (SDS), and test plans.</li>
    </ul>
    <p class="tech-line"><strong>Technologies:</strong> C#, SQLite, SQL, WPF, Keygen Licensing API, Orthanc PACS server, MWL emulator, rzdcx toolkit, dcmtk toolkit.</p>
  </div>

  <div class="timeline-entry">
    <p class="role-title">Assistant Lecturer &middot; <span class="role-org">University of Kerbala</span></p>
    <span class="role-meta">Prosthetics &amp; Orthotics Dept., College of Engineering &middot; Karbala, Iraq (Part-Time) &middot; Aug 2020&ndash;Aug 2023</span>
    <ul class="duty-list">
      <li>Taught as Assistant Lecturer in the Prosthetics and Orthotics Department, College of Engineering.</li>
      <li>Served as administrator of the College of Engineering's IT Department (2022&ndash;2023).</li>
    </ul>
  </div>

  <div class="timeline-entry">
    <p class="role-title">Software Developer Intern &middot; <span class="role-org">Kubtec Medical Imaging</span></p>
    <span class="role-meta">Stratford, CT &middot; Aug 2019&ndash;May 2020</span>
    <ul class="duty-list">
      <li>Reviewed and analyzed system specifications and tested imaging software.</li>
      <li>Conducted research to reduce speech signal noise and improve voice-recognition features.</li>
      <li>Developed, executed, and analyzed test plans for the imaging software, with a focus on the voice-commands feature.</li>
      <li>Troubleshot customer issues and worked on customization requests.</li>
    </ul>
    <p class="tech-line"><strong>Technologies:</strong> C#, WPF, Python, SQL, SQLite, Orthanc PACS server.</p>
  </div>

  <div class="timeline-entry">
    <p class="role-title">Computer Engineer &amp; Teaching Assistant &middot; <span class="role-org">University of Kerbala</span></p>
    <span class="role-meta">Prosthetics &amp; Orthotics Dept., College of Engineering &middot; Karbala, Iraq &middot; May 2017&ndash;Aug 2018</span>
    <ul class="duty-list">
      <li>Worked as a computer engineer and teaching assistant in the Prosthetics and Orthotics Department, College of Engineering.</li>
    </ul>
  </div>

  <div class="timeline-entry">
    <p class="role-title">Teaching Assistant &middot; <span class="role-org">Al-Nahrain University</span></p>
    <span class="role-meta">Computer Engineering Department &middot; Baghdad, Iraq &middot; Oct 2014&ndash;May 2017</span>
    <ul class="duty-list">
      <li>Taught as a teaching assistant in the Computer Engineering Department.</li>
      <li>Developed the College of Engineering's E-Library system.</li>
    </ul>
  </div>

  <div class="timeline-entry">
    <p class="role-title">Network Engineer Intern &middot; <span class="role-org">NetMax Company</span></p>
    <span class="role-meta">Baghdad, Iraq &middot; Sep 2014&ndash;Oct 2014</span>
    <ul class="duty-list">
      <li>Worked on device configuration, troubleshooting, and network service monitoring.</li>
    </ul>
  </div>

</div>
