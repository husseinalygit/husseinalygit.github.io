---
title: 'NGBoost: Natural Gradient Boosting for Probabilistic Prediction'
authors:
- Tony Duan
- Avati Anand
- Daisy Yi Ding
- Khanh K. Thai
- Sanjay Basu
- Andrew Ng
- Alejandro Schuler
date: '2020-11-21'
publishDate: '2023-11-24T10:39:00.338050Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 37th International Conference on Machine Learning*'
abstract: We present Natural Gradient Boosting (NGBoost), an algorithm for generic
  probabilistic prediction via gradient boosting. Typical regression models return
  a point estimate, conditional on covariates, but probabilistic regression models
  output a full probability distribution over the outcome space, conditional on the
  covariates. This allows for predictive uncertainty estimation - crucial in applications
  like healthcare and weather forecasting. NGBoost generalizes gradient boosting to
  probabilistic regression by treating the parameters of the conditional distribution
  as targets for a multiparameter boosting algorithm. Furthermore, we show how the
  Natural Gradient is required to correct the training dynamics of our multiparameter
  boosting approach. NGBoost can be used with any base learner, any family of distributions
  with continuous parameters, and any scoring rule. NGBoost matches or exceeds the
  performance of existing methods for probabilistic prediction while offering additional
  benefits in flexibility, scalability, and usability. An open-source implementation
  is available at github.com/stanfordmlgroup/ngboost.
links:
- name: URL
  url: https://proceedings.mlr.press/v119/duan20a.html
---
