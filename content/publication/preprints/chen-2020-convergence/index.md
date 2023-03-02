---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Convergence Analysis of Accelerated Stochastic Gradient Descent under the Growth
  Condition
subtitle: ''
summary: ''
authors:
- You-Lin Chen
- Sen Na
- Mladen Kolar
tags: [math.OC]
categories: []
date: '2020-06-01'
#lastmod:
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
publishDate: '2023-02-28T22:15:07.525235Z'
publication_types:
- '3'
abstract: "
We study the convergence of accelerated stochastic gradient descent for strongly convex objectives under the growth condition, which states that the variance of stochastic gradient is bounded by a multiplicative part that grows with the full gradient, and a constant additive part. Through the lens of the growth condition, we investigate four widely used accelerated methods: Nesterov’s accelerated method (NAM), robust momentum method (RMM), accelerated dual averaging method (ADAM), and implicit ADAM (iADAM). While these methods are known to improve the convergence rate of SGD under the condition that the stochastic gradient has bounded variance, it is not well understood how their convergence rates are affected by the multiplicative noise. In this paper, we show that these methods all converge to a neighborhood of the optimum with accelerated convergence rates (compared to SGD) even under the growth condition. In particular, NAM, RMM, iADAM enjoy acceleration only with a mild multiplicative noise, while ADAM enjoys acceleration even with a large multiplicative noise. Furthermore, we propose a generic tail-averaged scheme that allows the accelerated rates of ADAM and iADAM to nearly attain the theoretical lower bound (up to a logarithmic factor in the variance term).
"

publication: '*arXiv preprint arXiv:2006.06782*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2006.06782
---
