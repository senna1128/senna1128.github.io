---
# Documentation: https://wowchemy.com/docs/managing-content/

title: High-dimensional Varying Index Coefficient Models via Stein's Identity
subtitle: ''
summary: ''
authors:
- Sen Na
- Zhuoran Yang
- Zhaoran Wang
- Mladen Kolar
tags: [cs.LG,stat.ML,stat.CO,recent]
categories: []
date: '2019-12-01'
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
publishDate: '2023-02-28T22:15:06.816791Z'
publication_types:
- '2'
abstract: "We study the parameter estimation problem for a varying index coefficient model in high dimensions. Unlike the most existing works that iteratively estimate the parameters and link functions, based on the generalized Stein's identity, we propose computationally efficient estimators for the high-dimensional parameters without estimating the link functions. We consider two different setups where we either estimate each sparse parameter vector individually or estimate the parameters simultaneously as a sparse or low-rank matrix. For all these cases, our estimators are shown to achieve optimal statistical rates of convergence (up to logarithmic terms in the low-rank setting). Moreover, throughout our analysis, we only require the covariate to satisfy certain moment conditions, which is significantly weaker than the Gaussian or elliptically symmetric assumptions that are commonly made in the existing literature. Finally, we conduct extensive numerical experiments to corroborate the theoretical results."
publication: '*Journal of Machine Learning Research*'
links:
- name: URL
  url: http://jmlr.org/papers/v20/18-705.html
- name: arXiv
  url: https://arxiv.org/abs/1810.07128
---
