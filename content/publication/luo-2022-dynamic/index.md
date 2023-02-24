---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dynamic Regret Minimization for Control of Non-stationary Linear Dynamical
  Systems
subtitle: ''
summary: ''
authors:
- Yuwei Luo
- Varun Gupta
- Mladen Kolar
tags: []
categories: []
date: '2022-06-01'
lastmod: 2022-09-03T22:16:00-05:00
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
publishDate: '2022-09-04T03:16:00.327413Z'
publication_types:
- '1'
abstract: 'We consider the problem of controlling a Linear Quadratic Regulator (LQR) system over a finite horizon $T$ with fixed and known cost matrices $Q,R$, but unknown and non-stationary dynamics $\{A_t, B_t\}$. The sequence of dynamics matrices can be arbitrary, but with a total variation, $V_T$, assumed to be $o(T)$ and unknown to the controller. Under the assumption that a sequence of stabilizing, but potentially sub-optimal controllers is available for all $t$, we present an algorithm that achieves the optimal dynamic regret of $\tilde{\cal O}\left(V_T^{2/5}T^{3/5}\right)$. With piecewise constant dynamics, our algorithm achieves the optimal regret of $\tilde{\cal O}(\sqrt{ST})$ where $S$ is the number of switches. The crux of our algorithm is an adaptive non-stationarity detection strategy, which builds on an approach recently developed for contextual Multi-armed Bandit problems. We also argue that non-adaptive forgetting (e.g., restarting or using sliding window learning with a static window size) may not be regret optimal for the LQR problem, even when the window size is optimally tuned with the knowledge of $V_T$. The main technical challenge in the analysis of our algorithm is to prove that the ordinary least squares (OLS) estimator has a small bias when the parameter to be estimated is non-stationary. Our analysis also highlights that the key motif driving the regret is that the LQR problem is in spirit a bandit problem with linear feedback and locally quadratic cost. This motif is more universal than the LQR problem itself, and therefore we believe our results should find wider application.'
publication: '*Proceedings of the 2022 ACM SIGMETRICS*'
links:
 - name: Video
   url: https://www.youtube.com/watch?v=YzS4Zf7m8q8
 - name: Slides
   url: slides.pdf
 - name: arXiv
   url: https://arxiv.org/abs/2111.03772   
doi: 10.1145/3489048.3522649
---
