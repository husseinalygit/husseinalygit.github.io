---
title: 'Hopular: Modern Hopfield Networks for Tabular Data'
authors:
- Bernhard Schäfl
- Lukas Gruber
- Angela Bitto-Nemling
- Sepp Hochreiter
date: '2022-06-01'
publishDate: '2023-11-24T10:39:01.689167Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2206.00664
abstract: While Deep Learning excels in structured data as encountered in vision and
  natural language processing, it failed to meet its expectations on tabular data.
  For tabular data, Support Vector Machines (SVMs), Random Forests, and Gradient Boosting
  are the best performing techniques with Gradient Boosting in the lead. Recently,
  we saw a surge of Deep Learning methods that were tailored to tabular data but still
  underperform compared to Gradient Boosting on small-sized datasets. We suggest \"Hopular\",
  a novel Deep Learning architecture for medium- and small-sized datasets, where each
  layer is equipped with continuous modern Hopfield networks. The modern Hopfield
  networks use stored data to identify feature-feature, feature-target, and sample-sample
  dependencies. Hopular's novelty is that every layer can directly access the original
  input as well as the whole training set via stored data in the Hopfield networks.
  Therefore, Hopular can step-wise update its current model and the resulting prediction
  at every layer like standard iterative learning algorithms. In experiments on small-sized
  tabular datasets with less than 1,000 samples, Hopular surpasses Gradient Boosting,
  Random Forests, SVMs, and in particular several Deep Learning methods. In experiments
  on medium-sized tabular data with about 10,000 samples, Hopular outperforms XGBoost,
  CatBoost, LightGBM and a state-of-the art Deep Learning method designed for tabular
  data. Thus, Hopular is a strong alternative to these methods on tabular data.
tags:
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2206.00664
---
