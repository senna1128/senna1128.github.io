---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Personalized Federated Learning with Multiple Known Clusters
subtitle: ''
summary: ''
authors:
- Boxiang Lyu
- Filip Hanzely
- Mladen Kolar
tags:
- cs.LG
categories: []
date: '2022-04-01'
lastmod: 2022-09-03T21:43:09-05:00
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
publishDate: '2022-09-04T02:43:09.712753Z'
publication_types:
- '3'
abstract: We consider the problem of personalized federated learning when there are
  known cluster structures within users. An intuitive approach would be to regularize
  the parameters so that users in the same cluster share similar model weights. The
  distances between the clusters can then be regularized to reflect the similarity
  between different clusters of users. We develop an algorithm that allows each cluster
  to communicate independently and derive the convergence results. We study a hierarchical
  linear model to theoretically demonstrate that our approach outperforms agents learning
  independently and agents learning a single shared weight. Finally, we demonstrate
  the advantages of our approach using both simulated and real-world data.
publication: '*Technical report (arXiv:2204.13619)*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2204.13619
---
