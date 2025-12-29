---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Statistical Inference of Constrained Stochastic Optimization via Sketched Sequential Quadratic Programming
subtitle: ''
summary: ''
authors:
- Sen Na
- Michael W. Mahoney
tags: [math.OC, cs.LG, stat.ML, recent]
categories: []
date: '2025-02-01'
lastmod: 2025-02-28T14:15:05-08:00
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
publishDate: '2025-02-28T22:15:05.539693Z'
publication_types:
- '2'
abstract: 'We consider **online statistical inference** of constrained stochastic nonlinear optimization problems. 
We apply the **Stochastic Sequential Quadratic Programming** (StoSQP) method to solve these problems, which 
can be regarded as applying second-order Newton’s method to the Karush-Kuhn-Tucker (KKT) conditions. In 
each iteration, the StoSQP method computes the Newton direction by solving a quadratic program, and then 
selects a proper **adaptive stepsize** $\bar{\alpha}_t$ to update the primal-dual iterate. To reduce 
dominant computational cost of the method, we inexactly solve the quadratic program in each iteration 
by employing an **iterative sketching solver**. Notably, the approximation error of the sketching solver 
need not vanish as iterations proceed, meaning that the per-iteration computational cost does not blow up. 
For the above StoSQP method, we show that under mild assumptions, the rescaled primal-dual sequence
$1/\sqrt{\bar{\alpha}_t}\cdot (x_t−x^{\star},\lambda_t-\lambda^\star)$ converges to a mean-zero Gaussian 
distribution with a nontrivial covariance matrix depending on the underlying sketching distribution. 
To perform inference in practice, we also analyze a plug-in covariance matrix estimator. We illustrate 
the asymptotic normality result of the method both on benchmark nonlinear problems in CUTEst test set and
on linearly/nonlinearly constrained regression problems.
'
publication: '*Journal of Machine Learning Research*'
links:
- name: URL
  url: https://www.jmlr.org/papers/volume26/24-0530/24-0530.pdf
- name: arXiv
  url: https://arxiv.org/abs/2205.13687
---
