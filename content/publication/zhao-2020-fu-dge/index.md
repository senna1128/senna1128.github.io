---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'FuDGE: A Method to Estimate a Functional Differential Graph in a High-Dimensional
  Setting'
subtitle: ''
summary: ''
authors:
- Boxin Zhao
- sam-wang
- Mladen Kolar
tags:
- stat.ML
- cs.LG
categories: []
date: '2022-01-01'
lastmod: 2022-01-04T15:48:17-06:00
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
publishDate: '2022-09-04T03:26:16.777554Z'
publication_types:
- '2'
abstract: 'We consider the problem of estimating the difference between two undirected functional graphical models with shared structures. In many applications, data are naturally regarded as a vector of random functions rather than as a vector of scalars. For example, electroencephalography (EEG) data are treated more appropriately as functions of time. In such a problem, not only can the number of functions measured per sample be large, but each function is itself an infinite dimensional object, making estimation of model parameters challenging. This is further complicated by the fact that curves are usually observed only at discrete time points. We first define a functional differential graph that captures the differences between two functional graphical models and formally characterize when the functional differential graph is well defined. We then propose a method, FuDGE, that directly estimates the functional differential graph without first estimating each individual graph. This is particularly beneficial in settings where the individual graphs are dense but the differential graph is sparse. We show that FuDGE consistently estimates the functional differential graph even in a high-dimensional setting for both fully observed and discretely observed function paths. We illustrate the finite sample properties of our method through simulation studies. We also propose a competing method, the Joint Functional Graphical Lasso, which generalizes the Joint Graphical Lasso to the functional setting. Finally, we apply our method to EEG data to uncover differences in functional brain connectivity between a group of individuals with alcohol use disorder and a control group.'

publication: '*Journal of Machine Learning Research*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2003.05402v1
- name: Code
  url: https://github.com/boxinz17/FuDGE  
- name: URL
  url: http://jmlr.org/papers/v23/20-231.html
---
