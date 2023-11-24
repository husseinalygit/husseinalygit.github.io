---
title: 'TabularNet: A Neural Network Architecture for Understanding Semantic Structures
  of Tabular Data'
authors:
- Lun Du
- Fei Gao
- Xu Chen
- Ran Jia
- Junshan Wang
- Jiang Zhang
- Shi Han
- Dongmei Zhang
date: '2021-08-14'
publishDate: '2023-11-24T10:39:01.803810Z'
publication_types:
- article-journal
doi: 10.1145/3447548.3467228
abstract: Tabular data are ubiquitous for the widespread applications of tables and
  hence have attracted the attention of researchers to extract underlying information.
  One of the critical problems in mining tabular data is how to understand their inherent
  semantic structures automatically. Existing studies typically adopt Convolutional
  Neural Network (CNN) to model the spatial information of tabular structures yet
  ignore more diverse relational information between cells, such as the hierarchical
  and paratactic relationships. To simultaneously extract spatial and relational information
  from tables, we propose a novel neural network architecture, TabularNet. The spatial
  encoder of TabularNet utilizes the row/column-level Pooling and the Bidirectional
  Gated Recurrent Unit (Bi-GRU) to capture statistical information and local positional
  correlation, respectively. For relational information, we design a new graph construction
  method based on the WordNet tree and adopt a Graph Convolutional Network (GCN) based
  encoder that focuses on the hierarchical and paratactic relationships between cells.
  Our neural network architecture can be a unified neural backbone for different understanding
  tasks and utilized in a multitask scenario. We conduct extensive experiments on
  three classification tasks with two real-world spreadsheet data sets, and the results
  demonstrate the effectiveness of our proposed TabularNet over state-of-the-art baselines.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3447548.3467228
---
