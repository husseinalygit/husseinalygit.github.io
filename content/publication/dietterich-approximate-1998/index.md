---
title: Approximate Statistical Tests for Comparing Supervised Classification Learning
  Algorithms
authors:
- Thomas G. Dietterich
date: '1998-10-01'
publishDate: '2023-11-24T10:38:59.839119Z'
publication_types:
- article-journal
doi: 10.1162/089976698300017197
abstract: "This article reviews five approximate statistical tests for determining
  whether one learning algorithm outperforms another on a particular learning task.
  These test sare compared experimentally to determine their probability of incorrectly
  detecting a difference when no difference exists (type I error). Two widely used
  statistical tests are shown to have high probability of type I error in certain
  situations and should never be used: a test for the difference of two proportions
  and a paired-differences t test based on taking several random train-test splits.
  A third test, a paired-differences t test based on 10-fold cross-validation, exhibits
  somewhat elevated probability of type I error. A fourth test, McNemar's test, is
  shown to have low type I error. The fifth test is a new test, 5 × 2 cv, based on
  five iterations of twofold cross-validation. Experiments show that this test also
  has acceptable type I error. The article also measures the power (ability to detect
  algorithm differences when they do exist) of these tests. The cross-validated t
  test is the most powerful. The 5×2 cv test is shown to be slightly more powerful
  than McNemar's test. The choice of the best test is determined by the computational
  cost of running the learning algorithm. For algorithms that can be executed only
  once, Mc-Nemar's test is the only test with acceptable type I error. For algorithms
  that can be executed 10 times, the 5 × 2 cv test is recommended, because it is slightly
  more powerful and because it directly measures variation due to the choice of training
  set."
tags:
- _tablet_modified
---
