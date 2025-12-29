---
title: Statistical Inference of Constrained Model Estimation via Derivative-Free Stochastic Sequential Quadratic Programming
date: '2025-09'
publishDate: '2025-09-01'
authors:
- Jianliang Ye
- Sen Na
publication_types:
- '4'
abstract: 'We propose a derivative-free stochastic sequential quadratic programming (DF-SSQP) method for solving nonlinear equality-constrained stochastic optimization problems using only zero-order information. Our algorithm estimates gradients and Hessians via randomized finite differences and introduces an online debiasing technique that aggregates past iterates to reduce bias without excessive memory cost. We establish global and local convergence, asymptotic normality of the averaged iterates, and a functional central limit theorem (FCLT) for the optimization path. Notably, we extend existing FCLT results to a double-averaging setting arising from the debiasing process, addressing technical challenges that do not appear in standard single-averaging schemes. Our method also relaxes restrictive step size conditions by allowing random stabilization, improving practical applicability. We discuss a sketching-based extension to reduce complexity, making DF-SSQP suitable for large-scale derivative-free inference and optimization tasks.
'
featured: false
publication: '*A short version has been accepted in NeurIPS 2025 COML Workshop*'
tags: [math.OC, cs.NA, math.NA, stat.CO, stat.ML]
#url_code: 
#doi: 
#links:
#- name: 
#  url: 
---
