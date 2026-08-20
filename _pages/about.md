---
permalink: /
title: "Xiwei Wu"
excerpt: "Formal verification, verified systems, and AI-assisted verification"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<p class="home-role">Ph.D. Candidate at Shanghai Jiao Tong University</p>

<h2 id="about">About Me</h2>

<p class="home-lead">
  I am a Ph.D. candidate in Computer Science and Technology at
  <a href="https://en.sjtu.edu.cn/">Shanghai Jiao Tong University</a>, advised by
  Prof. Qinxiang Cao. I am a primary developer of
  <strong>QCP (Qualified C Programming Verifier)</strong>, a separation-logic-based
  verification tool that combines annotation-guided automation with interactive
  proofs in Rocq.
</p>

<p class="home-lead">
  My research focuses on making formal verification practical for real-world
  systems software. In particular, I am interested in program logics and
  automated reasoning, the verification of low-level systems software, and
  AI-assisted techniques for invariant and proof generation.
</p>

<p class="home-contact">
  <a href="mailto:yashen@sjtu.edu.cn">Email</a>
  <span aria-hidden="true">&middot;</span>
  <a href="https://github.com/yashen32768">GitHub</a>
</p>

<section id="research" class="home-section">
  <h2>Research</h2>

  My research centers on QCP and its applications:

  <ul class="research-list">
    <li><strong>QCP:</strong> developing a practical C program verifier based on separation logic, symbolic execution, automated reasoning, and proof checking in Rocq.</li>
    <li><strong>Systems Verification:</strong> applying QCP to real-world systems software, including eBPF applications and operating-system kernels.</li>
    <li><strong>AI-assisted Verification:</strong> integrating large language models with QCP for loop-invariant generation, verification-condition proving, and more automated verification workflows.</li>
  </ul>
</section>

{% include publications-home.html heading="Selected Publications" equal_note="Equal contribution." selected_only=true view_all_url="/publications/" view_all_label="View all publications →" %}

{% include home-styles.html %}
