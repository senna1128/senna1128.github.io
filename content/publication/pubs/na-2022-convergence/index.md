---
# Documentation: https://wowchemy.com/docs/managing-content/

title: On the Convergence of Overlapping Schwarz Decomposition for Nonlinear Optimal
  Control
subtitle: ''
summary: ''
authors:
- Sen Na
- Sungho Shin
- Mihai Anitescu
- Victor M. Zavala
author_notes:
- "Equal contribution"
- "Equal contribution"

tags: [math.OC, math.DS, cs.LG, recent]
categories: []
date: '2022-11-01'
lastmod: 2023-02-28T22:29:02-08:00
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
publishDate: '2023-03-01T06:29:02.176835Z'
publication_types:
- '2'
abstract: "We study the convergence properties of an overlapping Schwarz decomposition algorithm for solving nonlinear optimal control problems (OCPs). The algorithm decomposes the time domain into a set of overlapping subdomains, and solves all subproblems defined over subdomains in parallel. The convergence is attained by updating primal-dual information at the boundaries of overlapping subdomains. We show that the algorithm exhibits local linear convergence, and that the convergence rate improves exponentially with the overlap size. We also establish global convergence results for a general quadratic programming, which enables the application of the Schwarz scheme inside second-order optimization algorithms (e.g., sequential quadratic programming). The theoretical foundation of our convergence analysis is a sensitivity result of nonlinear OCPs, which we call “exponential decay of sensitivity” (EDS). Intuitively, EDS states that the impact of perturbations at domain boundaries (i.e., initial and terminal time) on the solution decays exponentially as one moves into the domain. Here, we expand a previous analysis available in the literature by showing that EDS holds for both primal and dual solutions of nonlinear OCPs, under uniform second-order sufficient condition, controllability condition, and boundedness condition. We conduct experiments with a quadrotor motion planning problem and a partial differential equations (PDE) control problem to validate our theory, and show that the approach is significantly more efficient than alternating direction method of multipliers and as efficient as the centralized interior-point solver."
publication: '*IEEE Transactions on Automatic Control*'
doi: 10.1109/tac.2022.3194087
links:
- name: arXiv
  url: https://arxiv.org/abs/2005.06674
---
