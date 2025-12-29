---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Near-Optimal Performance of Stochastic Model Predictive Control
subtitle: ''
summary: ''
authors:
- Sungho Shin
- Sen Na
- Mihai Anitescu
tags: [cs.SY, eess.SY, recent]
categories: []
date: '2025-08-01'
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
- '2'
abstract: 'This article presents a **dynamic regret analysis** for stochastic model predictive control (SMPC) 
in linear systems with quadratic performance index and additive and multiplicative uncertainties. 
Under a finite support assumption, the problem can be cast as a finite-dimensional quadratic program, 
but the problem becomes quickly intractable as the problem size grows exponentially in the horizon length. 
SMPC aims to compute approximate solutions by solving a sequence of problems with truncated prediction 
horizons and committing the solution in a receding-horizon fashion. While this approach is widely used 
in practice, its performance relative to the optimal solution is not well understood. This article 
reports for the first time a rigorous **near-optimal performance** guarantee of SMPC: Under **stabilizability** 
and **detectability** conditions, the dynamic regret of SMPC is **exponentially small** in the prediction horizon 
length, allowing SMPC to achieve near-optimal performance at a substantially reduced computational expense.
'
publication: '*To appear in Mathematics of Operations Research*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2210.08599
---
