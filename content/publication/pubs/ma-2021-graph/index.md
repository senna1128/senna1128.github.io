---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The Graph-Based Behavior-Aware Recommendation for Interactive News
subtitle: ''
summary: ''
authors:
- Mingyuan Ma
- Sen Na
- Hongyu Wang
- Congzhou Chen
- Jin Xu
tags: [cs.IR, cs.LG, stat.ML]
categories: []
date: '2021-06-01'
lastmod: 2023-02-28T14:15:06-08:00
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
publishDate: '2023-02-28T22:15:06.146902Z'
publication_types:
- '2'
abstract: 'Interactive news recommendation has been launched and attracted much attention recently. In this scenario, user’s behavior evolves from single click behavior to multiple behaviors including like, comment, share etc. However, most of the existing methods still use single click behavior as the unique criterion of judging user’s preferences. Further, although heterogeneous graphs have been applied in different areas, a proper way to construct a heterogeneous graph for interactive news data with an appropriate learning mechanism on it is still desired. To address the above concerns, we propose a graph-based behavior-aware network, which simultaneously considers six different types of behaviors as well as user’s demand on the news diversity. We have three mainsteps. First, we build an interaction behavior graph for multi-level and multi-category data. Second, we apply DeepWalk on the behavior graph to obtain entity semantics, then build a graph-based convolutional neural network called G-CNN to learn news representations, and an attention-based LSTM to learn behavior sequence representations. Third, we introduce core and coritivity features for the behavior graph, which measure the concentration degree of user’s interests. These features affect the trade-off between accuracy and diversity of our personalized recommendation system. Taking these features into account, our system finally achieves recommending news to different users at their different levels of concentration degrees.'
publication: '*Applied Intelligence*'
doi: 10.1007/s10489-021-02497-x
links:
- name: arXiv
  url: https://arxiv.org/abs/1812.00002
---
