---
title: Trust-Region Sequential Quadratic Programming for Stochastic Optimization with Random Models
date: '2024-09'
authors:
- Yuchen Fang
- Sen Na
- Michael W. Mahoney
- Mladen Kolar
tags: [math.OC, cs.LG, math.NA, stat.CO, stat.ML]
featured: false
draft: false
projects: []
publishDate: '2024-09-24'

publication_types:
- '3'
abstract: '
In this work, we consider solving optimization problems with a stochastic objective and deterministic 
equality constraints. We propose a Trust-Region Sequential Quadratic Programming method to find both 
**first- and second-order stationary points**. Our method utilizes a **random model** to represent the objective 
function, which is constructed from stochastic observations of the objective and is designed to satisfy 
proper adaptive accuracy conditions with a high but fixed probability. To converge to first-order 
stationary points, our method computes a **gradient step** in each iteration defined by minimizing a 
quadratic approximation of the objective subject to a (relaxed) linear approximation of the problem 
constraints and a trust-region constraint. To converge to second-order stationary points, our method 
additionally computes an **eigen step** to explore the negative curvature of the reduced Hessian matrix, 
as well as a **second-order correction step** to address the potential Maratos effect, which arises due to 
the nonlinearity of the problem constraints. Such an effect may impede the method from moving away from 
saddle points. Both gradient and eigen step computations leverage a novel parameter-free decomposition 
of the step and the trust-region radius, accounting for the proportions among the feasibility residual, 
optimality residual, and negative curvature. We establish global almost sure first- and second-order 
convergence guarantees for our method, and present computational results on CUTEst problems, regression 
problems, and saddle-point problems to demonstrate its superiority over existing line-search-based 
stochastic methods.
'
publication: '*arXiv preprint arXiv:2409.15734*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2409.15734

---
