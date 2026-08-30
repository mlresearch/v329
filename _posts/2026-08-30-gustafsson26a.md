---
title: Well-calibrated probabilities for prediction sets
abstract: Conformal prediction is a model-agnostic, distribution-free statistical
  framework that outputs prediction sets such that, for each prediction, the probability
  that the true label falls outside the set is less than a user-specified tolerance,
  $\varepsilon$. Notably, this guarantee holds conditionally on the calibration dataset
  and thus only prior to observing a new object. We present a method that assigns
  prediction probabilities to any set prediction. These probabilities approximate
  the true conditional probability that the label lies within the set, and converge
  to it with increasing data. Venn-Abers predictors are (multi)-probabilistic predictors
  combining Venn-predictors and isotonic regression to output well-calibrated probabilities
  for binary prediction problems. We propose applying Venn-Abers to the constructed
  prediction sets from conformal prediction and, thereby, assigning a well-calibrated
  probability of the true label being in that set. We further introduce a novel self-consistent
  scoring rule for Venn-Abers predictors, which treats a predicted probability as
  being as likely as the event it postulates.
section: Calibration, Regression and Predictive Distributions
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gustafsson26a
month: 0
tex_title: Well-calibrated probabilities for prediction sets
firstpage: 222
lastpage: 248
page: 222-248
order: 222
cycles: false
bibtex_author: Gustafsson, Oskar and Pavia, John and K{\"a}ll, Styrbj{\"o}rn and Szabadv{\'a}ry,
  Johan Hallberg and Lundstr{\"o}m, Jens and Ahlberg, Ernst
author:
- given: Oskar
  family: Gustafsson
- given: John
  family: Pavia
- given: Styrbjörn
  family: Käll
- given: Johan Hallberg
  family: Szabadváry
- given: Jens
  family: Lundström
- given: Ernst
  family: Ahlberg
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
pdf: https://raw.githubusercontent.com/mlresearch/v329/main/assets/gustafsson26a/gustafsson26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
