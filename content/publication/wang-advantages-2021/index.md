---
title: 'Advantages of direct input-to-output connections in neural networks: The Elman
  network for stock index forecasting'
authors:
- Yaoli Wang
- Lipo Wang
- Fangjun Yang
- Wenxia Di
- Qing Chang
date: '2021-02-08'
publishDate: '2023-11-24T10:39:00.773843Z'
publication_types:
- article-journal
doi: 10.1016/j.ins.2020.09.031
abstract: The Elman neural network (ElmanNN) is well-known for its capability of processing
  dynamic information, which has led to successful applications in stock forecasting.
  In this paper, we introduce direct input-to-output connections (DIOCs) into the
  ElmanNN and show that the proposed Elman neural network with DIOCs (Elman-DIOCs)
  significantly out-performs the original ElmanNN without such DIOCs. Four different
  global stock indices, i.e., the Shanghai Stock Exchange (SSE) Composite Index, the
  Korea Stock Price Index (KOSPI), the Nikkei 225 Index (Nikkei225), and the Standard
  & Poor’s 500 Index (SPX), are used to demonstrate the affecacy of the Elman-DIOCs
  in time-series prediction. We systematically evaluate 8 models, depending whether
  or not there are hidden layer biases, whether or not there are output layer biases,
  and whether or not there are DIOCs. The experimental results show that DIOCs lead
  to much better prediction accuracy, while requiring fewer than a half of the hidden
  neurons. Take the SPX index, for example - the root mean squared error (RMSE) and
  the mean absolute error (MAE) of the Elman-DIOCs are improved by 44.2% and 41.1%,
  respectively, compared to the ElmanNN, and 65.6% and 60.8%, respectively, compared
  to the multi-layer perceptron (MLP). We argue that (1) DIOCs can always help to
  improve accuracy, while reducing network complexity and computational burden, as
  long as the problem at hand (either regression or classification) has linear components,
  and (2) most real-world applications contain linear components. Therefore DIOCs
  will be almost always beneficial in any types of neural networks for classification
  or regression. We also point out that in rare cases where the problem at hand is
  entirely nonlinear, DIOCs should not be used.
tags:
- Direct input-to-output connections (DIOCs)
- Stock index forecasting
- The Elman neural network
- Direct Link
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0020025520309415
---
