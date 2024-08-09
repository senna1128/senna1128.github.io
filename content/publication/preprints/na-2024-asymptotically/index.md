---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Asymptotically Optimal Method for Constrained Stochastic Optimization
subtitle: ''
summary: ''
authors:
- Sen Na
- Yihang Gao
- Michael K. Ng
- Michael W. Mahoney
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: [math.OC, stat.CO, stat.ML]
categories: []
date: '2024-01-27'
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
publishDate: '2023-02-28T22:15:08.487247Z'
publication_types:
- '3'
abstract: "
We perform statistical inference for the solution of stochastic optimization problems with equality and box inequality constraints. The considered problems are prevalent in statistics and machine learning, encompassing constrained $M$-estimation, PDE-constrained problems, physics-inspired networks, and algorithmic fairness. We introduce a stochastic sequential quadratic programming method (StoSQP) to solve these problems, where we determine the search direction by performing a quadratic approximation of the objective with a linear approximation of the constraints. Despite having access to unbiased estimates of population gradients, a key challenge in constrained problems lies in dealing with the bias in the search direction. To address this challenge, we introduce a novel **gradient averaging technique to debias the direction step**, leading to Debiased-StoSQP. Our method achieves **global almost sure convergence** and exhibits **local asymptotic normality** with an optimal limiting covariance matrix in Hájek and Le Cam's sense. Additionally, a plug-in covariance matrix estimator is provided for practical inference purposes. To our knowledge, Debiased-StoSQP is the first **fully online** method to achieve **asymptotic minimax optimality** without relying on projection operators to the constraint set, which are incomputable for nonlinear problems. Through extensive experiments on benchmark nonlinear problems in the CUTEst test set, as well as on constrained generalized linear models and portfolio allocation problems, with both synthetic and real data, we demonstrate the superior performance of the method.
"
publication: '*in submission*'
links:
- name: PDF
  url: /publication/preprints/na-2024-asymptotically/main.pdf
---
