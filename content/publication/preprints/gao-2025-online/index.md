---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Online Inference of Constrained Optimization: Primal-Dual Optimality and Sequential Quadratic Programming'
subtitle: ''
summary: ''
authors:
- Yihang Gao
- Michael K. Ng
- Michael W. Mahoney
- Sen Na
tags: [math.OC, stat.CO, stat.ML]
categories: []
date: '2025-11-29'
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
publishDate: '2025-11-28T22:15:08.487247Z'
publication_types:
- '3'
abstract: 'We study online statistical inference for the solutions of stochastic optimization problems with equality and 
inequality constraints. Such problems are prevalent in statistics and machine learning, encompassing constrained $M$-estimation, 
physics-informed models, safe reinforcement learning, and algorithmic fairness. We develop a **stochastic sequential quadratic programming** 
(SSQP) method to solve these problems, where the step direction is computed by sequentially performing a quadratic approximation of 
the objective and a linear approximation of the constraints. Despite having access to unbiased estimates of population gradients, 
a key challenge in constrained stochastic problems lies in dealing with the bias in the step direction. As such, we apply a 
momentum-style **gradient moving-average technique** within SSQP to debias the step. We show that our method achieves global 
almost-sure convergence and exhibits local asymptotic normality with an **optimal** primal-dual limiting covariance matrix in the 
sense of Hájek and Le Cam. In addition, we provide a plug-in covariance matrix estimator for practical inference. To our knowledge, 
the proposed SSQP method is the **first fully online method** that attains primal-dual asymptotic minimax optimality without relying on 
projection operators onto the constraint set, which are generally intractable for nonlinear problems. Through extensive experiments 
on benchmark nonlinear problems, as well as on constrained generalized linear models and portfolio allocation problems using both 
synthetic and real data, we demonstrate superior performance of our method, showing that the method and its asymptotic behavior not 
only solve constrained stochastic problems efficiently but also provide valid and practical online inference in real-world applications.
'
publication: '*submitted*'
links:
- name: PDF
  url: /publication/preprints/gao-2025-online/main.pdf
---
