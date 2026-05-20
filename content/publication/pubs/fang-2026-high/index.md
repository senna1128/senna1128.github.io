---
title: High Probability Complexity Bounds of Trust-Region Stochastic Sequential Quadratic Programming with Heavy-Tailed Noise
date: '2026-03-01'
publishDate: '2025-03-01'
authors:
- Yuchen Fang
- Javad Lavaei
- Sen Na
tags: [math.OC, cs.CC, cs.LG, math.NA, stat.ML,recent]
categories: []
featured: true
draft: false
projects: []

publication_types:
- '2'
abstract: '
In this paper, we consider nonlinear optimization problems with a stochastic objective and deterministic equality constraints. We propose a **Trust-Region Stochastic Sequential Quadratic Programming** (TR-SSQP) method and establish its high-probability iteration complexity bounds for identifying first- and second-order $\epsilon$-stationary points. In our algorithm, we assume that exact objective values, gradients, and Hessians are not directly accessible but can be estimated via zeroth-, first-, and secondorder probabilistic oracles. Compared to existing complexity studies of SSQP methods that rely on a zeroth-order oracle with 
sub-exponential tail noise (i.e., light-tailed) and focus mostly on first-order stationarity, our analysis accommodates **biased** (also referred to as irreducible in the literature) and **heavy-tailed noise** in the zeroth-order oracle and significantly extends the analysis to **second-order stationarity**. We show that under heavy-tailed noise conditions, our SSQP method achieves the same high-probability first-order iteration complexity bounds as in the light-tailed noise setting, while further exhibiting promising second-order iteration complexity bounds. Specifically, the method identifies a first-order $\epsilon$-stationary point in $O(\epsilon^{-2})$ iterations and a second-order $\epsilon$-stationary point in $O(\epsilon^{-3})$ iterations with high probability, provided that $\epsilon$ is lower bounded by a constant determined by the bias magnitude (i.e., the irreducible noise) in estimation. We validate our theoretical findings and evaluate the practical performance of our method on CUTEst benchmark test set.
'
publication: '*Mathematical Programming*'
doi: 10.1007/s10107-026-02357-x
links:
- name: arXiv
  url: https://arxiv.org/abs/2503.19091
---
