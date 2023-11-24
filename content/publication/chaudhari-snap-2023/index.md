---
title: 'SNAP: Efficient Extraction of Private Properties with Poisoning'
authors:
- Harsh Chaudhari
- John Abascal
- Alina Oprea
- Matthew Jagielski
- Florian Tramèr
- Jonathan Ullman
date: '2023-05-01'
publishDate: '2023-11-24T10:39:01.900613Z'
publication_types:
- paper-conference
publication: '*2023 IEEE Symposium on Security and Privacy (SP)*'
doi: 10.1109/SP46215.2023.10179334
abstract: Property inference attacks allow an adversary to extract global properties
  of the training dataset from a machine learning model. Such attacks have privacy
  implications for data owners sharing their datasets to train machine learning models.
  Several existing approaches for property inference attacks against deep neural networks
  have been proposed [1] –[3], but they all rely on the attacker training a large
  number of shadow models, which induces a large computational overhead.In this paper,
  we consider the setting of property inference attacks in which the attacker can
  poison a subset of the training dataset and query the trained target model. Motivated
  by our theoretical analysis of model confidences under poisoning, we design an efficient
  property inference attack, SNAP, which obtains higher attack success and requires
  lower amounts of poisoning than the state-of-the-art poisoning-based property inference
  attack by Mahloujifar et al. [3]. For example, on the Census dataset, SNAP achieves
  34% higher success rate than [3] while being 56.5× faster. We also extend our attack
  to infer whether a certain property was present at all during training and estimate
  the exact proportion of a property of interest efficiently. We evaluate our attack
  on several properties of varying proportions from four datasets and demonstrate
  SNAP’s generality and effectiveness.
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10179334
---
