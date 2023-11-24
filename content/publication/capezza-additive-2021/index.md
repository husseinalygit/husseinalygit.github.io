---
title: Additive stacking for disaggregate electricity demand forecasting
authors:
- Christian Capezza
- Biagio Palumbo
- Yannig Goude
- Simon N. Wood
- Matteo Fasiolo
date: '2021-06-01'
publishDate: '2023-11-24T10:39:00.568383Z'
publication_types:
- article-journal
doi: 10.1214/20-AOAS1417
abstract: Future grid management systems will coordinate distributed production and
  storage resources to manage, in a cost effective fashion, the increased load and
  variability brought by the electrification of transportation and by a higher share
  of weather dependent production. Electricity demand forecasts at a low level of
  aggregation will be key inputs for such systems. We focus on forecasting demand
  at the individual household level, which is more challenging than forecasting aggregate
  demand, due to the lower signal-to-noise ratio and to the heterogeneity of consumption
  patterns across households. We propose a new ensemble method for probabilistic forecasting
  which borrows strength across the households while accommodating their individual
  idiosyncrasies. In particular, we develop a set of models or “experts” which capture
  different demand dynamics, and we fit each of them to the data from each household.
  Then, we construct an aggregation of experts where the ensemble weights are estimated
  on the whole data set, the main innovation being that we let the weights vary with
  the covariates by adopting an additive model structure. In particular, the proposed
  aggregation method is an extension of regression stacking where the mixture weights
  are modelled using linear combinations of parametric, smooth or random effects.
  The methods for building and fitting additive stacking models are implemented by
  the gamFactory R package, available at https://github.com/mfasiolo/gamFactory.
tags:
- Electricity demand forecasting
- Ensemble methods
- generalised additive models
- probabilistic forecast
- regression stacking
links:
- name: URL
  url: 
    https://projecteuclid.org/journals/annals-of-applied-statistics/volume-15/issue-2/Additive-stacking-for-disaggregate-electricity-demand-forecasting/10.1214/20-AOAS1417.full
---
