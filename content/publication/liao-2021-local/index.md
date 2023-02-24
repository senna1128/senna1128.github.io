---
title: Local AdaGrad-type algorithm for stochastic convex-concave optimization
date: '2022-11-01'
publishDate: '2022-11-26T18:50:06.013078Z'
authors:
- Luofeng Liao
- Li Shen
- Jia Duan
- Mladen Kolar
- Dacheng Tao
publication_types:
- '2'
abstract: 'Large scale convex-concave minimax problems arise in numerous applications, including game theory, robust training, and training of generative adversarial networks. Despite their wide applicability, solving such problems efciently and efectively is challenging in the presence of large amounts of data using existing stochastic minimax methods. We study a class of stochastic minimax methods and develop a communication-efcient distributed stochastic extragradient algorithm, LocalAdaSEG, with an adaptive learning rate suitable for solving convex-concave minimax problems in the Parameter-Server model. LocalAdaSEG has three main features: (1) a periodic communication strategy that reduces the communication cost between workers and the server; (2) an adaptive learning rate that is computed locally and allows for tuning-free implementation; and (3) theoretically, a nearly linear speed-up with respect to the dominant variance term, arising from the estimation of the stochastic gradient, is proven in both the smooth and nonsmooth convex-concave settings. LocalAdaSEG is used to solve a stochastic bilinear game, and train a generative adversarial network. We compare LocalAdaSEG against several existing optimizers for minimax problems and demonstrate its efcacy through several experiments in both homogeneous and heterogeneous settings.'
featured: false
publication: '*Machine Learning*'
tags:
- cs.LG
- cs.DC
- math.OC
doi: 10.1007/s10994-022-06239-z
links:
- name: arXiv
  url: https://arxiv.org/abs/2106.10022
- name: PDF
  url: Liao2021Local.pdf
---
