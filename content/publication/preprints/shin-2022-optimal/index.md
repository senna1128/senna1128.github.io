---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Near-Optimal Performance of Stochastic Predictive Control
subtitle: ''
summary: ''
authors:
- Sungho Shin
- Sen Na
- Mihai Anitescu
tags: [cs.SY, eess.SY]
categories: []
date: '2022-10-01'
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
publishDate: '2023-02-28T22:15:08.368479Z'
publication_types:
- '3'
abstract: 'We study the performance of stochastic predictive control (SPC) for linear systems with a quadratic performance index and additive and multiplicative uncertainties. Under a finite support assumption, the problem can be cast as a finite-dimensional quadratic program, but the problem becomes quickly intractable as the problem size grows exponentially in the horizon length. SPC aims to compute approximate solutions by solving a sequence of problems with truncated prediction horizons and committing the solution in a receding-horizon fashion. While this approach is widely used in practice, its performance relative to the optimal solution is not well understood. This article reports for the first time a rigorous performance guarantee of SPC: under the standard stabilizability and detectability conditions, the dynamic regret of SPC is exponentially small in the prediction horizon length. Therefore, SPC can achieve near-optimal performance -- the expected performance can be made arbitrarily close to the optimal solution -- at a substantially reduced computational expense.
'
publication: '*arXiv preprint arXiv:2210.08599*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2210.08599
---
