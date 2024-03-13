---
title: Deterministically Constrained Stochastic Optimization
summary: "The problems appear widely in *constrained M-estimation*, *semiparametric models*, and *constrained neural networks*."
authors: []
tags: []
categories: []
date: 2023-03-03
show_date: false
external_link: ""
image:
  caption: ""
  focal_point: ""
  preview_only: false
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
slides: ""
---

The above problem prominently appears in machine learning and statistics. For example, given $n$ response-feature data pairs {{< math >}}$\{(b_i,\boldsymbol{a}_i)\}_{i=1}^n${{< /math >}}, we can let {{< math >}}$\mathcal{P} = \text{Uniform}(\{(b_i,\boldsymbol{a}_i)\}_{i=1}^n)${{< /math >}} be the empirical distribution. Then, $f$ reduces to the empirical loss 
$f(\boldsymbol{x}) = \frac{1}{n}\sum_{i=1}^n F(\boldsymbol{x}; b_i, \boldsymbol{a}_i)$, and we arrive at the $M$-estimation problems.
The constraints that encode prior model knowledge are ubiquitous in practice. For example, in semiparametric estimation, we require the true parameter $\boldsymbol{x}^\star$ to satisfy {{< math >}}$\boldsymbol{x}^\star\in\{\boldsymbol{x}\in\mathbb{R}^d:\|\boldsymbol{x}\|^2 = 1, \boldsymbol{x}_1>0\}${{< /math >}} to resolve the identifiability issue ([Na et al., 2019](/publication/pubs/na-2019-high), [Na and Kolar, 2021](/publication/pubs/na-2021-high)). 

Check out my highlighted works [Na et al., 2022](/publication/pubs/na-2022-adaptive), [2023](/publication/pubs/na-2023-inequality), [Fang et al., 2022](/publication/preprints/fang-2022-fully)!


