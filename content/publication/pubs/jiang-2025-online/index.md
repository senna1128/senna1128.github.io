---
title: Online Covariance Estimation in Nonsmooth Stochastic Approximation
date: '2025-03-01'
publishDate: '2023-02-28'
authors:
- Liwei Jiang
- Abhishek Roy 
- Krishna Balasubramanian
- Damek Davis
- Dmitriy Drusvyatskiy
- Sen Na
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: [stat.ML, cs.LG, math.OC, recent]
categories: []
date: '2025-03-02'
lastmod: 2023-03-02T11:36:26-08:00
featured: false
draft: false

projects: []
publishDate: '2023-03-02T19:36:25.791960Z'
publication_types:
- '2'
abstract: '
We consider applying stochastic approximation (SA) methods to solve **nonsmooth variational inclusion problems**. 
Existing studies have shown that the averaged iterates of SA methods exhibit asymptotic normality, with 
an optimal limiting covariance matrix in the local minimax sense of Hájek and Le Cam. However, no methods 
have been proposed to estimate this covariance matrix in a nonsmooth and potentially non-monotone 
(nonconvex) setting. In this paper, we study an online **batch-means covariance matrix estimator** introduced 
in [Zhu et al.(2023)](https://www.tandfonline.com/doi/full/10.1080/01621459.2021.1933498). The estimator groups the SA iterates 
appropriately and computes the sample covariance among batches as an estimate of the limiting covariance. 
Its construction does not require prior knowledge of the total sample size, and updates can be performed 
recursively as new data arrives. We establish that, as long as the batch size sequence is properly 
specified (depending on the stepsize sequence), the estimator achieves a convergence rate of order 
$O(\sqrt{d}n^{−1/8+\epsilon})$ for any $\epsilon>0$, where $d$ and $n$ denote the problem dimensionality 
and the number of iterations (or samples) used. Although the problem is nonsmooth and potentially 
non-monotone (nonconvex), our convergence rate **matches the best-known rate** for covariance estimation 
methods using only first-order information in smooth and strongly-convex settings. The consistency of 
this covariance estimator enables asymptotically valid statistical inference, including constructing 
confidence intervals and performing hypothesis testing.
'
publication: '*Conference on Learning Theory*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2502.05305
---
