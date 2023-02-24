---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Pessimism meets VCG: Learning Dynamic Mechanism Design via Offline Reinforcement
  Learning'
subtitle: ''
summary: ''
authors:
- Boxiang Lyu
- Zhaoran Wang
- Mladen Kolar
- Zhuoran Yang
tags:
- cs.LG
- cs.GT
- stat.ML
categories: []
date: '2022-07-01'
lastmod: 2022-09-03T21:37:25-05:00
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
publishDate: '2022-09-04T02:37:25.407391Z'
publication_types:
- '1'
abstract: 'Dynamic mechanism design has garnered significant attention from both computer
  scientists and economists in recent years. By allowing agents to interact with the
  seller over multiple rounds, where agents’ reward functions may change with time
  and are state-dependent, the framework is able to model a rich class of real-world
  problems. In these works, the interaction between agents and sellers is often assumed
  to follow a Markov Decision Process (MDP). We focus on the setting where the reward
  and transition functions of such an MDP are not known a priori, and we are attempting
  to recover the optimal mechanism using an a priori collected data set. In the setting
  where the function approximation is employed to handle large state spaces, with
  only mild assumptions on the expressiveness of the function class, we are able to
  design a dynamic mechanism using offline reinforcement learning algorithms. Moreover,
  learned mechanisms approximately have three key desiderata: efficiency, individual
  rationality, and truthfulness. Our algorithm is based on the pessimism principle
  and only requires a mild assumption on the coverage of the offline data set. To
  the best of our knowledge, our work provides the first offline RL algorithm for
  dynamic mechanism design without assuming uniform coverage.'
publication: '*Proceedings of the 39th International Conference on Machine Learning (ICML) 2022*'
links:
- name: PDF
  url: https://proceedings.mlr.press/v162/lyu22b/lyu22b.pdf
- name: Video
  url: https://icml.cc/virtual/2022/spotlight/17344
- name: Slides
  url: https://icml.cc/media/icml-2022/Slides/17344.pdf
- name: arXiv
  url: https://arxiv.org/abs/2205.02450  
---
