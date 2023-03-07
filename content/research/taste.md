---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: accomplishments
# This file represents a page section.
headless: true
# Order that this section appears on the page.
weight: 20
active : true

title: Research <br> Taste
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

There are **<span style='color: red;'>three common threads</span>** of my research topics: 

* I recover model parameters by optimizing certain loss functions that can only be evaluated in a **<span style='color: red;'>noisy</span>** way (e.g., by sampling). 
* The model parameters have to satisfy constraints in a **<span style='color: red;'>hard</span>** way, which do not merely provide suggestions and lead to an inductive bias.
* The uncertainty quantification and inference of the methods are crucial to draw any **<span style='color: red;'>statistically significant</span>** conclusions.  

More specifically, my constrained problems have the following components: 
- The model parameters $\boldsymbol{x}$ can be in low, high, or infinite dimensions (e.g., a policy mapping in control problems). 

- The loss functions can be in purely stochastic form $E_{\xi\sim\mathcal{P}}[f(\boldsymbol{x};\xi)]$, empirical finite-sum form $\frac{1}{n}\sum_{i=1}^{n}f_i(\boldsymbol{x})$, or integral form $\int_{t\in\mathcal{T}}(\boldsymbol{x}(t) - \boldsymbol{x}_{ref}(t))^2 dt$.

- The constraints on $\boldsymbol{x}$ can be in equality, inequality, deterministic, or expected forms. In addition, $\boldsymbol{x}$ can be restricted to Riemannian manifolds or satisfy some PDEs.

Due to constraints' nonlinearity, the projected first-order methods are often inapplicable. Therefore, I primarily focus on second-order primal-dual methods and allow Hessians to be approximated imprecisely. 



