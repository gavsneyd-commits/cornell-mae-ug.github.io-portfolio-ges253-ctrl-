---
layout: default
title: Projects
permalink: /projects/
---

<h1>Projects</h1>

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" loading="lazy" onerror="this.onerror=null;this.src='{{ '/assets/images/project-placeholder.png' | relative_url }}';" />
          <div class="gallery-text">
            <h3>{{ project.title }}</h3>
            {% if project.description %}<p>{{ project.description }}</p>{% endif %}
          </div>
        </a>
      </div>
    {% endfor %}
</div>
</div>
