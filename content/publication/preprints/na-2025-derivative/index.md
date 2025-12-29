---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Derivative-Free Sequential Quadratic Programming for Equality-Constrained Stochastic Optimization
subtitle: ''
summary: ''
authors:
- Sen Na
tags: [math.OC, math.NA, math.ST, stat.CO, stat.ML]
categories: []
date: '2025-10-25'
lastmod: 2023-02-28T14:15:08-08:00
featured: false
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
publishDate: '2024-06-11T22:15:08.368479Z'
publication_types:
- '3'
abstract: 'We consider solving nonlinear optimization problems with a stochastic objective and deterministic equality constraints, assuming that only zero-order information is available for both the objective and constraints, and that the objective is also subject to random sampling noise. Under this setting, we propose a **Derivative-Free Stochastic Sequential Quadratic Programming** (DF-SSQP) method. Due to the lack of derivative information, we adopt a simultaneous perturbation stochastic approximation (SPSA) technique to randomly estimate the gradients and Hessians of both the objective and constraints. This approach requires only a dimension-independent number of zero-order evaluations -- as few as eight -- at each iteration step. A key distinction between our derivative-free and existing derivative-based SSQP methods lies in the intricate random bias introduced into the gradient and Hessian estimates of the objective and constraints, brought by stochastic zero-order approximations. To address this issue, we introduce an **online debiasing** technique based on **momentum-style estimators** that properly aggregate past gradient and Hessian estimates to reduce stochastic noise, while avoiding excessive memory costs via a moving averaging scheme. Under standard assumptions, we establish the global almost-sure convergence of the proposed DF-SSQP method. Notably, we further complement the global analysis with local convergence guarantees by demonstrating that the rescaled iterates exhibit asymptotic normality, with a limiting covariance matrix resembling the minimax optimal covariance achieved by derivative-based methods, albeit larger due to the absence of derivative information. Our local analysis enables online statistical inference of model parameters leveraging DF-SSQP. Numerical experiments on benchmark nonlinear problems demonstrate both the global and local behavior of DF-SSQP.
'
publication: '*arXiv preprint arXiv:2510.22458*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2510.22458
---
