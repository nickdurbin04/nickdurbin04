---
layout: default
title: GitHub Projects
---

<section class="projects-page">
  <h1>{{ page.title }}</h1>
  <p>Check out the projects I'm working on, focusing on AI, coding, and open-source contributions.</p>

  <div class="project-list">
    {% assign projects = site.data.projects %}
    {% for project in projects %}
    <div class="project-item">
      <h2>{{ project.title }}</h2>
      <p>{{ project.description }}</p>
      <a href="{{ project.url }}" class="btn-primary" target="_blank">View on GitHub</a>
    </div>
    {% endfor %}
  </div>
</section>
