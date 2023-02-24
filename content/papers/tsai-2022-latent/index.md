---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Latent Multimodal Functional Graphical Model Estimation
subtitle: ''
summary: ''
authors:
- Katherine Tsai
- Boxin Zhao
- Oluwasanmi Koyejo
- Mladen Kolar
tags:
- stat.ME
- cs.LG
- stat.ML
categories: []
date: '2022-10-31'
lastmod: 2022-11-01T11:31:54-05:00
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
publishDate: '2022-11-01T16:31:48.789246Z'
publication_types:
- '3'
abstract: Joint multimodal functional data acquisition, where functional data from
  multiple modes are measured simultaneously from the same subject, has emerged as
  an exciting modern approach enabled by recent engineering breakthroughs in the neurological
  and biological sciences. One prominent motivation to acquire such data is to enable
  new discoveries of the underlying connectivity by combining multimodal signals.
  Despite the scientific interest, there remains a gap in principled statistical methods
  for estimating the graph underlying multimodal functional data. To this end, we
  propose a new integrative framework that models the data generation process and
  identifies operators mapping from the observation space to the latent space. We
  then develop an estimator that simultaneously estimates the transformation operators
  and the latent graph. This estimator is based on the partial correlation operator,
  which we rigorously extend from the multivariate to the functional setting. Our
  procedure is provably efficient, with the estimator converging to a stationary point
  with quantifiable statistical error. Furthermore, we show recovery of the latent
  graph under mild conditions. Our work is applied to analyze simultaneously acquired
  multimodal brain imaging data where the graph indicates functional connectivity
  of the brain. We present simulation and empirical results that support the benefits
  of joint estimation.
publication: '*Technical report*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2210.17237
---
