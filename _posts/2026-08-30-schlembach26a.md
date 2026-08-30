---
title: Corrected Max-Rank for Finite-Sample Conformal Prediction
abstract: Max-Rank is a dependence-aware family-wise error rate correction method
  used to construct hyperrectangular prediction regions in conformal multi-target
  regression. It ranks dimension-wise internal nonconformity scores and uses the largest
  dimension-wise rank as a joint nonconformity score, often achieving smaller regions
  than Bonferroni correction. In this paper, we revisit the finite-sample validity
  of Max-Rank and distinguish between the Max-Rank rule in the rank space and its
  implementation in the dimension-wise score space. The rank-space rule is valid.
  Its original score-space implementation, however, is incorrect and loses the finite-sample
  coverage guarantee. The implementation translates a rank threshold q into the qth
  dimension-wise calibration score. We show that this threshold is one order statistic
  too small and that the correct score threshold is the (q + 1)st dimension-wise calibration
  score, with the usual +$\infty$ convention when no large enough order statistic
  exists. We propose Corrected Max-Rank, a straightforward modification that uses
  the correct rank-to-score implementation. We prove that the corrected implementation
  satisfies the desired finite-sample coverage guarantee under exchangeability and
  dimension-separable internal scores. Experiments on synthetic multidimensional internal
  score distributions confirm that the original implementation can exceed the targeted
  error rate, especially for small calibration sets and a larger number of output
  dimensions. Corrected Max-Rank restores validity at the cost of slightly wider prediction
  regions.
section: Foundations and Theory
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schlembach26a
month: 0
tex_title: Corrected Max-Rank for Finite-Sample Conformal Prediction
firstpage: 199
lastpage: 221
page: 199-221
order: 199
cycles: false
bibtex_author: Schlembach, Filip and Smirnov, Evgueni and H. M. Winands, Mark
author:
- given: Filip
  family: Schlembach
- given: Evgueni
  family: Smirnov
- given: Mark
  family: H. M. Winands
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
pdf: https://raw.githubusercontent.com/mlresearch/v329/main/assets/schlembach26a/schlembach26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
