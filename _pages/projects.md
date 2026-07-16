---
layout: default
title: Eric Luo - Portfolio
permalink: /projects/
---

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
    <h2> Featured </h2>
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    <h2> Other </h2>
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
