---
title: Online Covariance Matrix Estimation in Sketched Newton Methods
date: '2025-02'
publishDate: '2025-02-01'
authors:
- Wei Kuang
- Mihai Anitescu
- Sen Na
tags: [stat.ML, cs.LG, math.NA, math.OC, stat.CO]
categories: []
featured: false
draft: false
projects: []

publication_types:
- '3'
abstract: '
Given the ubiquity of streaming data, online algorithms have been widely used for parameter 
estimation, with second-order methods particularly standing out for their efficiency and robustness. 
In this paper, we study an **online sketched Newton method** that leverages a randomized sketching technique 
to perform an approximate Newton step in each iteration, thereby eliminating the computational bottleneck 
of second-order methods. While existing studies have established the asymptotic normality of sketched 
Newton methods, a consistent estimator of the limiting covariance matrix remains an open problem. 
We propose a **fully online covariance matrix estimator** that is constructed entirely from the Newton 
iterates and requires no matrix factorization. Compared to covariance estimators for first-order 
online methods, our estimator for second-order methods is batch-free. We establish the consistency 
and convergence rate of our estimator, and coupled with asymptotic normality results, we can then 
perform online statistical inference for the model parameters based on sketched Newton methods. We also 
discuss the extension of our estimator to constrained problems, and demonstrate its superior performance 
on regression problems as well as benchmark problems in the CUTEst set.
'
publication: '*arXiv preprint arXiv:2502.07114*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2502.07114
---
