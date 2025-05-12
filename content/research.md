---
title: 'Research'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'


sections:
  - block: research-published papers
    id: papers
    content:
      username: published papers
      title: Published papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: research-working papers
    content:
      username : working papers
      title: Working papers
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: research-other published
    content:
      username: other publications
      title: Other publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
