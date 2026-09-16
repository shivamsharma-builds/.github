---
layout: default
title: Home
---

<section class="hero">
  <div class="container">
    <p class="eyebrow">DevOps Portfolio</p>
    <h1>{{ site.data.profile.name }}</h1>
    <p class="lead">{{ site.data.profile.tagline }}</p>
    <div class="buttons">
      <a class="button" href="{{ site.data.profile.internship_repo }}">View Internship Repository</a>
      <a class="button secondary" href="{{ '/blogs/' | relative_url }}">Read My Blogs</a>
    </div>
  </div>
</section>

<section class="section" id="about">
  <div class="container">
    <p class="eyebrow">About</p>
    <h2>{{ site.data.profile.role }}</h2>
    <p>I am documenting my hands-on journey across Linux, networking, Git, cloud platforms, infrastructure as code, containers, Kubernetes, CI/CD, and Agentic AI.</p>
  </div>
</section>

<section class="section" id="journey">
  <div class="container">
    <p class="eyebrow">Learning Journey</p>
    <h2>DevOps Micro Internship</h2>
    <div class="cards">
      <div class="card"><h3>Weeks 00–02</h3><p>Internet & Networking, Success Mindset, and Agentic AI.</p></div>
      <div class="card"><h3>Weeks 03–06</h3><p>Linux/Bash, Git/GitHub, AWS and Azure fundamentals.</p></div>
      <div class="card"><h3>Weeks 07–13</h3><p>Terraform, Ansible, Azure DevOps, Docker, Kubernetes and the final project.</p></div>
    </div>
  </div>
</section>

<section class="section" id="projects">
  <div class="container">
    <p class="eyebrow">Projects</p>
    <h2>Hands-on Work</h2>
    <div class="cards">
      <div class="card"><h3>DevOps Micro Internship</h3><p>Weekly assignments and practical DevOps learning.</p><a href="{{ site.data.profile.internship_repo }}">Open repository →</a></div>
      <div class="card"><h3>Blog & Documentation</h3><p>Technical notes explaining what I learn and build.</p><a href="{{ '/blogs/' | relative_url }}">Explore blogs →</a></div>
    </div>
  </div>
</section>

<section class="section" id="contact">
  <div class="container">
    <p class="eyebrow">Contact</p>
    <h2>Find me online</h2>
    <p><a href="https://github.com/{{ site.data.profile.github_username }}">GitHub</a></p>
  </div>
</section>
