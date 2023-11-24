---
title: Early Exit Ensembles for Uncertainty Quantification
authors:
- Lorena Qendro
- Alexander Campbell
- Pietro Lio
- Cecilia Mascolo
date: '2021-11-28'
publishDate: '2023-11-24T10:39:01.186401Z'
publication_types:
- paper-conference
publication: '*Proceedings of Machine Learning for Health*'
abstract: Deep learning is increasingly used for decision-making in health applications.
  However, commonly used deep learning models are deterministic and are unable to
  provide any estimate of predictive uncertainty. Quantifying model uncertainty is
  crucial for reducing the risk of misdiagnosis by informing practitioners of low-confident
  predictions. To address this issue, we propose early exit ensembles, a novel framework
  capable of capturing predictive uncertainty via an implicit ensemble of early exits.
  We evaluate our approach on the task of classification using three state-of-the-art
  deep learning architectures applied to three medical imaging datasets. Our experiments
  show that early exit ensembles provide better-calibrated uncertainty compared to
  Monte Carlo dropout and deep ensembles using just a single forward-pass of the model.
  Depending on the dataset and baseline, early exit ensembles can improve uncertainty
  metrics up to 2x, while increasing accuracy by up to 2% over its single model counterpart.
  Finally, our results suggest that by providing well-calibrated predictive uncertainty
  for both in- and out-of-distribution inputs, early exit ensembles have the potential
  to improve trustworthiness of models in high-risk medical decision-making.
links:
- name: URL
  url: https://proceedings.mlr.press/v158/qendro21a.html
---
