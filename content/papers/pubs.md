---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: "Publications"
subtitle: ""

order : "desc"

content:
  page_type: publication
  count : 10
  filters:
    exclude_featured: false
    kinds:
      - page
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0
  archive:
    enable: true
    text : "see all publications"
    link : publication/
  
design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
  view : 4
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
  