---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'AEGCN: An Autoencoder-Constrained Graph Convolutional Network'
subtitle: ''
summary: ''
authors:
- Mingyuan Ma
- Sen Na
- Hongyu Wang
tags: [cs.LG,stat.ML]
categories: []
date: '2021-04-01'
lastmod: 2023-02-28T14:15:07-08:00
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
publishDate: '2023-02-28T22:15:06.943540Z'
publication_types:
- '2'
abstract: 'We propose a novel neural network architecture, called autoencoder-constrained graph convolutional network, to solve node classification task on graph domains. As suggested by its name, the core of this model is a convolutional network operating directly on graphs, whose hidden layers are constrained by an autoencoder. Comparing with vanilla graph convolutional networks, the autoencoder step is added to reduce the information loss brought by Laplacian smoothing. We consider applying our model on both homogeneous graphs and heterogeneous graphs. For homogeneous graphs, the autoencoder approximates to the adjacency matrix of the input graph by taking hidden layer representations as encoder and another one-layer graph convolutional network as decoder. For heterogeneous graphs, since there are multiple adjacency matrices corresponding to different types of edges, the autoencoder approximates to the feature matrix of the input graph instead, and changes the encoder to a particularly designed multi-channel pre-processing network with two layers. In both cases, the error occurred in the autoencoder approximation goes to the penalty term in the loss function. In extensive experiments on citation networks and other heterogeneous graphs, we demonstrate that adding autoencoder constraints significantly improves the performance of graph convolutional networks. Further, we notice that our technique can be applied on graph attention network to improve the performance as well. This reveals the wide applicability of the proposed autoencoder technique.'
publication: '*Neurocomputing*'
doi: 10.1016/j.neucom.2020.12.061
links:
- name: arXiv
  url: https://arxiv.org/abs/2007.03424
---
