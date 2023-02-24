---
title: "Adaptive Client Sampling in Federated Learning via Online Learning with Bandit Feedback"
date: 2021-12-01
publishDate: 2022-01-02T16:45:51.529826Z
authors: ["Boxin Zhao", "Ziqi Liu", "Chaochao Chen", "Mladen Kolar", "Zhiqiang Zhang", "Jun Zhou"]
publication_types: ["3"]
abstract: "In federated learning (FL) problems, client sampling plays a key role in the convergence speed of training algorithm. However, while being an important problem in FL, client sampling is lack of study. In this paper, we propose an online learning with bandit feedback framework to understand the client sampling problem in FL. By adapting an Online Stochastic Mirror Descent algorithm to minimize the variance of gradient estimation, we propose a new adaptive client sampling algorithm. Besides, we use online ensemble method and doubling trick to automatically choose the tuning parameters in the algorithm. Theoretically, we show dynamic regret bound with comparator as the theoretically optimal sampling sequence; we also include the total variation of this sequence in our upper bound, which is a natural measure of the intrinsic difficulty of the problem. To the best of our knowledge, these theoretical contributions are novel to existing literature. Moreover, by implementing both synthetic and real data experiments, we show empirical evidence of the advantages of our proposed algorithms over widely-used uniform sampling and also other online learning based sampling strategies in previous studies. We also examine its robustness to the choice of tuning parameters. Finally, we discuss its possible extension to sampling without replacement and personalized FL objective. While the original goal is to solve client sampling problem, this work has more general applications on stochastic gradient descent and stochastic coordinate descent methods."
featured: false
publication: "*Technical report*"
tags: ["cs.LG"]
url_preprint: https://arxiv.org/abs/2112.14332
---
