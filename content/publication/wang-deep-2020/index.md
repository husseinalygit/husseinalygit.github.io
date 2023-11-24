---
title: A Deep Generative Model for Non-Intrusive Identification of EV Charging Profiles
authors:
- Shengyi Wang
- Liang Du
- Jin Ye
- Dongbo Zhao
date: '2020-11-01'
publishDate: '2023-11-24T10:39:02.269903Z'
publication_types:
- article-journal
doi: 10.1109/TSG.2020.2998080
abstract: The proliferation of electric vehicles (EVs) brings environmental benefits
  and technical challenges to power grids. An identification algorithm which can accurately
  extract individual EV charging profiles out of widely available smart meter measurements
  has attracted great interests. This paper proposes a non-intrusive identification
  framework for EV charging profile extraction, which is driven by deep generative
  models (DGM). First, the proposed DGM is designed as a representation layer embedded
  into the Markov process and used to model the joint probability distribution of
  available time-series data. A novel contribution is to approximate posterior distributions
  by neural networks whose parameters are obtained by variational inference and supervised
  learning. Second, the EV charging status is inferred from the DGM via dynamic programming.
  Lastly, the desired EV charging profile can be reconstructed by the rated power
  of EV models and inferred status. Compared with the benchmark Hidden Markov Models,
  the proposed framework can better handle noise in data with less computational complexity
  and better overall accuracy performances with smaller recall. The proposed framework
  is validated by numerical experiments on the Pecan Street dataset.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9102286
---
