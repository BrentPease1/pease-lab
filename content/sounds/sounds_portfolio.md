---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 2

title: 'Sounds of Nature'
subtitle: 'Discover Biodiversity Through Sound'

content:
  # choose which content to display in widget
  filters:
    #folders to display content from
    folders:
      - ./sounds/SoN
      
  # Page type to display. E.g. project.
  page_type: project

design:
  columns: '1'
  view: 3
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---