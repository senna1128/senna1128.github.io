---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Superconvergence of Online Optimization for Model Predictive Control
subtitle: ''
summary: ''
authors:
- Sen Na
- Mihai Anitescu
tags: [math.DS,math.NA,cs.NA,cs.SY,eess.SY,recent]
categories: []
date: '2023-03-01'
lastmod: 2023-02-28T22:18:31-08:00
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
publishDate: '2023-03-01T06:18:31.261052Z'
publication_types:
- '2'
abstract: "We develop a one-Newton-step-per-horizon, online, lag-$L$, model predictive control (MPC) algorithm for solving discrete-time, equality-constrained, nonlinear dynamic programs. Based on recent sensitivity analysis results for the target problems class, we prove that the approach exhibits a behavior that we call superconvergence; that is, the tracking error with respect to the full-horizon solution is not only stable for successive horizon shifts, but also decreases with increasing shift order to a minimum value that decays exponentially in the length of the receding horizon. The key analytical step is the decomposition of the one-step error recursion of our algorithm into algorithmic error and perturbation error. We show that the perturbation error decays exponentially with the lag between two consecutive receding horizons, whereas the algorithmic error, determined by Newton's method, achieves quadratic convergence instead. Overall this approach induces our local exponential convergence result in terms of the receding horizon length for suitable values of $L$. Numerical experiments validate our theoretical findings."
publication: '*IEEE Transactions on Automatic Control*'
doi: 10.1109/tac.2022.3223323
links:
- name: arXiv
  url: https://arxiv.org/abs/2001.03707
---
