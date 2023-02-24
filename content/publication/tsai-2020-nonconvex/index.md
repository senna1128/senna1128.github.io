---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Nonconvex Framework for Structured Dynamic Covariance Recovery
subtitle: ''
summary: ''
authors:
- Katherine Tsai
- Mladen Kolar
- Oluwasanmi Koyejo
tags:
- stat.ML
- cs.LG
- stat.AP
- stat.ME
categories: []
date: '2022-01-01'
lastmod: 2022-01-04T15:21:38-06:00
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
publishDate: '2022-09-04T03:11:27.352909Z'
publication_types:
- '2'
abstract: 'We propose a flexible, yet interpretable model for high-dimensional data with time-varying second-order statistics, motivated and applied to functional neuroimaging data. Our approach implements the neuroscientific hypothesis of discrete cognitive processes by factorizing covariances into sparse spatial and smooth temporal components. Although this factorization results in parsimony and domain interpretability, the resulting estimation problem is nonconvex. We design a two-stage optimization scheme with a tailored spectral initialization, combined with iteratively refined alternating projected gradient descent. We prove a linear convergence rate up to a nontrivial statistical error for the proposed descent scheme and establish sample complexity guarantees for the estimator. Empirical results using simulated data and brain imaging data illustrate that our approach outperforms existing baselines.'
publication: '*Journal of Machine Learning Research*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2011.05601
- name: Code
  url: https://github.com/koyejo-lab/dynamicCov.git
- name: URL
  url: http://jmlr.org/papers/v23/21-0795.html
---
