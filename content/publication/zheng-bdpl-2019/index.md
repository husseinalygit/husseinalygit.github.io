---
title: 'BDPL: A Boundary Differentially Private Layer Against Machine Learning Model
  Extraction Attacks'
authors:
- H. Zheng
- Q. Ye
- H. Hu
- C. Fang
- J. Shi
date: '2019-01-01'
publishDate: '2023-11-24T10:39:01.356951Z'
publication_types:
- article-journal
doi: 10.1007/978-3-030-29959-0_4
abstract: Machine learning models trained by large volume of proprietary data and
  intensive computational resources are valuable assets of their owners, who merchandise
  these models to third-party users through prediction service API. However, existing
  literature shows that model parameters are vulnerable to extraction attacks which
  accumulate a large number of prediction queries and their responses to train a replica
  model. As countermeasures, researchers have proposed to reduce the rich API output,
  such as hiding the precise confidence level of the prediction response. Nonetheless,
  even with response being only one bit, an adversary can still exploit fine-tuned
  queries with differential property to infer the decision boundary of the underlying
  model. In this paper, we propose boundary differential privacy (ϵ -BDP) as a solution
  to protect against such attacks by obfuscating the prediction responses near the
  decision boundary. ϵ -BDP guarantees an adversary cannot learn the decision boundary
  by a predefined precision no matter how many queries are issued to the prediction
  API. We design and prove a perturbation algorithm called boundary randomized response
  that can achieve ϵ -BDP. The effectiveness and high utility of our solution against
  model extraction attacks are verified by extensive experiments on both linear and
  non-linear models. © 2019, Springer Nature Switzerland AG.
---
