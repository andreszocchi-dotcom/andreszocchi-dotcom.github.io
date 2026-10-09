---
layout: default
title: Projects
permalink: /projects/
---

<p class="eyebrow">Selected projects</p>

<h1 class="page-title">{{ page.title | escape }}</h1>

<div class="project-list">
  {% for project in site.data.projects %}
    {% include project-card.html project=project %}
  {% endfor %}
</div>
