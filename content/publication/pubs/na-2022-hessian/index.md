---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hessian Averaging in Stochastic Newton Methods Achieves Superlinear Convergence
subtitle: ''
summary: ''
authors:
- Sen Na
- Michał Dereziński
- Michael W. Mahoney
tags: [math.OC, cs.LG, stat.ML, recent]
categories: []
date: '2022-12-01'
lastmod: 2023-02-28T14:15:07-08:00
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
publishDate: '2023-02-28T22:15:07.889433Z'
publication_types:
- '2'
abstract: '
We consider minimizing a smooth and strongly convex objective function using a stochastic Newton method. At each iteration, the algorithm is given an oracle access to a stochastic estimate of the Hessian matrix. The oracle model includes popular algorithms such as Subsampled Newton and Newton Sketch. Despite using second-order information, these existing methods do not exhibit superlinear convergence, unless the stochastic noise is gradually reduced to zero during the iteration, which would lead to a computational blow-up in the per-iteration cost. We propose to address this limitation with Hessian averaging: instead of using the most recent Hessian estimate, our algorithm maintains an average of all the past estimates. This reduces the stochastic noise while avoiding the computational blow-up. We show that this scheme exhibits local $Q$-superlinear convergence with a non-asymptotic rate of $(\Upsilon\sqrt{\log t/t})^t$, where $\Upsilon$ is proportional to the level of stochastic noise in the Hessian oracle. A potential drawback of this (uniform averaging) approach is that the averaged estimates contain Hessian information from the global phase of the method, i.e., before the iterates converge to a local neighborhood. This leads to a distortion that may substantially delay the superlinear convergence until long after the local neighborhood is reached. To address this drawback, we study a number of weighted averaging schemes that assign larger weights to recent Hessians, so that the superlinear convergence arises sooner, albeit with a slightly slower rate. Remarkably, we show that there exists a universal weighted averaging scheme that transitions to local convergence at an optimal stage, and still exhibits a superlinear convergence rate nearly (up to a logarithmic factor) matching that of uniform Hessian averaging.
'
publication: '*Mathematical Programming*'
doi: 10.1007/s10107-022-01913-5
links:
- name: arXiv
  url: https://arxiv.org/abs/2204.09266
---
