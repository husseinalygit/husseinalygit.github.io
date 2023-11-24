---
title: Property Inference Attacks on Fully Connected Neural Networks using Permutation
  Invariant Representations
authors:
- Karan Ganju
- Qi Wang
- Wei Yang
- Carl A. Gunter
- Nikita Borisov
date: '2018-10-15'
publishDate: '2023-11-24T10:39:00.316920Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications
  Security*'
doi: 10.1145/3243734.3243834
abstract: With the growing adoption of machine learning, sharing of learned models
  is becoming popular. However, in addition to the prediction properties the model
  producer aims to share, there is also a risk that the model consumer can infer other
  properties of the training data the model producer did not intend to share. In this
  paper, we focus on the inference of global properties of the training data, such
  as the environment in which the data was produced, or the fraction of the data that
  comes from a certain class, as applied to white-box Fully Connected Neural Networks
  (FCNNs). Because of their complexity and inscrutability, FCNNs have a particularly
  high risk of leaking unexpected information about their training sets; at the same
  time, this complexity makes extracting this information challenging. We develop
  techniques that reduce this complexity by noting that FCNNs are invariant under
  permutation of nodes in each layer. We develop our techniques using representations
  that capture this invariance and simplify the information extraction task. We evaluate
  our techniques on several synthetic and standard benchmark datasets and show that
  they are very effective at inferring various data properties. We also perform two
  case studies to demonstrate the impact of our attack. In the first case study we
  show that a classifier that recognizes smiling faces also leaks information about
  the relative attractiveness of the individuals in its training set. In the second
  case study we show that a classifier that recognizes Bitcoin mining from performance
  counters also leaks information about whether the classifier was trained on logs
  from machines that were patched for the Meltdown and Spectre attacks.
tags:
- neural networks
- permutation equivalence
- property inference
links:
- name: URL
  url: https://doi.org/10.1145/3243734.3243834
---
