---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Asymptotic Convergence Rate and Statistical Inference for Stochastic Sequential
  Quadratic Programming
subtitle: ''
summary: ''
authors:
- Sen Na
- Michael W. Mahoney
tags: [math.OC, cs.LG, stat.ML]
categories: []
date: '2022-05-01'
lastmod: 2023-02-28T14:15:05-08:00
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
publishDate: '2023-02-28T22:15:05.539693Z'
publication_types:
- '3'
abstract: 'We apply a stochastic sequential quadratic programming (StoSQP) algorithm to solve constrained nonlinear optimization problems, where the objective is stochastic and the constraints are deterministic. We study a fully stochastic setup, where only a single sample is available in each iteration for estimating the gradient and Hessian of the objective. We allow StoSQP to select a random stepsize $\bar{\alpha}_t$ adaptively, such that $\beta_t≤\bar{\alpha}_t≤\beta_t+\chi_t$, where $\beta_t$, $\chi_t=o(\beta_t)$ are prespecified deterministic sequences. We also allow StoSQP to solve Newton system inexactly via randomized iterative solvers, e.g., with the sketch-and-project method; and we do not require the approximation error of inexact Newton direction to vanish. For this general StoSQP framework, we establish the asymptotic convergence rate for its last iterate, with the worst-case iteration complexity as a byproduct; and we perform statistical inference. In particular, with proper decaying $\beta_t,\chi_t$, we show that: (i) **the StoSQP scheme can take at most $O(1/\epsilon^4)$ iterations to achieve $\epsilon$-stationarity;** (ii) asymptotically and almost surely, $||(x_t−x^{\star},\lambda_t−\lambda^{\star})||$ $=O(\sqrt{\beta_t\log(1/\beta_t)})+O(\chi_t/\beta_t)$, where $(x_t,\lambda_t)$ is the primal-dual StoSQP iterate; (iii) **the sequence $1/\sqrt{\beta_t}\cdot (x_t−x^{\star},\lambda_t-\lambda^\star)$ converges to a mean zero Gaussian distribution with a nontrivial covariance matrix.** Moreover, we establish the **Berry-Esseen bound** for $(x_t,\lambda_t)$ to measure quantitatively the convergence of its distribution function. We also provide a practical estimator for the covariance matrix, from which the confidence intervals of $(x^\star,λ^\star)$ can be constructed using iterates {{< math >}}$\{(x_t,\lambda_t)\}_t${{< /math >}}. Our theorems are validated using nonlinear problems in CUTEst test set.
'
publication: '*arXiv preprint arXiv:2205.13687*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2205.13687
---
