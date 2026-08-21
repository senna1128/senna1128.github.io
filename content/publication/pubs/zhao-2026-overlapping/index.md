---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Overlapping Schwarz Scheme for Linear-Quadratic Programs in Continuous Time
subtitle: ''
summary: ''
authors:
- Hongli Zhao
- Mihai Anitescu
- Sen Na
tags: [math.OC, cs.CE, cs.DC, math.DS, math.NA, recent]
categories: []
date: '2026-08-01'
lastmod: 2026-08-21T00:00:00-07:00
featured: true
draft: false
aliases:
- /publication/preprints/zhao-2025-overlapping/

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
publishDate: '2026-08-01T00:00:00Z'
publication_types:
- '2'
abstract: 'We present an **optimize-then-discretize** framework for solving linear-quadratic optimal control problems (OCP) governed by time-inhomogeneous ordinary differential equations (ODEs). Our method employs a modified **overlapping Schwarz decomposition** based on the **Pontryagin Minimum Principle**, partitioning the temporal domain into overlapping intervals and independently solving **Hamiltonian systems in continuous time**. We demonstrate that the convergence is ensured by appropriately updating the boundary conditions of the individual Hamiltonian dynamics. The cornerstone of our analysis is to prove that the **exponential decay of sensitivity** (EDS) exhibited in discrete-time OCPs carries over to the continuous-time setting. Unlike the discretize-then-optimize approach, our method can flexibly incorporate different numerical integration methods for solving the resulting Hamiltonian two-point boundary-value subproblems, including adaptive-time integrators. A numerical experiment on a linear-quadratic OCP illustrates the practicality of our approach in broad scientific applications.
'
publication: '*To appear in Mathematics of Operations Research*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2510.04478
---
