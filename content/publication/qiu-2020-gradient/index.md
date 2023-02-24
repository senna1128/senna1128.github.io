---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Gradient-Variation Bound for Online Convex Optimization with Constraints
subtitle: ''
summary: ''
authors:
- Shuang Qiu
- Xiaohan Wei
- Mladen Kolar
tags:
- math.OC
- cs.LG
- stat.ML
categories: []
date: '2022-11-01'
lastmod: 2022-11-26T13:11:03-06:00
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
publishDate: '2022-11-26T19:11:03.132079Z'
publication_types:
- '1'
abstract: We study online convex optimization with constraints consisting of multiple functional constraints and a relatively simple constraint set, such as a Euclidean ball. As enforcing the constraints at each time step through projections is computationally challenging in general, we allow decisions to violate the functional constraints but aim to achieve a low regret and cumulative violation of the constraints over a horizon of $T$ time steps. First-order methods achieve an $\mathcal O(\sqrt T)$ regret and an $\mathcal O(1)$ constraint violation, which is the best-known bound, but do not take into account the structural information of the problem. Furthermore, the existing algorithms and analysis are limited to Euclidean space. In this paper, we provide an emphinstance-dependent bound for online convex optimization with complex constraints obtained by a novel online primal-dual mirror-prox algorithm. Our instance-dependent regret is quantified by the total gradient variation $V_\*(T)$ in the sequence of loss functions. The proposed algorithm works in emphgeneral non-Euclidean spaces and simultaneously achieves an $\mathcal O(\sqrt{V_\*(T)})$ regret and an $\mathcal O(1)$ constraint violation, which is never worse than the best-known $(\mathcal O(\sqrt T), \mathcal O(1) )$ result and improves over previous works that applied mirror-prox-type algorithms for this problem achieving $\mathcal O(T^{2/3})$ regret and constraint violation. Finally, our algorithm is computationally efficient, as it only performs mirror descent steps in each iteration instead of solving a general Lagrangian minimization problem.
publication: '*AAAI Conference on Artificial Intelligence (to appear)*'
links:
- name: arXiv
  url: https://arxiv.org/pdf/2006.12455v2
---
