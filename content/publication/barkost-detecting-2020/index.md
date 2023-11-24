---
title: Detecting EV Charging From Hourly Smart Meter Data
authors:
- Per Harald Barkost
date: '2020-05-15'
publishDate: '2023-11-24T10:39:02.026996Z'
publication_types:
- thesis
abstract: Detecting electrical vehicle (EV) charging from smart meter data (EV detection)
  is a highly relevant problem for the distribution system operators (DSOs), especially
  with the expected growth of EVs worldwide. There are several reasons why DSOs may
  want to detect EV charging. In the present day, the main motivation is to reduce
  the total load on the grid in high demand periods. This can be achieved by giving
  incentives to EV owners to charge their EVs in low demand periods. In the future,
  it is also anticipated that EVs can act as an energy reservoir, which can be a further
  motivation for EV detection.   In this thesis, we explore two problems of EV detection.
  First, can we detect customers that charge an EV at home (EV load profiling)? Second,
  can we detect when an EV is charging (EV event detection)? To solve these problems,
  we analyze smart meter data provided by Eidsiva (a DSO from Norway).    For the
  problem of load profiling, we propose, a feature-based  Gaussian mixture modeling
  of weekly load profiles. The results are promising, showing that some EV owners
  have unique power consumption patterns.    For the problem of event detection, we
  propose a modified version of UTime for EV event detection. UTime is a fully convolutional
  feed-forward neural network, initially proposed for sleep stage segmentation. The
  modified UTime is compared with previously proposed convolutional architectures
  for the problem of EV detection. Results show that UTime for EV detection outperforms
  the previous models on a generated labeled dataset.     In order to solve the problem
  of EV detection, a labeled data set with ground truth is crucial. Unfortunately,
  this is lacking in this thesis. We resolve this issue by proposing a method of generating
  a labeled data set by combining two data sources. Even though the method show promise
  and models seem to generalize for an unlabeled dataset, more verification is needed
  to state conclusively that our proposed method is efficient.
links:
- name: URL
  url: https://munin.uit.no/handle/10037/19274
---
