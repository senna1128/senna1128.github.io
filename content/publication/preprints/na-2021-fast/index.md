---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Fast Temporal Decomposition Procedure for Long-horizon Nonlinear Dynamic
  Programming
subtitle: ''
summary: ''
authors:
- Sen Na
- Mihai Anitescu
- Mladen Kolar
tags: [math.OC, math.DS]
categories: []
date: '2021-07-01'
lastmod: 2023-02-28T14:15:07-08:00
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
publishDate: '2023-02-28T22:15:07.753261Z'
publication_types:
- '3'
abstract: 'We propose a fast temporal decomposition procedure for solving long-horizon nonlinear dynamic programs. The core of the procedure is sequential quadratic programming (SQP), with a differentiable exact augmented Lagrangian being the merit function. Within each SQP iteration, we solve the Newton system approximately using an overlapping temporal decomposition. We show that the approximated search direction is still a descent direction of the augmented Lagrangian, provided the overlap size and penalty parameters are suitably chosen, which allows us to establish global convergence. Moreover, we show that a unit stepsize is accepted locally for the approximated search direction, and further establish a uniform, local linear convergence over stages. Our local convergence rate matches the rate of the recent Schwarz scheme [(Na et al., 2022)](/publication/pubs/na-2022-convergence). However, the Schwarz scheme has to solve nonlinear subproblems to optimality in each iteration, while we only perform one Newton step instead. Numerical experiments validate our theories and demonstrate the superiority of our method.'
publication: '*arXiv preprint arXiv:2107.11560*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2107.11560
---
