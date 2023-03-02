---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Adaptive Stochastic Sequential Quadratic Programming with Differentiable Exact Augmented Lagrangians
subtitle: ''
summary: ''
authors:
- Sen Na
- Mihai Anitescu
- Mladen Kolar
tags: [math.OC, math.NA, cs.NA, stat.CO, stat.ML, recent]
categories: []
date: '2022-06-01'
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
publishDate: '2023-02-28T22:15:05.404479Z'
publication_types:
- '2'
abstract: 'We consider solving nonlinear optimization problems with a stochastic objective and deterministic equality constraints. We assume for the objective that its evaluation, gradient, and Hessian are inaccessible, while one can compute their stochastic estimates by, for example, subsampling. We propose a stochastic algorithm based on sequential quadratic programming (SQP) that uses a differentiable exact augmented Lagrangian as the merit function. To motivate our algorithm design, we first revisit and simplify an old SQP method [(Lucidi S, 1990)](https://doi.org/10.1007/BF00940474) developed for solving deterministic problems, which serves as the skeleton of our stochastic algorithm. Based on the simplified deterministic algorithm, we then propose a non-adaptive SQP for dealing with stochastic objective, where the gradient and Hessian are replaced by stochastic estimates but the stepsizes are deterministic and prespecified. Finally, we incorporate a recent stochastic line search procedure [(Paquette and Scheinberg, 2020)](https://doi.org/10.1137/18M1216250) into the non-adaptive stochastic SQP to adaptively select the random stepsizes, which leads to an adaptive stochastic SQP. The global “almost sure” convergence for both non-adaptive and adaptive SQP methods is established. Numerical experiments on nonlinear problems in CUTEst test set demonstrate the superiority of the adaptive algorithm.'
publication: '*Mathematical Programming*'
doi: 10.1007/s10107-022-01846-z
links:
- name: arXiv
  url: https://arxiv.org/abs/2102.05320
---
