---
title: On the Impact of Side Information on Smart Meter Privacy-Preserving Methods
authors:
- Mohammadhadi Shateri
- Francisco Messina
- Pablo Piantanida
- Fabrice Labeau
date: '2020-11-01'
publishDate: '2023-11-24T10:39:01.704225Z'
publication_types:
- paper-conference
publication: '*2020 IEEE International Conference on Communications, Control, and
  Computing Technologies for Smart Grids (SmartGridComm)*'
doi: 10.1109/SmartGridComm47815.2020.9302948
abstract: 'Smart meters (SMs) can pose privacy threats for consumers, an issue that
  has received significant attention in recent years. This paper studies the impact
  of Side Information (SI) on the performance of possible attacks to real-time privacy-preserving
  algorithms for SMs. In particular, we consider a deep adversarial learning framework,
  in which the desired releaser, which is a Recurrent Neural Network (RNN), is trained
  by fighting against an adversary network until convergence. To define the objective
  for training, two different approaches are considered: the Causal Adversarial Learning
  (CAL) and the Directed Information (DI)-based learning. The main difference between
  these approaches relies on how the privacy term is measured during the training
  process. The releaser in the CAL method, disposing of supervision from the actual
  values of the private variables and feedback from the adversary performance, tries
  to minimize the adversary log-likelihood. On the other hand, the releaser in the
  DI approach completely relies on the feedback received from the adversary and is
  optimized to maximize its uncertainty. The performance of these two algorithms is
  evaluated empirically using real-world SMs data, considering an attacker with access
  to SI (e.g., the day of the week) that tries to infer the occupancy status from
  the released SMs data. The results show that, although they perform similarly when
  the attacker does not exploit the SI, in general, the CAL method is less sensitive
  to the inclusion of SI. However, in both cases, privacy levels are significantly
  affected, particularly when multiple sources of SI are included.'
tags:
- Training
- Privacy
- Optimization
- Data privacy
- Smart grids
- Power demand
- Random variables
---
