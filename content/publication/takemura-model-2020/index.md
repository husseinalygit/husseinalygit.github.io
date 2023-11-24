---
title: Model Extraction Attacks on Recurrent Neural Networks
authors:
- Tatsuya Takemura
- Naoto Yanai
- Toru Fujiwara
date: '2020-01-01'
publishDate: '2023-11-24T10:39:01.336545Z'
publication_types:
- article-journal
doi: 10.2197/ipsjjip.28.1010
abstract: Model extraction attacks are an attack in which an adversary utilizes a
  query access to the target model to obtain a new model whose performance is equivalent
  to the target model efficiently, i.e., fewer datasets and computational resources
  than those of the target model. Existing works have dealt with only simple deep
  neural networks (DNNs), e.g., only three layers, as targets of model extraction
  attacks, and hence are not aware of the effectiveness of recurrent neural networks
  (RNNs) in dealing with time-series data. In this work, we shed light on the threats
  of model extraction attacks on RNNs. We discuss whether a model with a higher accuracy
  can be extracted with a simple RNN from a long short-term memory (LSTM), which is
  a more complicated and powerful type of RNN. Specifically, we tackle the following
  problems. First, in case of a classification task, such as image recognition, extraction
  of an RNN model without final outputs from an LSTM model is presented by utilizing
  outputs halfway through the sequence. Next, in case of a regression task such as
  weather forecasting, a new attack by newly configuring a loss function is presented.
  We conduct experiments on our model extraction attacks on an RNN and an LSTM trained
  with publicly available academic datasets. We then show that a model with a higher
  accuracy can be extracted efficiently, especially through configuring a loss function
  and a more complex architecture different from the target model.
tags:
- long short-term memory
- deep neural networks
- model extraction attacks
- recurrent neural networks
---
