---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Statistical Inference of Constrained Stochastic Optimization via Sketched Sequential Quadratic Programming
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
abstract: '
We consider statistical inference of equality-constrained stochastic nonlinear optimization problems. We develop a fully online stochastic sequential quadratic programming (StoSQP) method to solve the problems, which can be regarded as applying Newton’s method to the first-order optimality conditions (i.e., the KKT conditions). Motivated by recent designs of numerical second-order methods, we allow StoSQP to adaptively select any random stepsize $\bar{\alpha}_t$, as long as $\beta_t≤\bar{\alpha}_t≤\beta_t+\chi_t$, for some
control sequences $\beta_t$ and $\chi_t=o(\beta_t)$. To reduce the dominant computational cost of second-order methods, we additionally allow StoSQP to inexactly solve quadratic programs via efficient randomized iterative solvers that utilize sketching techniques. Notably, we do not require the approximation error to diminish as iteration proceeds. For the developed method, we show that under mild assumptions (i) **computationally**, it can take at most **$O(1/\epsilon^4)$** iterations (same as samples) to attain $\epsilon$-stationarity; (ii) **statistically**, its primal-dual sequence $1/\sqrt{\beta_t}\cdot (x_t−x^{\star},\lambda_t-\lambda^\star)$ converges to a mean-zero Gaussian distribution with a nontrivial covariance matrix depending on the underlying sketching distribution. Additionally, we establish the **almost-sure convergence rate** of the iterate $(x_t,\lambda_t)$ along with the **Berry-Esseen bound**; the latter quantitatively measures the convergence rate of the distribution function. We analyze a **plug-in limiting covariance matrix estimator**, and demonstrate the performance of the method both on benchmark nonlinear problems in CUTEst test set and on linearly/nonlinearly constrained regression problems.
'
publication: '*arXiv preprint arXiv:2205.13687*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2205.13687
---
