---
title: "High-dimensional Functional Graphical Model Structure Learning via Neighborhood Selection Approach"
date: 2021-05-01
publishDate: 2022-01-02T21:57:50.057508Z
authors: ["Boxin Zhao", "Shengjun Zhai", sam-wang, "Mladen Kolar"]
publication_types: ["3"]
abstract: "Undirected graphical models have been widely used to model the conditional independence structure of high-dimensional random vector data for years. In many modern applications such as EEG and fMRI data, the observations are multivariate random functions rather than scalars. To model the conditional independence of this type of data, functional graphical models are proposed and have attracted an increasing attention in recent years. In this paper, we propose a neighborhood selection approach to estimate Gaussian functional graphical models. We first estimate the neighborhood of all nodes via function-on-function regression, and then we can recover the whole graph structure based on the neighborhood information. By estimating conditional structure directly, we can circumvent the need of a well-defined precision operator which generally does not exist. Besides, we can better explore the effect of the choice of function basis for dimension reduction. We give a criterion for choosing the best function basis and motivate two practically useful choices, which we justified by both theory and experiments and show that they are better than expanding each function onto its own FPCA basis as in previous literature. In addition, the neighborhood selection approach is computationally more efficient than fglasso as it is more easy to do parallel computing. The statistical consistency of our proposed methods in high-dimensional setting are supported by both theory and experiment."
featured: false
publication: "*Technical report*"
tags: ["stat.ML", "cs.LG", "stat.ME"]
url_preprint: https://arxiv.org/abs/2105.02487
---
