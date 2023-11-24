---
title: Model Reconstruction from Model Explanations
authors:
- Smitha Milli
- Ludwig Schmidt
- Anca D. Dragan
- Moritz Hardt
date: '2019-01-29'
publishDate: '2023-11-24T10:39:01.321703Z'
publication_types:
- paper-conference
publication: '*Proceedings of the Conference on Fairness, Accountability, and Transparency*'
doi: 10.1145/3287560.3287562
abstract: We show through theory and experiment that gradient-based explanations of
  a model quickly reveal the model itself. Our results speak to a tension between
  the desire to keep a proprietary model secret and the ability to offer model explanations.
  On the theoretical side, we give an algorithm that provably learns a two-layer ReLU
  network in a setting where the algorithm may query the gradient of the model with
  respect to chosen inputs. The number of queries is independent of the dimension
  and nearly optimal in its dependence on the model size. Of interest not only from
  a learning-theoretic perspective, this result highlights the power of gradients
  rather than labels as a learning primitive. Complementing our theory, we give effective
  heuristics for reconstructing models from gradient explanations that are orders
  of magnitude more query-efficient than reconstruction attacks relying on prediction
  interfaces.
tags:
- machine learning
- security
- privacy
- Explanations
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3287560.3287562
---
