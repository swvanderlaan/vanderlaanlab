---
# Documentation: https://wowchemy.com/docs/widget/portfolio/
widget: portfolio
headless: true  # This file represents a page section.

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

# ... Put Your Section Options Here (title etc.) ...

content:
  # Page type to display. E.g. project.
  page_type: project

# Uncomment to only show content with specific tags
#  filters:
#    tags:
#      - featured project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below)
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: All
      tag: '*'
    - name: Genetics
      tag: genetics
    - name: Functional Genomics
      tag: functional-genomics
    - name: ExpressScan
      tag: ExpressScan
    - name: Other
      tag: other
      
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact  
  #   3 = Card
  #   5 = Showcase
  view: 5
  # For Showcase view, flip alternate rows?
  flip_alt_rows: true
---
