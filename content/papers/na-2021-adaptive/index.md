---
title: An adaptive stochastic sequential quadratic programming with differentiable
  exact augmented lagrangians
date: '2022-06-01'
publishDate: '2022-09-04T02:24:42.813663Z'
authors:
- Sen Na
- Mihai Anitescu
- Mladen Kolar
publication_types:
- '2'
abstract: 'We consider solving nonlinear optimization problems with a stochastic objective and deterministic equality constraints. We assume for the objective that its evaluation, gradient, and Hessian are inaccessible, while one can compute their stochastic estimates by, for example, subsampling. We propose a stochastic algorithm based on sequential quadratic programming (SQP) that uses a differentiable exact augmented Lagrangian as the merit function. To motivate our algorithm design, we first revisit and simplify an old SQP method Lucidi (J. Optim. Theory Appl. 67(2): 227–245, 1990) developed for solving deterministic problems, which serves as the skeleton of our stochastic algorithm. Based on the simplified deterministic algorithm, we then propose a non-adaptive SQP for dealing with stochastic objective, where the gradient and Hessian are replaced by stochastic estimates but the stepsizes are deterministic and prespecified. Finally, we incorporate a recent stochastic line search procedure Paquette and Scheinberg (SIAM J. Optim. 30(1): 349–376 2020) into the non-adaptive stochastic SQP to adaptively select the random stepsizes, which leads to an adaptive stochastic SQP. The global "almost sure" convergence for both non-adaptive and adaptive SQP methods is established. Numerical experiments on nonlinear problems in CUTEst test set demonstrate the superiority of the adaptive algorithm.'
featured: true
publication: '*Mathematical Programming*'
tags: [math.OC, cs.NA, math.NA, stat.CO, stat.ML]
url_code: https://github.com/senna1128/Constrained-Stochastic-Optimization
doi: 10.1007/s10107-022-01846-z
links:
- name: arXiv
  url: https://arxiv.org/abs/2102.05320
---
