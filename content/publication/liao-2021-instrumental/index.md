---
title: "Instrumental Variable Value Iteration for Causal Offline Reinforcement Learning"
date: 2021-02-01
publishDate: 2021-05-10T03:14:31.124782Z
authors: ["Luofeng Liao", "Zuyue Fu", "Zhuoran Yang", "Mladen Kolar", "Zhaoran Wang"]
publication_types: ["3"]
abstract: "In offline reinforcement learning (RL) an optimal policy is learnt solely from a priori collected observational data. However, in observational data, actions are often confounded by unobserved variables. Instrumental variables (IVs), in the context of RL, are the variables whose influence on the state variables are all mediated through the action. When a valid instrument is present, we can recover the confounded transition dynamics through observational data. We study a confounded Markov decision process where the transition dynamics admit an additive nonlinear functional form. Using IVs, we derive a conditional moment restriction (CMR) through which we can identify transition dynamics based on observational data. We propose a provably efficient IV-aided Value Iteration (IVVI) algorithm based on a primal-dual reformulation of CMR. To the best of our knowledge, this is the first provably efficient algorithm for instrument-aided offline RL."
featured: false
publication: "*Technical report*"
tags: ["stat.ML", "cs.LG"]
url_preprint: https://arxiv.org/abs/2102.09907
---
