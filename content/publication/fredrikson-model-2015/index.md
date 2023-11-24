---
title: Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures
authors:
- Matt Fredrikson
- Somesh Jha
- Thomas Ristenpart
date: '2015-10-12'
publishDate: '2023-11-24T10:39:00.289936Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 22nd ACM SIGSAC Conference on Computer and Communications
  Security*'
doi: 10.1145/2810103.2813677
abstract: "Machine-learning (ML) algorithms are increasingly utilized in privacy-sensitive
  applications such as predicting lifestyle choices, making medical diagnoses, and
  facial recognition. In a model inversion attack, recently introduced in a case study
  of linear classifiers in personalized medicine by Fredrikson et al., adversarial
  access to an ML model is abused to learn sensitive genomic information about individuals.
  Whether model inversion attacks apply to settings outside theirs, however, is unknown.
  We develop a new class of model inversion attack that exploits confidence values
  revealed along with predictions. Our new attacks are applicable in a variety of
  settings, and we explore two in depth: decision trees for lifestyle surveys as used
  on machine-learning-as-a-service systems and neural networks for facial recognition.
  In both cases confidence values are revealed to those with the ability to make prediction
  queries to models. We experimentally show attacks that are able to estimate whether
  a respondent in a lifestyle survey admitted to cheating on their significant other
  and, in the other context, show how to recover recognizable images of people's faces
  given only their name and access to the ML model. We also initiate experimental
  exploration of natural countermeasures, investigating a privacy-aware decision tree
  training algorithm that is a simple variant of CART learning, as well as revealing
  only rounded confidence values. The lesson that emerges is that one can avoid these
  kinds of MI attacks with negligible degradation to utility."
tags:
- machine learning
- privacy
- attacks
links:
- name: URL
  url: https://doi.org/10.1145/2810103.2813677
---
