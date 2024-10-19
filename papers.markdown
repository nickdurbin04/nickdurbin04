---
layout: default
title: Research Papers I've Read
---

<section class="papers-page">
  <h1>{{ page.title }}</h1>
  <p>A curated list of papers I have studied. Click on a title to read the paper.</p>

  <div class="paper-list">
    {% assign papers = site.data.papers | reverse %}
    {% for paper in papers %}
    <div class="paper-item">
      <h3>{{ paper.title }}</h3>
      <a href="{{ paper.url }}" class="btn-primary" target="_blank">Read Paper</a>
    </div>
    {% endfor %}
  </div>
</section>
