---
title: Constrained Optimization via Exact Augmented Lagrangian and Randomized Iterative Sketching
date: '2023-05'
publishDate: '2023-05-31'
authors:
- Ilgee Hong
- Sen Na
- Michael W. Mahoney
- Mladen Kolar
author_notes:
- "Equal contribution"
- "Equal contribution"
publication_types:
- '2'
abstract: 'We consider solving equality-constrained nonlinear, nonconvex optimization problems. This class of problems appears widely in a variety of applications in machine learning and engineering, ranging from constrained deep neural networks, to optimal control, to PDE-constrained optimization. We develop an adaptive inexact Newton method for this problem class. In each iteration, we solve the Lagrangian Newton system inexactly via a **randomized iterative sketching** solver, and select a suitable stepsize by performing line search on an **exact augmented Lagrangian** merit function. The randomized solvers have advantages over deterministic linear system solvers by significantly reducing per-iteration flops complexity and storage cost, when equipped with suitable sketching matrices. Our method adaptively controls the accuracy of the randomized solver and the penalty parameters of the exact augmented Lagrangian, to ensure that the inexact Newton direction is a descent direction of the exact augmented Lagrangian. This allows us to establish a **global almost sure convergence**. We also show that a unit stepsize is admissible locally, so that our method exhibits a **local linear convergence**. Furthermore, we prove that the linear convergence can be strengthened to **superlinear convergence** if we gradually sharpen the adaptive accuracy condition on the randomized solver. We demonstrate the superior performance of our method on benchmark nonlinear problems in CUTEst test set, constrained logistic regression with data from LIBSVM, and a PDE-constrained problem.'

featured: false
publication: '*International Conference on Machine Learning*'
tags: [math.OC, cs.LG, cs.NA, math.NA, stat.ML]
#url_code: 
#doi: 
links:
- name: arXiv
  url: https://arxiv.org/abs/2305.18379
---
