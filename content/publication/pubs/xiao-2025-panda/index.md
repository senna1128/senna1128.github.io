---
title: 'Panda: partially approximate newton methods for distributed minimax optimization with unbalanced dimensions'
date: '2025-01-01'
publishDate: '2023-01-28'
authors:
- Minheng Xiao
- Chengchang Liu
- Cheng Chen
- John C.S. Lui
- Sen Na
featured: false
draft: false
publication_types:
- '2'
abstract: '
Unbalanced dimensions are crucial characteristics in various minimax optimization problems, 
such as few-shot learning and fairness-aware machine learning. In this paper, we propose a 
**communication-efficient** second-order method named PANDA (Partially Approximate Newton methods 
for Distributed minimAx) to solve problems with unbalanced dimensions. PANDA requires almost the same 
per-iteration communication cost as the first-order methods by utilizing the special problem structure 
in its design for data exchange between the client and server. More importantly, it exhibits a superior 
**linear-quadratic convergence rate** and significantly reduces the total number of communication rounds 
through the efficient use of second-order information. We also develop GIANT-PANDA based on the 
framework of PANDA, which further reduces the computation cost of the latter one by performing 
**sketching** operations on each client. Through comprehensive theoretical analysis and empirical 
evaluations, we demonstrate the superior performance of the proposed methods compared to existing 
state-of-the-art methods.
'
publication: '*Machine Learning*'
doi: 10.1007/s10994-025-06813-1
# links:
#- name: 
#  url: 
---
