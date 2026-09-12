---
layout: page
title: Projects
permalink: /projects/
description: Selected research and robotics systems spanning embodied AI, human-centered safety, perception, and control.
nav: true
published: true
nav_order: 3
---

<div class="project-list">
  <article class="project-feature project-feature--wide">
    <div class="project-feature__content">
      <p class="eyebrow">Robotics · Senior capstone</p>
      <h2>Trash vs. Recycling Robot</h2>
      <p>Developed a CasADi-based model predictive controller for mobile robot navigation with obstacle-avoidance constraints and finite-horizon velocity optimization. The broader three-person system approached seated users, collected deposited items, and routed trash and recycling into separate onboard bins.</p>
      <a class="text-link" href="https://github.com/owen-hoffman40/trash_bot">Capstone code <span aria-hidden="true">↗</span></a>
      <ul class="tag-list"><li>ROS 2</li><li>Python</li><li>CasADi</li><li>Model predictive control</li></ul>
    </div>
  </article>

  <div class="project-grid">
    <article class="project-feature">
      <div class="project-feature__content">
        <p class="eyebrow">Human-centered AI</p>
        <h2>Privacy Navigator</h2>
        <p>Built an LLM-assisted pipeline that extracts and scores website privacy disclosures, identifies contact channels, and translates policy language into concrete actions people can take to improve their privacy.</p>
        <ul class="tag-list"><li>LLMs</li><li>Web extraction</li><li>Interface design</li><li>Evaluation</li></ul>
      </div>
    </article>
  </div>

  <article class="project-feature project-feature--publication">
    <div class="project-feature__content">
      <p class="eyebrow">Published at ACM CHI 2026</p>
      <h2>ScamPilot</h2>
      <p>Designed an LLM-agent system that simulates adaptive scam conversations for interactive safety training. I developed the controlled prompting and experimental pipeline, led the user study, and implemented the statistical analysis of scam recognition, response efficacy, and self-efficacy.</p>
      <a class="text-link" href="https://dl.acm.org/doi/full/10.1145/3772318.3791313">Read the paper <i class="fa-solid fa-arrow-up-right-from-square" aria-hidden="true"></i></a>
    </div>
    <img src="{{ '/assets/img/publication_preview/scampilot.png' | relative_url }}" alt="Diagram of the ScamPilot multi-agent conversation system">
  </article>
</div>
