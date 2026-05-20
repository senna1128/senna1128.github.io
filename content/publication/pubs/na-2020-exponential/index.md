---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Exponential Decay in the Sensitivity Analysis of Nonlinear Dynamic Programming
subtitle: ''
summary: ''
authors:
- Sen Na
- Mihai Anitescu
tags: [math.NA,math.OC,eess.SY,recent]
categories: []
date: '2020-01-01'
lastmod: 2023-02-28T14:15:06-08:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-02-28T22:15:06.615033Z'
publication_types:
- '2'
abstract: 'In this paper, we study the sensitivity of discrete-time dynamic programs with nonlinear dynamics and objective to perturbations in the initial conditions and reference parameters. Under uniform controllability and boundedness assumptions for the problem data, we prove that the directional derivative of the optimal state and control at time $k$, $x_k^\star$ and $u_k^\star$, with respect to the reference signal at time $i$, $d_i$, will have exponential decay in terms of $|k-i|$ with a decay rate $\rho$ independent of the temporal horizon length. The key technical step is to prove that a version of the convexification approach proposed by [Verschueren et al., 2017](https://doi.org/10.1137/16m1081543) can be applied to the KKT conditions and results in a convex quadratic program with uniformly bounded data. In turn, Riccati techniques can be further employed to obtain the sensitivity result, borne from the observation that the directional derivatives are solutions of quadratic programs with structure similar to the KKT conditions themselves. We validate our findings with numerical experiments on a small nonlinear, nonconvex, dynamic program.
 '
publication: '*SIAM Journal on Optimization*'
doi: 10.1137/19m1265065
links:
- name: arXiv
  url: https://arxiv.org/abs/1912.06734
---
