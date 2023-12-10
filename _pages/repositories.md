---
layout: page
permalink: /repositories/
title: Code
description: 
nav: true
nav_order: 4
---

<!-- 1. ATM (Matlab): Adaptive algorithm for learning structured transport maps from samples
2. StochasticMaps (Matlab): Sequential Bayesian inference for non-Gaussian dynamical systems 
3. TransportMaps (Python): Learning parametric transformations between probability distributions 
4. GreedyPC (Matlab): Greedy algorithm for constructing sparse polynomial approximations
5. BOCS (Python/Matlab): Bayesian optimization for solving black-box combinatorial problems
 -->
Personal Github repositories for some research projects:

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
\


## Collaborative projects

I have had the opportunity to contribute to software packages that learn transport maps for generative modeling, solving inference problems, and representing probabilistic graphical models:

**[TransportMaps](https://transportmaps.mit.edu)**\
**[Monotone Parameterization Toolkit](https://measuretransport.github.io/MParT/)**
