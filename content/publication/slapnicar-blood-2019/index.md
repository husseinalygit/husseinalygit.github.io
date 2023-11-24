---
title: Blood Pressure Estimation from Photoplethysmogram Using a Spectro-Temporal
  Deep Neural Network
authors:
- Gašper Slapničar
- Nejc Mlakar
- Mitja Luštrek
date: '2019-01-01'
publishDate: '2023-11-24T10:38:57.906598Z'
publication_types:
- article-journal
doi: 10.3390/s19153420
abstract: Blood pressure (BP) is a direct indicator of hypertension, a dangerous and
  potentially deadly condition. Regular monitoring of BP is thus important, but many
  people have aversion towards cuff-based devices, and their limitation is that they
  can only be used at rest. Using just a photoplethysmogram (PPG) to estimate BP is
  a potential solution investigated in our study. We analyzed the MIMIC III database
  for high-quality PPG and arterial BP waveforms, resulting in over 700 h of signals
  after preprocessing, belonging to 510 subjects. We then used the PPG alongside its
  first and second derivative as inputs into a novel spectro-temporal deep neural
  network with residual connections. We have shown in a leave-one-subject-out experiment
  that the network is able to model the dependency between PPG and BP, achieving mean
  absolute errors of 9.43 for systolic and 6.88 for diastolic BP. Additionally we
  have shown that personalization of models is important and substantially improves
  the results, while deriving a good general predictive model is difficult. We have
  made crucial parts of our study, especially the list of used subjects and our neural
  network code, publicly available, in an effort to provide a solid baseline and simplify
  potential comparison between future studies on an explicit MIMIC III subset.
tags:
- deep learning
- signal processing
- photoplethysmogram
- blood pressure
- regression
links:
- name: URL
  url: https://www.mdpi.com/1424-8220/19/15/3420
---
