---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 40

title: Courses
subtitle: '
I have given about 450h of couses in total, for various diploma and at various levels. 


The materials I have created and co-created for my courses can be found [here](https://www.dropbox.com/scl/fo/q263e9wh8bq3subya1dxo/h?dl=0&rlkey=qlx5xj815s0lahc9sllthcbmu)


'


content:
  # Page type to display. E.g. project.
  page_type: allcourses

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: Summary
    tag: summary
  - name: Current
    tag: Current
  - name: ATER
    tag: CoursesCurrent
  - name: Ph.D.
    tag: CoursesPHD
  - name: All
    tag: "*"

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: card


  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
