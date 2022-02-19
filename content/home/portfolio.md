---
widget: portfolio
widget_id: portfolio
headless: true
weight: 10
title: Maria Pangoli
subtitle: My portfolio
active: true
content:
  page_type: project
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Street Art
    tag: STREET_ART
  - name: Case studies
    tag: CASE_STUDIES
  - name: Mixed media
    tag: MIXED_MEDIA

design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---
