---
permalink: /research/
title: "Research"
author_profile: true
classes: wide
---

My research uses probabilistic machine learning for strong gravitational lensing and dark-matter inference. I focus on uncertainty, model mismatch, and inference over sources, lenses, and substructure.

<figure class="gm-visual gm-visual--contained">
  <img src="{{ '/assets/images/research_dag.png' | relative_url }}" alt="Strong-lensing dark-matter inference diagram">
  <figcaption>
    Directed acyclic graph (DAG) for strong-lensing dark-matter inference. A source is lensed by a macro model and a substructure field to produce the observed image. Galaxy image adapted from Bottrell et al. (2024).
  </figcaption>
</figure>

<section class="gm-section">
  <h2>Scientific Motivation</h2>
  <p>
    Approximately 85% of the matter in the universe exists in the form of dark matter, which is dark because we do not observe it directly. Its presence is inferred from gravitational effects on astrophysical observations that cannot be explained by visible matter alone.
  </p>
  <p>
    Despite its pervasive influence, the true nature of dark matter remains one of the most significant open questions in modern cosmology. Different theoretical models, notably cold dark matter (CDM) and warm dark matter (WDM), predict distinct dark-matter distributions on scales smaller than a single galaxy. Accurately measuring dark matter on these scales would help distinguish between these models, but doing so requires a purely gravitational probe.
  </p>
  <p>
    Strong gravitational lensing, the bending of light from background galaxies by the gravitational field of a foreground mass, offers one such probe. Dark-matter subhalos can induce subtle perturbations in the lensing signal, providing indirect evidence of their existence. The challenge is that this signal must be separated from the background source, the main lens mass, foreground galaxy light, and observational noise.
  </p>
  <figure class="gm-visual gm-visual--compact">
    <img src="{{ '/assets/images/kappa_maps.png' | relative_url }}" alt="Simulated cold and warm dark matter substructure maps">
    <figcaption>
      Cold and warm dark-matter models predict different substructure populations. Simulations created with pyHalo; credit: Gilman et al. (2019).
    </figcaption>
  </figure>
</section>
