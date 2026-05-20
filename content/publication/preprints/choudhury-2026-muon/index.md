---
title: "Muon with Nesterov Momentum: Heavy-Tailed Noise and (Randomized) Inexact Polar Decomposition"
date: '2026-05-07'
publishDate: '2026-05-07'
authors:
- Sayantan Choudhury
- Xiaoran Cheng
- Martin Takáč
- Sen Na
- Mladen Kolar
tags: [math.OC, cs.LG]
categories: []
featured: true
draft: false
projects: []

publication_types:
- '3'
abstract: >-
  Most first-order optimizers treat matrix-valued parameters as vectors, ignoring the intrinsic geometry of hidden-layer weights in neural networks. Muon addresses this mismatch by updating along the polar factor of a momentum matrix, but its theoretical understanding has lagged behind practice. In particular, practical implementations incorporate Nesterov momentum, compute the polar factor only approximately, and operate with stochastic gradients that may be heavy-tailed. We close this gap by developing a convergence theory for Muon with Nesterov momentum and **inexact polar decomposition** in **non-convex matrix optimization** under **heavy-tailed noise**. Our analysis builds on a unified framework for inexact polar decomposition that captures practical iterative approximations such as Newton-Schulz and quantifies how their errors propagate through the optimization dynamics. Under this framework, we establish an optimal iteration and sample complexity of $O \left(\varepsilon^{\frac{-(3\alpha-2)}{(\alpha-1)}} \right)$ for finding an $\varepsilon$-stationary point, where $\alpha\in(1,2]$ denotes the heavy-tail index. For the inexact-polar setting with $\sigma_1=0$, we also provide guarantees that do not require prior knowledge of $\alpha$. We analyze a **randomized low-rank polar decomposition** that is substantially more efficient than full-space methods while remaining compatible with our theory. Numerical experiments further demonstrate the effectiveness of the proposed inexact and randomized variants.
publication: '*arXiv preprint arXiv:2605.06884*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2605.06884
---
