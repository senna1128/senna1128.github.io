---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Fully Stochastic Trust-Region Sequential Quadratic Programming for Equality-Constrained
  Optimization Problems
subtitle: ''
summary: ''
authors:
- Yuchen Fang
- Sen Na
- Michael W. Mahoney
- Mladen Kolar
tags: [math.OC, stat.CO, stat.ML,recent]
categories: []
date: '2024-01-29'
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
publishDate: '2023-02-28T22:15:08.487247Z'
publication_types:
- '2'
abstract: 'We propose a trust-region stochastic sequential quadratic programming algorithm (TR-StoSQP) to solve nonlinear optimization problems with stochastic objectives and deterministic equality constraints. We consider a fully stochastic setting, where at each step a single sample is generated to estimate the objective gradient. The algorithm adaptively selects the trust-region radius and, compared to the existing line-search StoSQP schemes, allows us to utilize indefinite Hessian matrices (i.e., Hessians without modification) in SQP subproblems. As a trust-region method for constrained optimization, our algorithm must address an infeasibility issue --- the linearized equality constraints and trust-region constraints may lead to infeasible SQP subproblems. In this regard, we propose an **adaptive relaxation technique** to compute the trial step, consisting of a normal step and a tangential step. To control the lengths of these two steps while ensuring a **scale-invariant property**, we adaptively decompose the trust-region radius into two segments, based on the proportions of the rescaled feasibility and optimality residuals to the rescaled full KKT residual. The normal step has a closed form, while the tangential step is obtained by solving a trust-region subproblem, to which a solution ensuring the Cauchy reduction is sufficient for our study. We establish a global almost sure convergence guarantee for TR-StoSQP, and illustrate its empirical performance on both a subset of problems in the CUTEst test set and constrained logistic regression problems using data from the LIBSVM collection.'
publication: '*To appear in SIAM Journal on Optimization*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2211.15943
---
