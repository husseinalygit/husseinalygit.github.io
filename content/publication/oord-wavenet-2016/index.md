---
title: 'WaveNet: A Generative Model for Raw Audio'
authors:
- Aaron van den Oord
- Sander Dieleman
- Heiga Zen
- Karen Simonyan
- Oriol Vinyals
- Alex Graves
- Nal Kalchbrenner
- Andrew Senior
- Koray Kavukcuoglu
date: '2016-09-19'
publishDate: '2023-11-24T10:38:57.819901Z'
publication_types:
- article-journal
abstract: This paper introduces WaveNet, a deep neural network for generating raw
  audio waveforms. The model is fully probabilistic and autoregressive, with the predictive
  distribution for each audio sample conditioned on all previous ones; nonetheless
  we show that it can be efficiently trained on data with tens of thousands of samples
  per second of audio. When applied to text-to-speech, it yields state-of-the-art
  performance, with human listeners rating it as significantly more natural sounding
  than the best parametric and concatenative systems for both English and Mandarin.
  A single WaveNet can capture the characteristics of many different speakers with
  equal fidelity, and can switch between them by conditioning on the speaker identity.
  When trained to model music, we find that it generates novel and often highly realistic
  musical fragments. We also show that it can be employed as a discriminative model,
  returning promising results for phoneme recognition.
tags:
- Computer Science - Machine Learning
- Computer Science - Sound
links:
- name: URL
  url: http://arxiv.org/abs/1609.03499
---
