---
title: On Embeddings for Numerical Features in Tabular Deep Learning
authors:
- Yury Gorishniy
- Ivan Rubachev
- Artem Babenko
date: '2023-07-26'
publishDate: '2023-11-24T10:39:01.570553Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2203.05556
abstract: 'Recently, Transformer-like deep architectures have shown strong performance
  on tabular data problems. Unlike traditional models, e.g., MLP, these architectures
  map scalar values of numerical features to high-dimensional embeddings before mixing
  them in the main backbone. In this work, we argue that embeddings for numerical
  features are an underexplored degree of freedom in tabular DL, which allows constructing
  more powerful DL models and competing with GBDT on some traditionally GBDT-friendly
  benchmarks. We start by describing two conceptually different approaches to building
  embedding modules: the first one is based on a piecewise linear encoding of scalar
  values, and the second one utilizes periodic activations. Then, we empirically demonstrate
  that these two approaches can lead to significant performance boosts compared to
  the embeddings based on conventional blocks such as linear layers and ReLU activations.
  Importantly, we also show that embedding numerical features is beneficial for many
  backbones, not only for Transformers. Specifically, after proper embeddings, simple
  MLP-like models can perform on par with the attention-based architectures. Overall,
  we highlight embeddings for numerical features as an important design aspect with
  good potential for further improvements in tabular DL.'
tags:
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2203.05556
---
