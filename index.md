---
layout: default
title: Home
---
<section class="hero">
<div class="wrap">
<p class="eyebrow">DevOps Portfolio</p>
<h1>{{ site.data.profile.name }}</h1>
<p class="lead">{{ site.data.profile.tagline }}</p>
<div class="buttons">
<a class="button" href="{{ site.data.profile.internship_repo }}">DevOps Internship Repository</a>
<a class="button alt" href="{{ '/blogs/' | relative_url }}">Read Blogs</a>
</div>
</div>
</section>

<section class="section" id="journey"><div class="wrap">
<p class="eyebrow">Learning Journey</p><h2>DevOps Micro Internship</h2>
<div class="cards">
<div class="card"><h3>Week 00</h3><p>Internet & Networking fundamentals.</p><a href="{{ '/blogs/dmi-week-00-internet-and-networking-assignment.html' | relative_url }}">Read assignment →</a></div>
<div class="card"><h3>Week 01</h3><p>Success mindset and learning habits.</p><a href="{{ '/blogs/dmi-week-01-success-mindset-assignment.html' | relative_url }}">Read assignment →</a></div>
<div class="card"><h3>Week 02</h3><p>Agentic AI concepts and practical workflows.</p><a href="{{ '/blogs/dmi-week-02-agentic-ai-assignment.html' | relative_url }}">Read assignment →</a></div>
</div>
</div></section>

<section class="section" id="projects"><div class="wrap">
<p class="eyebrow">Projects</p><h2>Hands-on Work</h2>
<div class="cards"><div class="card"><h3>DevOps Micro Internship</h3><p>Weekly assignments, projects and documentation.</p><a href="{{ site.data.profile.internship_repo }}">Open GitHub repository →</a></div></div>
</div></section>

<section class="section" id="contact"><div class="wrap">
<p class="eyebrow">Contact</p><h2>GitHub</h2>
<p><a href="https://github.com/{{ site.data.profile.github_username }}">github.com/{{ site.data.profile.github_username }}</a></p>
</div></section>
