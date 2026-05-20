---
title: A Trust-Region Interior-Point Stochastic Sequential Quadratic Programming Method
date: '2026-03-10'
publishDate: '2026-03-10'
authors:
- Yuchen Fang
- Jihun Kim
- Sen Na
- James Demmel
- Javad Lavaei
tags: [math.OC, cs.LG, math.NA, stat.ML]
categories: []
featured: false
draft: false
projects: []

publication_types:
- '3'
abstract: >-
  In this paper, we propose a **trust-region interior-point stochastic sequential quadratic programming** (TR-IP-SSQP) method for solving optimization problems with a stochastic objective and deterministic nonlinear equality and inequality constraints. In this setting, exact evaluations of the objective function and its gradient are unavailable, but their stochastic estimates can be constructed. In particular, at each iteration our method builds stochastic oracles, which estimate the objective value and gradient to satisfy proper adaptive accuracy conditions with a fixed probability. To handle inequality constraints, we adopt an interior-point method (IPM), in which the barrier parameter follows a prescribed decaying sequence. Under standard assumptions, we establish **global almost-sure convergence** of the proposed method to first-order stationary points. We implement the method on a subset of problems from the CUTEst test set, as well as on logistic regression problems, to demonstrate its practical performance.
publication: '*arXiv preprint arXiv:2603.10230*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2603.10230
---
