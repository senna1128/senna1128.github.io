---
title: "Tensor Canonical Correlation Analysis With Convergence and Statistical Guarantees"
date: 2021-01-25
publishDate: 2020-01-27T20:57:22.564882Z
authors: [you-lin-chen, mladen-kolar, "Ruey S. Tsay"]
publication_types: ["2"]
abstract: "In many applications, such as classification of images or videos, it is of interest to develop a framework for tensor data instead of an ad-hoc way of transforming data to vectors due to the computational and under-sampling issues. In this article, we study convergence and statistical properties of two-dimensional canonical correlation analysis under an assumption that data come from a probabilistic model. We show that carefully initialized the power method converges to the optimum and provide a finite sample bound. Then we extend this framework to tensor-valued data and propose the higher-order power method, which is commonly used in tensor decomposition, to extract the canonical directions. Our method can be used effectively in a large-scale data setting by solving the inner least squares problem with a stochastic gradient descent, and we justify convergence via the theory of Lojasiewicz’s inequalities without any assumption on data generating process and initialization. For practical applications, we further develop (a) an inexact updating scheme which allows us to use the state-of-the-art stochastic gradient descent algorithm, (b) an effective initialization scheme which alleviates the problem of local optimum in nonconvex optimization, and (c) a deflation procedure for extracting several canonical components. Empirical analyses on challenging data including gene expression and air pollution indexes in Taiwan, show the effectiveness and efficiency of the proposed methodology. Our results fill a missing, but crucial, part in the literature on tensor data. Supplementary materials for this article are available online."
featured: false
publication: "*Journal of Computational and Graphical Statistics 30(3)*"
tags: ["stat.ML", "cs.LG", "stat.ME"]
url_preprint: "https://arxiv.org/abs/1906.05358"
url_code: "https://github.com/youlinchen/TCCA"
doi: 10.1080/10618600.2020.1856118
---
