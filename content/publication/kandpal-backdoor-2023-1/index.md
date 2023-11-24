---
title: Backdoor Attacks for In-Context Learning with Language Models
authors:
- Nikhil Kandpal
- Matthew Jagielski
- Florian Tramèr
- Nicholas Carlini
date: '2023-07-27'
publishDate: '2023-11-24T10:39:01.592917Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: "Because state-of-the-art language models are expensive to train, most practitioners
  must make use of one of the few publicly available language models or language model
  APIs. This consolidation of trust increases the potency of backdoor attacks, where
  an adversary tampers with a machine learning model in order to make it perform some
  malicious behavior on inputs that contain a predefined backdoor trigger. We show
  that the in-context learning ability of large language models significantly complicates
  the question of developing backdoor attacks, as a successful backdoor must work
  against various prompting strategies and should not affect the model's general purpose
  capabilities. We design a new attack for eliciting targeted misclassification when
  language models are prompted to perform a particular target task and demonstrate
  the feasibility of this attack by backdooring multiple large language models ranging
  in size from 1.3 billion to 6 billion parameters. Finally we study defenses to mitigate
  the potential harms of our attack: for example, while in the white-box setting we
  show that fine-tuning models for as few as 500 steps suffices to remove the backdoor
  behavior, in the black-box setting we are unable to develop a successful defense
  that relies on prompt engineering alone."
tags:
- Computer Science - Cryptography and Security
links:
- name: URL
  url: http://arxiv.org/abs/2307.14692
---
