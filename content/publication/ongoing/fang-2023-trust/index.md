---
title: Trust-Region Sequential Quadratic Programming for Stochastic Optimization with Random Models
date: '2023-02'
publishDate: '2023-02-28'
authors:
- Yuchen Fang
- Sen Na
- Michael W. Mahoney
- Mladen Kolar
publication_types:
- '4'
abstract: '
We design a trust-region sequential quadratic programming (TR-SQP) method to find both **first- and second-order** stationary points for optimization problems with a stochastic objective and deterministic equality constraints. 
We name our method TR-SQP for STochastic Optimization with Random Models (TR-SQP-STORM). In each iteration, the algorithm constructs random models that require estimates of the objective value, gradient, and Hessian to satisfy adaptive accuracy conditions with a fixed probability. 
We introduce a novel reliability parameter, based on which we define reliable and unreliable iterations and adjust accuracy conditions accordingly. The reliability parameter equips the random models with extra flexibility to reduce the sample size at each step. To find first-order stationary points, we compute **gradient-steps** by employing the **adaptive relaxation technique** proposed by [Fang et al., 2022](/publication/preprints/fang-2022-fully). To find second-order stationary points, we design **eigen-steps** to explore the negative curvature of the reduced Lagrangian Hessian, with additional **second-order correctional steps** performed when necessary. 
Under reasonable assumptions, we establish both first- and second-order global convergence guarantees: with probability one, the TR-SQP-STORM iteration sequence converges to the first-order stationary point, with a subsequence converging to the second-order stationary point. We apply our method to a subset of problems in CUTEst set and on constrained Logistic regression problems to demonstrate its promising empirical performance.'
featured: false
publication: '*A short note is accepted by 2022 NeurIPS Higher-Order Optimization in Machine Learning (HOO) workshop*'
tags: [math.OC, cs.NA, math.NA, stat.CO, stat.ML]
#url_code: 
#doi: 
#links:
#- name: 
#  url: 
---
