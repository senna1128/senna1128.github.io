---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Global Convergence of Online Optimization for Nonlinear Model Predictive Control
subtitle: ''
summary: ''
authors:
- Sen Na
tags: [math.DS,math.NA,cs.NA,cs.SY,eess.SY,recent]
categories: []
date: '2021-12-01'
lastmod: 2023-02-28T14:15:05-08:00
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
publishDate: '2023-02-28T22:15:05.710175Z'
publication_types:
- '2'
abstract: 'We study a real-time iteration (RTI) scheme for solving online optimization problem appeared in nonlinear optimal control. The proposed RTI scheme modifies the existing RTI-based model predictive control (MPC) algorithm, by selecting the stepsize of each Newton step at each sampling time using a differentiable exact augmented Lagrangian. The scheme can adaptively select the penalty parameters of augmented Lagrangian on the fly, which are shown to be stabilized after certain time periods. We prove under generic assumptions that, by involving stepsize selection instead of always using a full Newton step (like what most of the existing RTIs do), the scheme converges globally: for any initial point, the KKT residuals of the subproblems converge to zero. A key step is to show that augmented Lagrangian keeps decreasing as horizon moves forward. We demonstrate the global convergence behavior of the proposed RTI scheme in a numerical experiment.'
publication: '*Advances in Neural Information Processing Systems*'
links:
- name: URL
  url: https://proceedings.neurips.cc/paper/2021/hash/67d16d00201083a2b118dd5128dd6f59-Abstract.html
---
