---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

A complete list of publications is available on my [Google Scholar page](https://scholar.google.com/citations?user=fgK0xnYAAAAJ&hl=en/).


{% comment %}
### Selected papers
* K.Guo and J.Chan, ["Bernstein-B\'ezier weight-adjusted discontinuous Galerkin methods for wave propagation in heterogeneous media"] (https://www.sciencedirect.com/science/article/pii/S002199911930676X), Journal of Computational Physics. 2020
{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}