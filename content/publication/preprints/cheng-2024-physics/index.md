---
title: Physics-Informed Neural Networks with Trust-Region Sequential Quadratic Programming
date: '2024-09'
publishDate: '2024-09-01'
authors:
- Xiaoran Cheng
- Sen Na
featured: false
draft: false

publication_types:
- '3'
abstract: '
Physics-Informed Neural Networks (PINNs) represent a significant advancement in Scientific Machine Learning (SciML), which integrate physical domain knowledge into an empirical loss function as soft constraints and apply existing machine learning methods to train the model. However, recent research has noted that PINNs may fail to learn relatively complex Partial Differential Equations (PDEs). This paper addresses the failure modes of PINNs by introducing a novel, hard-constrained deep learning method -- trust-region Sequential Quadratic Programming (trSQP-PINN). In contrast to directly training the penalized soft-constrained loss as in PINNs, our method performs a linear-quadratic approximation of the hard-constrained loss, while leveraging the soft-constrained loss to adaptively adjust the trust-region radius. We only trust our model approximations and make updates within the trust region, and such an updating manner can overcome the ill-conditioning issue of PINNs. We also address the computational bottleneck of second-order SQP methods by employing quasi-Newton updates for second-order information, and importantly, we introduce a simple pretraining step to further enhance training efficiency of our method. We demonstrate the effectiveness of trSQP-PINN through extensive experiments. Compared to existing hard-constrained methods for PINNs, such as penalty methods and augmented Lagrangian methods, trSQP-PINN significantly improves the accuracy of the learned PDE solutions, achieving up to 1-3 orders of magnitude lower errors. Additionally, our pretraining step is generally effective for other hard-constrained methods, and experiments have shown the robustness of our method against both problem-specific parameters and algorithm tuning parameters.
'
featured: false
publication: '*arXiv preprint arXiv:2409.10777*'
tags: [cs.LG, math.NA]
#url_code: 
#doi: 
links:
- name: arXiv
  url: https://arxiv.org/abs/2409.10777
---
