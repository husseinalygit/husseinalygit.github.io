---
title: Greedy Layer-Wise Training of Deep Networks
authors:
- Yoshua Bengio
- Pascal Lamblin
- Dan Popovici
- Hugo Larochelle
date: '2006-01-01'
publishDate: '2023-11-24T10:39:01.038470Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: Recent analyses (Bengio, Delalleau, & Le Roux, 2006; Bengio & Le Cun, 2007)
  of modern nonparametric machine learning algorithms that are kernel machines, such
  as Support Vector Machines (SVMs), graph-based manifold and semi-supervised learning
  algorithms suggest fundamental limitations of some learning algorithms. The problem
  is clear in kernel-based approaches when the kernel is \"local\" (e.g., the Gaussian
  kernel), i.e., K (x, y ) converges to a constant when textbartextbarx - y textbartextbar
  increases. These analyses point to the difficulty of learning \"highly-varying functions\",
  i.e., functions that have a large number of \"variations\" in the domain of interest,
  e.g., they would require a large number of pieces to be well represented by a piecewise-linear
  approximation. Since the number of pieces can be made to grow exponentially with
  the number of factors of variations in the input, this is connected with the well-known
  curse of dimensionality for classical non-parametric learning algorithms (for regression,
  classification and density estimation). If the shapes of all these pieces are unrelated,
  one needs enough examples for each piece in order to generalize properly. However,
  if these shapes are related and can be predicted from each other, \"non-local\"
  learning algorithms have the potential to generalize to pieces not covered by the
  training set. Such ability would seem necessary for learning in complex domains
  such as Artificial Intelligence tasks (e.g., related to vision, language, speech,
  robotics). Kernel machines (not only those with a local kernel) have a shallow architecture,
  i.e., only two levels of data-dependent computational elements. This is also true
  of feedforward neural networks with a single hidden layer (which can become SVMs
  when the number of hidden units becomes large (Bengio, Le Roux, Vincent, Delalleau,
  & Marcotte, 2006)). A serious problem with shallow architectures is that they can
  be very inefficient in terms of the number of computational units (e.g., bases,
  hidden units), and thus in terms of required examples (Bengio & Le Cun, 2007). One
  way to represent a highly-varying function compactly (with few parameters) is through
  the composition of many non-linearities, i.e., with a deep architecture. For example,
  the parity function with d inputs requires O(2d ) examples and parameters to be
  represented by a Gaussian SVM (Bengio et al., 2006), O(d2 ) parameters for a one-hidden-layer
  neural network, O(d) parameters and units for a multi-layer network with O(log2
  d) layers, and O(1) parameters with a recurrent neural network. More generally,
links:
- name: URL
  url: 
    https://papers.nips.cc/paper_files/paper/2006/hash/5da713a690c067105aeb2fae32403405-Abstract.html
---
