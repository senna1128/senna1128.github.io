---
title: Long-horizon Nonlinear Optimal Control
summary: "We study the *sensitivity* of optimal control policy to the system perturbation, and propose *offline distributed methods* and *online real-time MPC methods*."
authors: []
tags: []
categories: []
date: 2023-03-02
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
The figure above is taken from [Na et al., 2022](/publication/pubs/na-2022-convergence), which illustrates the robustness of the optimal state-control solution to system perturbations on the two boundaries, referred to as **exponential decay of sensitivity** in [Na and Anitescu, 2020](/publication/pubs/na-2020-exponential). 


We focus on solving time-varying nonlinear optimal control problems (OCPs) given by:
{{< math >}}
$$\begin{align}
\min_{\boldsymbol{x}, \boldsymbol{u}}\;\; & \sum_{k=1}^{N-1} g_k(\boldsymbol{x}_k, \boldsymbol{u}_k) + g_N(\boldsymbol{x}_N),\\
\text{s.t.}\;\; & \boldsymbol{x}_{k+1} = f_k(\boldsymbol{x}_k, \boldsymbol{u}_k),\quad k = 0,\ldots,N-1,\\
& \boldsymbol{x}_{0} = \bar{\boldsymbol{x}}_0.
\end{align}$$
{{< /math >}}
We are particularly interested in OCPs with a large number of stages $N$, which typically arise in settings with long horizons, fine time discretization resolutions, and multiple timescales. By conducting sensitivity analysis of OCPs, we propose **offline distributed methods** and **online real-time model predictive control (MPC) methods**, demonstrating promising global and local convergence guarantees.


For more details, please check out my highlighted works [Na and Anitescu, 2020](/publication/pubs/na-2020-exponential), [2023](/publication/pubs/na-2023-superconvergence), [Na, 2021](/publication/pubs/na-2021-global), [Na et al., 2021](/publication/preprints/na-2021-fast), [Na et al., 2022](/publication/pubs/na-2022-convergence), [Shin et al., 2022](/publication/preprints/shin-2022-optimal)! 

