---
permalink: /publications/
title: "Publications"
author_profile: true
classes: wide
---

{% assign selected_publications = site.data.publications | where: "section", "Selected papers" %}
{% assign additional_publications = site.data.publications | where: "section", "Additional papers" %}
{% assign theses = site.data.publications | where: "section", "Theses" %}

<section class="gm-section">
  <h2>Selected Papers</h2>
  <div class="gm-list">
  {% for publication in selected_publications %}
    <article class="gm-list-item">
      <div class="gm-meta">{{ publication.year }} - {{ publication.status }}</div>
      <h3>{{ publication.title }}</h3>
      <p>{{ publication.authors }}</p>
      <p><em>{{ publication.venue }}</em></p>
      <p><strong>{{ publication.role }}.</strong> {{ publication.summary }}</p>
      {% if publication.links and publication.links.size > 0 %}
        <div class="gm-link-row">
        {% for link in publication.links %}
          <a href="{{ link.url }}">{{ link.label }}</a>
        {% endfor %}
        </div>
      {% endif %}
    </article>
  {% endfor %}
  </div>
</section>

<section class="gm-section">
  <h2>Theses</h2>
  <div class="gm-list">
  {% for publication in theses %}
    <article class="gm-list-item">
      <div class="gm-meta">{{ publication.year }} - {{ publication.status }}</div>
      <h3>{{ publication.title }}</h3>
      <p>{{ publication.authors }}</p>
      <p><em>{{ publication.venue }}</em></p>
      <p><strong>{{ publication.role }}.</strong> {{ publication.summary }}</p>
      {% if publication.links and publication.links.size > 0 %}
        <div class="gm-link-row">
        {% for link in publication.links %}
          <a href="{{ link.url }}">{{ link.label }}</a>
        {% endfor %}
        </div>
      {% endif %}
    </article>
  {% endfor %}
  </div>
</section>

<section class="gm-section">
  <h2>Additional Papers</h2>
  <div class="gm-list">
  {% for publication in additional_publications %}
    <article class="gm-list-item">
      <div class="gm-meta">{{ publication.year }} - {{ publication.status }}</div>
      <h3>{{ publication.title }}</h3>
      <p>{{ publication.authors }}</p>
      <p><em>{{ publication.venue }}</em></p>
      <p><strong>{{ publication.role }}.</strong> {{ publication.summary }}</p>
      {% if publication.links and publication.links.size > 0 %}
        <div class="gm-link-row">
        {% for link in publication.links %}
          <a href="{{ link.url }}">{{ link.label }}</a>
        {% endfor %}
        </div>
      {% endif %}
    </article>
  {% endfor %}
  </div>
</section>
