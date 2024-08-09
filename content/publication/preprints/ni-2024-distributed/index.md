---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Distributed Sequential Quadratic Programming with Overlapping Graph Decomposition and Exact Augmented Lagrangian
subtitle: ''
summary: ''
authors:
- Runxin Ni
- Sen Na
- Sungho Shin
- Mihai Anitescu
tags: [math.OC]
categories: []
date: '2024-6-11'
lastmod: 2023-02-28T14:15:08-08:00
featured: false
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
publishDate: '2024-06-11T22:15:08.368479Z'
publication_types:
- '3'
abstract: 'In this paper, we address the challenge of solving **large-scale graph-structured nonlinear programs (gsNLPs)** in a scalable manner. GsNLPs are problems in which the objective and constraint functions are associated with nodes on a graph and depend on the variables of adjacent nodes. This graph-structured formulation encompasses various specific instances, such as dynamic optimization, PDE-constrained optimization, multistage stochastic optimization, and general network optimization. By leveraging the sequential quadratic programming (SQP) framework, we propose a globally convergent overlapping graph decomposition method to solve large-scale gsNLPs under standard mild regularity conditions on the graph topology. In each iteration, we perform an overlapping graph decomposition to compute an approximate Newton direction in a parallel environment. Then, we select a suitable stepsize and update the primal-dual iterate by performing a backtracking line search on an exact augmented Lagrangian merit function. Built on the **exponential decay of sensitivity** of gsNLPs, we show that the approximate Newton direction is a descent direction of the augmented Lagrangian, which leads to global convergence with local linear convergence rate. In particular, global convergence is achieved for sufficiently large overlaps, and the local linear convergence rate improves exponentially in terms of the overlap size. Our results match existing state-of-the-art guarantees established for dynamic programs (which simply correspond to linear graphs). We validate the theory on a semilinear elliptic PDE-constrained problem.
'
publication: '*arXiv preprint arXiv:2402.17170*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2402.17170
---
