---
title: Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech
  Synthesis
authors:
- Ye Jia
- Yu Zhang
- Ron J. Weiss
- Quan Wang
- Jonathan Shen
- Fei Ren
- Zhifeng Chen
- Patrick Nguyen
- Ruoming Pang
- Ignacio Lopez Moreno
- Yonghui Wu
date: '2019-01-02'
publishDate: '2023-11-24T10:38:57.834267Z'
publication_types:
- article-journal
abstract: 'We describe a neural network-based system for text-to-speech (TTS) synthesis
  that is able to generate speech audio in the voice of many different speakers, including
  those unseen during training. Our system consists of three independently trained
  components: (1) a speaker encoder network, trained on a speaker verification task
  using an independent dataset of noisy speech from thousands of speakers without
  transcripts, to generate a fixed-dimensional embedding vector from seconds of reference
  speech from a target speaker; (2) a sequence-to-sequence synthesis network based
  on Tacotron 2, which generates a mel spectrogram from text, conditioned on the speaker
  embedding; (3) an auto-regressive WaveNet-based vocoder that converts the mel spectrogram
  into a sequence of time domain waveform samples. We demonstrate that the proposed
  model is able to transfer the knowledge of speaker variability learned by the discriminatively-trained
  speaker encoder to the new task, and is able to synthesize natural speech from speakers
  that were not seen during training. We quantify the importance of training the speaker
  encoder on a large and diverse speaker set in order to obtain the best generalization
  performance. Finally, we show that randomly sampled speaker embeddings can be used
  to synthesize speech in the voice of novel speakers dissimilar from those used in
  training, indicating that the model has learned a high quality speaker representation.'
tags:
- to-read
- Computer Science - Machine Learning
- Computer Science - Sound
- Computer Science - Computation and Language
- Electrical Engineering and Systems Science - Audio and Speech Processing
links:
- name: URL
  url: http://arxiv.org/abs/1806.04558
---
