---
title: Online Statistical Inference of Constrained Stochastic Optimization via Random Scaling
date: '2025-05'
publishDate: '2025-05-01'
authors:
- Xinchen Du
- Wanrong Zhu
- Wei Biao Wu
- Sen Na
tags: [stat.ML, cs.LG, math.NA, math.OC, math.ST, stat.CO]
categories: []
featured: false
draft: false
projects: []

publication_types:
- '3'
abstract: '
Constrained stochastic nonlinear optimization problems have attracted significant attention for their 
ability to model complex real-world scenarios in physics, economics, and biology. As datasets continue 
to grow, **online inference** methods have become crucial for enabling real-time decision-making without 
the need to store historical data. In this work, we develop an online inference procedure for constrained 
stochastic optimization by leveraging a method called Sketched Stochastic Sequential Quadratic 
Programming (SSQP). As a direct generalization of sketched Newton methods, SSQP approximates the objective 
with a quadratic model and the constraints with a linear model at each step, then applies a sketching 
solver to inexactly solve the resulting subproblem. Building on this design, we propose a new online 
inference procedure called **random scaling**. In particular, we construct a test statistic based on SSQP 
iterates whose limiting distribution is free of any unknown parameters. Compared to existing online 
inference procedures, our approach offers two key advantages: (i) it enables the construction of 
**asymptotically valid confidence intervals**; and (ii) it is **matrix-free**, i.e. the computation involves 
only primal-dual SSQP iterates $(x_t,\lambda_t)$ without requiring any matrix inversions. We validate 
our theory through numerical experiments on nonlinearly constrained regression problems and demonstrate 
the superior performance of our random scaling method over existing inference procedures.
'
publication: '*arXiv preprint arXiv:2505.18327*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2505.18327
---
