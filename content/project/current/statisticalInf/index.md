---
title: Statistical Inference of Stochastic Approximation
summary: "We study the *stationarity* of SA methods, perform *online hypothesis testing*, and build *online confidence intervals*."
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

The first two plots are the histograms of the first-component error 
of the ``AI-StoSQP`` primal-dual iterates {{< math >}}$\{(\boldsymbol{x}_t, \boldsymbol{\lambda}_t)\}_t${{< /math >}}, and the third plot is {{< math >}}$95\%${{< /math >}} confidence interval of $\boldsymbol{x}^\star_1+\boldsymbol{\lambda}^\star_1$ constructed based on {{< math >}}$\{(\boldsymbol{x}_t, \boldsymbol{\lambda}_t)\}_t${{< /math >}}. Please check out [Na and Mahoney, 2022](/publication/preprints/na-2022-asymptotic) for more details.

We denote $(\boldsymbol{x}^\star, \boldsymbol{\lambda}^\star)$ as the primal-dual solution to a constrained problem with a population loss function. Statisticians aim to construct estimators based on $n$ samples and infer properties of $(\boldsymbol{x}^\star, \boldsymbol{\lambda}^\star)$. Optimization people aim to design iterative stochastic approximation (SA) methods by realizing one sample at each step and show algorithmic convergence rates. Studying stationarity of different SA methods bridges the gap between the two worlds, and allows us to do hypothesis testing and construct confidence intervals online.




