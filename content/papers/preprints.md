---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: "Preprints"
subtitle: "Under review"

order : "desc"

content:
  # Page type to display. E.g. project.
  page_type: preprint
  count : 2
  # Page order. Descending (desc) or ascending (asc) date.

  filters:
    exclude_featured: false
    kinds:
      - page
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  archive:
    enable: true
    text : "see all preprints"
    link : preprint/#1
  

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
  view : 4
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
  