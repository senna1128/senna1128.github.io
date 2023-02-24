---
# Documentation: https://wowchemy.com/docs/managing-content/

title: On the Lasso for Graphical Continuous Lyapunov Models
subtitle: ''
summary: ''
authors:
- Philipp Dettling
- Mathias Drton
- Mladen Kolar
tags:
- math.ST
- stat.TH
categories: []
date: '2022-08-29'
lastmod:
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
publishDate: '2022-09-04T01:36:31.169613Z'
publication_types:
- '3'
abstract: Graphical continuous Lyapunov models offer a new perspective on modeling causally interpretable dependence structure in multivariate data by treating each independent observation as a one-time cross-sectional snapshot of a temporal process. Specifically, the models assume the observations to be cross-sections of independent multivariate Ornstein-Uhlenbeck processes in equilibrium. The Gaussian equilibrium exists under a stability assumption on the drift matrix, and the equilibrium covariance matrix is determined by the continuous Lyapunov equation. Each graphical continuous Lyapunov model assumes the drift matrix to be sparse with a support determined by a directed graph. A natural approach to model selection in this setting is to use an $ell_1$-regularization approach that seeks to find a sparse approximate solution to the Lyapunov equation when given a sample covariance matrix. We study the model selection properties of the resulting lasso technique by applying the primal-dual witness technique for support recovery. Our analysis uses special spectral properties of the Hessian of the considered loss function in order to arrive at a consistency result. While the lasso technique is able to recover useful structure, our results also demonstrate that the relevant irrepresentability condition may be violated in subtle ways, preventing perfect recovery even in seemingly favorable settings.
publication: '*Technical report*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2208.13572
---
