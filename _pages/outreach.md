---
permalink: /outreach/
title: "Outreach"
author_profile: true
classes: wide
---

<div class="gm-grid gm-grid--two">
{% for item in site.data.outreach %}
  <article class="gm-card">
    <div class="gm-meta">{{ item.period }} - {{ item.context }}</div>
    <h3>{{ item.title }}</h3>
    <p><strong>{{ item.role }}</strong></p>
    <p>{{ item.summary }}</p>
    {% if item.links and item.links.size > 0 %}
      <div class="gm-link-row">
      {% for link in item.links %}
        <a href="{{ link.url }}">{{ link.label }}</a>
      {% endfor %}
      </div>
    {% endif %}
  </article>
{% endfor %}
</div>
