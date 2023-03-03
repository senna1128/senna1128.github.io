---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: accomplishments
# This file represents a page section.
headless: true
# Order that this section appears on the page.
weight: 10
active : true  

title: Research Overview
subtitle: 

# Summary for listings and search engines
summary:

# Link this post with a project
projects:
# Date published
date: ""
# Date updated
lastmod: ""

# Show this page in the Featured widget?
featured: false
image:
  caption: ''
  focal_point: ""
  placement: 2
  preview_only: false

content:
  # Page type to display. E.g. project.
  page_type: research
  filters:
    exclude_featured: false
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

I was trained as a [statistician](https://en.wikipedia.org/wiki/Statistician) in my Ph.D. study, but my research interests span high-dimensional statistics, nonlinear and nonconvex optimization, control theory, and scientific machine learning. My ultimate research goal is to develop a new generation of **<span style='color: red;'>stochastic numerical methods</span>** that exhibit promising **<span style='color: red;'>statistical and computational efficiency</span>** for solving knotty problems that appeared in statistics and engineering.

I develop practical methods by leveraging classical optimization techniques (e.g., exact penalty, augmented Lagrangian, trust region, active set, and interior-point methods) and reforming these techniques to address pressing modern challenges, such as **<span style='color: red;'>scalability</span>**, **<span style='color: red;'>reliability</span>**, and **<span style='color: red;'>adaptivity</span>**.

Toward the ultimate goal, my current research mainly includes the following topics:

* <font size="3"> Constrained stochastic optimization </font> 
* <font size="3"> Statistical inference of stochastic second-order methods </font> 
* <font size="3"> ML problems with physics-informed constraints </font>
* <font size="3"> Stochastic real-time optimal control \& model predictive control </font> 
* <font size="3"> Semiparametric graphical models </font> 

There are **<span style='color: red;'>three common threads</span>** of the above topics: 

* We recover model parameters by optimizing certain loss functions that can only be evaluated in a **<span style='color: red;'>noisy</span>** way. 
* The model parameters have to satisfy constraints in a **<span style='color: red;'>hard</span>** way, which do not merely provide suggestions and lead to an inductive bias.
* The uncertainty quantification and inference of the methods are crucial to draw any **<span style='color: red;'>statistically significant</span>** conclusions.  

More specifically, the components of constrained problems under investigation can be summarized as follows: 
- The model parameters $\boldsymbol{x}$ can be in low, high, or infinite dimensions (e.g., policy mapping in control problems). 

- The loss functions can be in purely stochastic form $E_{\xi\sim\mathcal{P}}[f(\boldsymbol{x};\xi)]$, empirical finite-sum form $\frac{1}{n}\sum_{i=1}^{n}f_i(\boldsymbol{x})$, or integral form $\int_{t\in\mathcal{T}}(\boldsymbol{x}(t) - \boldsymbol{x}_{ref}(t))^2 dt$. 
- The constraints on $\boldsymbol{x}$ can be in equality, inequality, deterministic, or expected forms. In addition, $\boldsymbol{x}$ can be restricted on Riemannian manifolds or satisfy some PDEs.

Due to the nonlinearity of constraints, the projected first-order methods are often not applicable. Thus, I primarily focus on second-order primal-dual methods, but Hessians can be approximated imprecisely. 



