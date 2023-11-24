---
title: How To Backdoor Federated Learning
authors:
- Eugene Bagdasaryan
- Andreas Veit
- Yiqing Hua
- Deborah Estrin
- Vitaly Shmatikov
date: '2020-06-03'
publishDate: '2023-11-24T10:39:01.608209Z'
publication_types:
- paper-conference
publication: '*Proceedings of the Twenty Third International Conference on Artificial
  Intelligence and Statistics*'
abstract: Federated models are created by aggregating model updates submittedby participants.  To
  protect confidentiality of the training data,the aggregator by design has no visibility
  into how these updates aregenerated.  We show that this makes federated learning
  vulnerable to amodel-poisoning attack that is significantly more powerful than poisoningattacks
  that target only the training data.A single or multiple malicious participants can
  use modelreplacement to introduce backdoor functionality into the joint model,e.g.,
  modify an image classifier so that it assigns an attacker-chosenlabel to images
  with certain features, or force a word predictor tocomplete certain sentences with
  an attacker-chosen word.  We evaluatemodel replacement under different assumptions
  for the standardfederated-learning tasks and show that it greatly outperformstraining-data
  poisoning.Federated learning employs secure aggregation to protect confidentialityof
  participants’ local models and thus cannot detect anomalies inparticipants’ contributions
  to the joint model.  To demonstrate thatanomaly detection would not have been effective
  in any case, we alsodevelop and evaluate a generic constrain-and-scale technique
  thatincorporates the evasion of defenses into the attacker’s loss functionduring
  training.
links:
- name: URL
  url: https://proceedings.mlr.press/v108/bagdasaryan20a.html
---
