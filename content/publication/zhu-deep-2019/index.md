---
title: Deep Leakage from Gradients
authors:
- Ligeng Zhu
- Zhijian Liu
- Song Han
date: '2019-01-01'
publishDate: '2023-11-24T10:39:00.165495Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: "Passing gradient is a widely used scheme in  modern multi-node learning
  system (e.g, distributed training, collaborative learning). In a long time, people
  used to believe that gradients are safe to share: i.e, the training set will not
  be leaked by gradient sharing.  However, in this paper, we show that we can obtain
  the private training set from the publicly shared gradients.  The leaking only takes
  few gradient steps to process and can obtain the original training set instead of
  look-alike alternatives.  We name this leakage as textitdeep leakage from gradient\
  \  and practically validate the effectiveness of our algorithm on both computer
  vision and natural language processing tasks. We empirically show that our attack
  is much stronger than previous approaches and thereby and raise people's awareness
  to rethink the gradients' safety. We also discuss some possible strategies to defend
  this deep leakage."
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper/2019/hash/60a6c4002cc7b29142def8871531281a-Abstract.html
---
