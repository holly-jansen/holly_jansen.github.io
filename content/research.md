---
title: 'Research'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'


sections:
  - block: collection
    id: papers
    content:
      title: Published papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Working papers
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Other publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
