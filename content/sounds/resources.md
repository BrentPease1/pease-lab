---
widget: portfolio
headless: true  # This file represents a page section.
weight: 2 # Order that this section appears on the page.
active: true #active this widget? true/false


# ... Put Your Section Options Here (title etc.) ...
title: "Resources"
subtitle: ""



content:
  # Choose which content to display in the widget
  filters: 
  # Folders to display content from
  folders:
  - volunteer
  - about
  - contact


# Field to sort by, such as Date or Title
sort_by: 'Date'
sort_ascending: false

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: All
      tag: '*'
    - name: Volunteer
      tag: Volunteer
    - name: About
      tag: About

  # Default filter toolbar button (e.g. 0 corresponds to the first `filter_button` instance above)
  filter_default: 0


# Default filter toolbar button (e.g. 0 corresponds to the first `filter_button` instance above)
filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'
# Choose a listing view
view: Masonry
# For Showcase view, flip alternate rows?
flip_alt_rows: true
---
