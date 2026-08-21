---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multiple-Shooting Interior-Point Differential Dynamic Programming for Constrained Nonlinear Optimal Control
subtitle: ''
summary: ''
authors:
- Tomohiro Sasaki
- Lu Gan
- Sen Na
tags: [math.OC, cs.RO, eess.SY, recent]
categories: []
date: '2026-07-31'
lastmod: 2026-08-21T00:00:00-07:00
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
publishDate: '2026-07-31T00:00:00Z'
publication_types:
- '2'
abstract: 'We propose Multiple-Shooting Interior-Point Differential Dynamic Programming (MS-IPDDP) for finite-horizon constrained nonlinear optimal control with smooth path inequalities and terminal equality constraints. The method lifts intermediate states into the decision variables, enforces the dynamics through defect constraints, and combines this multiple-shooting transcription with a primal-dual interior-point DDP recursion. As a result, the solver can start from dynamically inconsistent state-control guesses and reduce the resulting defects during the solve, rather than requiring a feasible rollout at every iteration. For a fixed barrier parameter and with an exact second-order local model, we show that the unregularized lifted backward pass coincides with the condensed Newton step of the perturbed KKT system for the lifted barrier subproblem. This equivalence identifies the precise Newton content of the method and clarifies how defect lifting changes the admissible iterates while preserving the stagewise structure of the solve. We also present an uncertainty-aware extension based on linearized covariance propagation and first-order Gaussian tightening of selected path constraints. Extensive numerical studies demonstrate the computational efficiency of the proposed MS-IPDDP, its robustness to deterministic initialization, the empirical calibration of the tightened surrogate in the stochastic setting, and viability for repeated solves in nonlinear MPC. The implementation of the proposed method will be made publicly available upon acceptance.'
publication: '*IEEE Conference on Decision and Control (CDC)*'
---
