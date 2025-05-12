---
title: 'Teaching'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'


sections:
  - block: collection
    id: papers
    content:
      title: Teaching philosophy
      filters:
        folders:
          - teaching
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Section leader
      text: ""
      filters:
        folders:
          - teaching
        exclude_featured: false
    design:
      view: citation

  - block: collection
    content:
      title: Teaching assistant
      text: ""
      filters:
        folders:
          - teaching
        exclude_featured: false
    design:
      view: citation
---
