---
title: 'Too Good to Conform: The Inverse Quality Paradox in Counterfactual Filtering'
abstract: 'As machine learning models enter high-stakes decision-making, explanations
  must be interpretable, reliable, and uncertainty-aware (Löfström et al., 2024, 2026).
  Counterfactuals (CFs) are a prominent explanation form, but their plausibility remains
  difficult to guarantee (Guidotti, 2024). Conformal prediction (Vovk et al., 2022)
  addresses this through generate-then-filter, which validates candidates post-hoc
  (Bates et al., 2023; Maalej et al., 2025; Adams et al., 2025), or filter-then-generate,
  which incorporates conformal constraints into generation (Altmeyer et al., 2024;
  Bilkhoo et al., 2025). We study the former. Although nonconformity-measure (NCM)
  design is actively studied in other conformal settings (Narteni et al., 2026), its
  role as a structural failure point in counterfactual filtering remains unexplored.
  We show that an NCM assigning greater nonconformity to candidates closer to xi can
  systematically reject the most proximal valid CFs — as generator quality (proximity
  to xi among candidates achieving the desired prediction change) improves, nonconformity
  increases, producing an inverse quality paradox. Our contributions are to: (i) formalise
  this failure for the reciprocal-distance score Aprox; (ii) show that it can reject
  reference-supported candidates while accepting candidates outside the data-supported
  region; and (iii) demonstrate that a score AR anchored to a fixed in-distribution
  reference set removes this dependence on xi and retains standard conformal validity
  under exchangeability.'
section: Extended Abstracts
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rabia-yapicioglu26a
month: 0
tex_title: 'Too Good to Conform: The Inverse Quality Paradox in Counterfactual Filtering'
firstpage: 1073
lastpage: 1075
page: 1073-1075
order: 1073
cycles: false
bibtex_author: Rabia Yapicioglu, Fatima and Srinivasan, Abhishek and Carlos Andresen,
  Juan and Bostr{\"o}m, Henrik
author:
- given: Fatima
  family: Rabia Yapicioglu
- given: Abhishek
  family: Srinivasan
- given: Juan
  family: Carlos Andresen
- given: Henrik
  family: Boström
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
pdf: https://raw.githubusercontent.com/mlresearch/v329/main/assets/rabia-yapicioglu26a/rabia-yapicioglu26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
