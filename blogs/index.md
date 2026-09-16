---
layout: blog
title: DevOps Blogs
description: Notes and write-ups from my DevOps Micro Internship journey.
permalink: /blogs/
---

<div class="cards">
{% assign posts = site.pages | where_exp: "p", "p.path contains 'blogs/'" %}
{% for post in posts %}
  {% unless post.path == "blogs/index.md" %}
  <div class="card">
    <h3>{{ post.title }}</h3>
    {% if post.description %}<p>{{ post.description }}</p>{% endif %}
    <a href="{{ post.url | relative_url }}">Read article →</a>
  </div>
  {% endunless %}
{% endfor %}
</div>
