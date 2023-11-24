---
title: The (Un)reliability of Saliency Methods
authors:
- Pieter-Jan Kindermans
- Sara Hooker
- Julius Adebayo
- Maximilian Alber
- Kristof T. Schütt
- Sven Dähne
- Dumitru Erhan
- Been Kim
date: '2019-01-01'
publishDate: '2023-11-24T10:38:59.808389Z'
publication_types:
- chapter
publication: '*Explainable AI: Interpreting, Explaining and Visualizing Deep Learning*'
doi: 10.1007/978-3-030-28954-6_14
abstract: Saliency methods aim to explain the predictions of deep neural networks.
  These methods lack reliability when the explanation is sensitive to factors that
  do not contribute to the model prediction. We use a simple and common pre-processing
  step which can be compensated for easily—adding a constant shift to the input data—to
  show that a transformation with no effect on how the model makes the decision can
  cause numerous methods to attribute incorrectly. In order to guarantee reliability,
  we believe that the explanation should not change when we can guarantee that two
  networks process the images in identical manners. We show, through several examples,
  that saliency methods that do not satisfy this requirement result in misleading
  attribution. The approach can be seen as a type of unit test; we construct a narrow
  ground truth to measure one stated desirable property. As such, we hope the community
  will embrace the development of additional tests.
links:
- name: URL
  url: https://doi.org/10.1007/978-3-030-28954-6_14
---
