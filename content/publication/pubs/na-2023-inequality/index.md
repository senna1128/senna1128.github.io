---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Inequality Constrained Stochastic Nonlinear Optimization via Active-Set Sequential
  Quadratic Programming
subtitle: ''
summary: ''
authors:
- Sen Na
- Mihai Anitescu
- Mladen Kolar
tags: [math.OC, math.NA, cs.LG, cs.NA, stat.ML, recent]
categories: []
date: '2023-03-02'
lastmod: 2023-03-02T11:36:26-08:00
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
publishDate: '2023-03-02T19:36:25.791960Z'
publication_types:
- '2'
abstract: 'We study nonlinear optimization problems with a stochastic objective and deterministic equality and inequality constraints, which emerge in numerous applications including finance, manufacturing, power systems and, recently, deep neural networks. We propose an active-set stochastic sequential quadratic programming (StoSQP) algorithm that utilizes a differentiable exact augmented Lagrangian as the merit function. The algorithm adaptively selects the penalty parameters of the augmented Lagrangian and performs a stochastic line search to decide the stepsize. The global convergence is established: for any initialization, the KKT residuals converge to zero almost surely. Our algorithm and analysis further develop the prior work of [Na et al., (2022)](/publication/pubs/na-2022-adaptive). Specifically, we allow nonlinear inequality constraints without requiring the strict complementary condition; refine some of the designs in [Na et al., (2022)](/publication/pubs/na-2022-adaptive) such as the feasibility error condition and the monotonically increasing sample size; strengthen the global convergence guarantee; and improve the sample complexity on the objective Hessian. We demonstrate the performance of the designed algorithm on a subset of nonlinear problems collected in CUTEst test set and on constrained logistic regression problems.
'
publication: '*Mathematical Programming*'
doi: 10.1007/s10107-023-01935-7
links:
- name: arXiv
  url: https://arxiv.org/abs/2109.11502
---
