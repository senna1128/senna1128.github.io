---
# Documentation: https://wowchemy.com/docs/managing-content/

title: L-SVRG and L-Katyusha with Adaptive Sampling
subtitle: ''
summary: ''
authors:
- Boxin Zhao
- Boxiang Lyu
- Mladen Kolar
tags:
- cs.LG
- math.OC
categories: []
date: '2022-01-01'
lastmod: 2022-02-01T11:50:32-06:00
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
publishDate: '2022-02-01T17:50:27.958239Z'
publication_types:
- '3'
abstract: Stochastic gradient-based optimization methods, such as L-SVRG and its accelerated
  variant L-Katyusha [12], are widely used to train machine learning models. Theoretical
  and empirical performance of L-SVRG and L-Katyusha can be improved by sampling the
  observations from a non-uniform distribution [17]. However, to design a desired
  sampling distribution, Qian et al.[17] rely on prior knowledge of smoothness constants
  that can be computationally intractable to obtain in practice when the dimension
  of the model parameter is high. We propose an adaptive sampling strategy for L-SVRG
  and L-Katyusha that learns the sampling distribution with little computational overhead,
  while allowing it to change with iterates, and at the same time does not require
  any prior knowledge on the problem parameters. We prove convergence guarantees for
  L-SVRG and L-Katyusha for convex objectives when the sampling distribution changes
  with iterates. These results show that even without prior information, the proposed
  adaptive sampling strategy matches, and in some cases even surpasses, the performance
  of the sampling scheme in Qian et al.[17]. Extensive simulations support our theory
  and the practical utility of the proposed sampling scheme on real data.
publication: '*Technical report*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2201.13387
---
