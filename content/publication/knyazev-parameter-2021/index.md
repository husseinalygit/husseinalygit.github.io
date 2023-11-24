---
title: Parameter Prediction for Unseen Deep Architectures
authors:
- Boris Knyazev
- Michal Drozdzal
- Graham W Taylor
- Adriana Romero Soriano
date: '2021-01-01'
publishDate: '2023-11-24T10:39:01.507750Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: Deep learning has been successful in automating the design of features in
  machine learning pipelines. However, the algorithms optimizing neural network parameters
  remain largely hand-designed and computationally inefficient. We study if we can
  use deep learning to directly predict these parameters by exploiting the past knowledge
  of training other networks. We introduce a large-scale dataset of diverse computational
  graphs of neural architectures - DeepNets-1M - and use it to explore parameter prediction
  on CIFAR-10 and ImageNet. By leveraging advances in graph neural networks, we propose
  a hypernetwork that can predict performant parameters in a single forward pass taking
  a fraction of a second, even on a CPU. The proposed model achieves surprisingly
  good performance on unseen and diverse networks. For example, it is able to predict
  all 24 million parameters of a ResNet-50 achieving a 60% accuracy on CIFAR-10. On
  ImageNet, top-5 accuracy of some of our networks approaches 50%. Our task along
  with the model and results can potentially lead to a new, more computationally efficient
  paradigm of training networks. Our model also learns a strong representation of
  neural architectures enabling their analysis.
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper_files/paper/2021/hash/f6185f0ef02dcaec414a3171cd01c697-Abstract.html
---
