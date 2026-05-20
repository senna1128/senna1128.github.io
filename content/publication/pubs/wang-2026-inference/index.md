---
title: "Inference of Online Newton Methods with Nesterov's Accelerated Sketching"
date: '2026-04-25'
publishDate: '2026-04-25'
authors:
- Haoxuan Wang
- Xinchen Du
- Sen Na
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: [stat.ML, cs.LG, math.OC, stat.CO, recent]
categories: []
featured: true
draft: false
projects: []

publication_types:
- '2'
abstract: >-
  Reliable decision-making with streaming data requires principled uncertainty quantification of online methods. While first-order methods enable efficient iterate updates, their inference procedures still require updating proper (covariance) matrices, incurring $O(d^2)$ time and memory complexity, and are sensitive to ill-conditioning and noise heterogeneity of the problem. This costly inference task offers an opportunity for more robust second-order methods, which are, however, bottlenecked by solving Newton systems with $O(d^3)$ complexity. In this paper, we address this gap by studying an online Newton method with Hessian averaging, where the Newton direction at each step is approximately computed using a **sketch-and-project solver with Nesterov's acceleration**, matching $O(d^2)$ complexity of first-order methods. For the proposed method, we quantify its uncertainty arising from both random data and randomized computation. Under standard smoothness and moment conditions, we establish global almost-sure convergence, prove **asymptotic normality** of the last iterate with a limiting covariance characterized by a **Lyapunov equation**, and develop a fully online covariance estimator with **non-asymptotic convergence guarantees**. We also connect the resulting uncertainty quantification to that of exact and sketched Newton methods without Nesterov's acceleration. Extensive experiments on regression models demonstrate the superiority of the proposed method for online inference.

publication: '*International Conference on Machine Learning*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2604.23436
---
