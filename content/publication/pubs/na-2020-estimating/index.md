---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Estimating Differential Latent Variable Graphical Models with Applications to Brain Connectivity
subtitle: ''
summary: ''
authors:
- Sen Na
- Mladen Kolar
- Oluwasanmi Koyejo
tags: [math.ST, stat.AP, stat.ME, stat.ML, stat.TH, recent]
categories: []
date: '2020-09-01'
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
publishDate: '2023-02-28T22:15:06.475576Z'
publication_types:
- '2'
abstract: 'Differential graphical models are designed to represent the difference between the conditional dependence structures of two groups, and thus are of particular interest for scientific investigations. Motivated by modern applications, this manuscript considers an extended setting where each group is generated by a latent variable Gaussian graphical model. Due to the existence of latent factors, the differential network is decomposed into sparse and low-rank components, both of which are symmetric indefinite matrices. We estimate these two components simultaneously using a two-stage procedure: (i) an initialization stage, which computes a simple, consistent estimator, and (ii) a convergence stage, implemented using a projected alternating gradient descent algorithm applied to a nonconvex objective, initialized using the output of the first stage. We prove that given the initialization, the estimator converges linearly with a nontrivial, minimax optimal statistical error. Experiments on synthetic and real data illustrate that the proposed nonconvex procedure outperforms existing methods.'
publication: '*Biometrika*'
doi: 10.1093/biomet/asaa066
links:
- name: arXiv
  url: https://arxiv.org/abs/1909.05892
---