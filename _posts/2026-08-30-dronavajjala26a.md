---
title: When Is Conformal Coverage Free? Switching Thresholds for Predict-then-Optimize
abstract: 'Machine learning increasingly drives operational decisions (dispatching
  power plants, routing vehicles, allocating medical supplies), yet its forecasts
  are uncertain. Conformal prediction turns a forecast into a calibrated uncertainty
  set with distribution-free guarantees, and a robust optimizer can then hedge its
  decision against that set. Before adopting this, a practitioner wants to know: will
  maintaining the uncertainty set actually change the decision the system makes, or
  will it leave the decision untouched and merely add an audit trail? We answer with
  a single quantity, the switching threshold: the point at which calibrated uncertainty
  begins to alter the chosen action. While the uncertainty stays below this threshold,
  coverage is free, and the system gains calibrated, auditable uncertainty without
  changing what it does. We show how to read this threshold from the structure of
  the decision problem, characterize the fluctuations of the online quantile that
  decide which side of it a problem falls on, and reduce these to a single pre-deployment
  safety margin that labels a problem as free, borderline, or costly. The label is
  set by the decision problem’s structure rather than the choice of predictor. Across
  real benchmarks in energy, routing, public health, and logistics, dispatching power
  under real market prices is free (coverage never changes which generators run and
  adds no cost), whereas routing on a dense city map changes the route about half
  the time. The certificate stays reliable at city scale, on road networks with tens
  of thousands of streets, and even when the predictor is a vision model reading images.
  The result is a simple test for whether adding conformal coverage will cost a decision
  system anything.'
section: Explainability and Decision Making
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dronavajjala26a
month: 0
tex_title: When Is Conformal Coverage Free? Switching Thresholds for Predict-then-Optimize
firstpage: 548
lastpage: 575
page: 548-575
order: 548
cycles: false
bibtex_author: Dronavajjala, Chandra
author:
- given: Chandra
  family: Dronavajjala
date: 2026-08-30
address:
container-title: Proceedings of the Fifteenth Symposium on Conformal and Probabilistic
  Prediction with Applications
volume: '329'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 8
  - 30
pdf: https://raw.githubusercontent.com/mlresearch/v329/main/assets/dronavajjala26a/dronavajjala26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
