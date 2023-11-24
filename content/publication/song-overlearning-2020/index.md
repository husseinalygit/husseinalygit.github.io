---
title: Overlearning Reveals Sensitive Attributes
authors:
- Congzheng Song
- Vitaly Shmatikov
date: '2020-02-08'
publishDate: '2023-11-24T10:39:00.303940Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.1905.11742
abstract: \"Overlearning\" means that a model trained for a seemingly simple objective
  implicitly learns to recognize attributes and concepts that are (1) not part of
  the learning objective, and (2) sensitive from a privacy or bias perspective. For
  example, a binary gender classifier of facial images also learns to recognize racestextemdash
  even races that are not represented in the training datatextemdash and identities.
  We demonstrate overlearning in several vision and NLP models and analyze its harmful
  consequences. First, inference-time representations of an overlearned model reveal
  sensitive attributes of the input, breaking privacy protections such as model partitioning.
  Second, an overlearned model can be \"re-purposed\" for a different, privacy-violating
  task even in the absence of the original training data. We show that overlearning
  is intrinsic for some tasks and cannot be prevented by censoring unwanted attributes.
  Finally, we investigate where, when, and why overlearning happens during model training.
tags:
- Computer Science - Machine Learning
- Statistics - Machine Learning
- Computer Science - Neural and Evolutionary Computing
links:
- name: URL
  url: http://arxiv.org/abs/1905.11742
---
