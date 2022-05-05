---
widget: portfolio
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title: ""
subtitle: ''

# Order that this section appears on the page.
weight: 2

content:
  # Choose which content to display in the widget
  filters:
  # Folders to display content from
  folders:
  - project
# Uncomment below to only show content with specific tags:
#    tags:
#      - Machine Learning

# Field to sort by, such as Date or Title
sort_by: 'Title'
sort_ascending: true

# Filter toolbar (optional).
# Add or remove as many filters (`filter_button` instances) as you like.
# To show all items, set `tag` to "*".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove toolbar, delete/comment all instances of `filter_button` below.
filter_button:
# - name: All
# tag: '*'
# - name: Volunteer
# tag: Volunteer
# - name: Resources
# tag: Resources

# Default filter toolbar button (e.g. 0 corresponds to the first `filter_button` instance above)
filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
# Choose a listing view
view: 5
# For Showcase view, flip alternate rows?
flip_alt_rows: true
---