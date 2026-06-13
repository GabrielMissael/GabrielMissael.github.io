---
layout: single
title: ""
author_profile: true
classes: wide
---

<section class="gm-hero">
  <div>
    <div class="gm-eyebrow">Probabilistic ML for astrophysics</div>
    <h1>Gabriel Missael Barco</h1>
    <p class="gm-lede">
      I am a PhD student in Physics at Université de Montréal and Mila, advised by Yashar Hezaveh and Laurence Perreault-Levasseur. I work on probabilistic machine learning for strong gravitational lensing and dark matter.
    </p>
    <div class="gm-actions">
      <a class="gm-button" href="{{ '/research/' | relative_url }}">Research</a>
      <a class="gm-button--secondary" href="{{ '/publications/' | relative_url }}">Publications</a>
    </div>
  </div>
  <figure class="gm-visual">
    <img src="{{ '/assets/images/research_dag.png' | relative_url }}" alt="Diagram of strong-lensing inference variables: source, lens, dark-matter substructure, and observation">
    <figcaption>
      Strong-lensing dark-matter inference.
    </figcaption>
  </figure>
</section>

<section class="gm-section">
  <h2>Featured Work</h2>
  <div class="gm-grid">
    <article class="gm-card">
      <img class="gm-image--contain" src="{{ '/assets/images/feature-apj-prior-update.png' | relative_url }}" alt="Figure from the ApJ paper showing biased and corrected source reconstructions under misspecified learned priors">
      <div class="gm-meta">ApJ paper</div>
      <h3>Correcting misspecified data-driven priors</h3>
      <p>Updating learned priors when simulations bias posterior reconstructions.</p>
      <div class="gm-link-row">
        <a href="https://arxiv.org/abs/2407.17667">arXiv</a>
        <a href="https://doi.org/10.3847/1538-4357/ad9b92">DOI</a>
      </div>
    </article>
    <article class="gm-card">
      <img class="gm-image--contain" src="{{ '/assets/images/feature-blind-inversion.png' | relative_url }}" alt="Figure from the blind inversion paper showing observed lensing data and joint source-lens posterior reconstructions">
      <div class="gm-meta">NeurIPS ML4PS 2025</div>
      <h3>Blind strong-lensing inversion</h3>
      <p>Joint source and lens-mass inference from noisy strong-lensing images.</p>
      <div class="gm-link-row">
        <a href="https://arxiv.org/abs/2511.04792">arXiv</a>
        <a href="https://neurips.cc/virtual/2025/122888">Poster</a>
      </div>
    </article>
    <article class="gm-card">
      <img class="gm-image--contain gm-image--logo" src="{{ '/assets/images/caustics_logo.png' | relative_url }}" alt="Caustics logo">
      <div class="gm-meta">Scientific software</div>
      <h3>Caustics</h3>
      <p>Open-source tools for differentiable strong-lensing simulations.</p>
      <div class="gm-link-row">
        <a href="https://github.com/Ciela-Institute/caustics">GitHub</a>
        <a href="https://joss.theoj.org/papers/10.21105/joss.07081">JOSS</a>
      </div>
    </article>
  </div>
</section>
