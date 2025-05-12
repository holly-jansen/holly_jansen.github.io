---
title: "Research"
date: 2024-05-19
type: landing

design:
  spacing: '5rem'

sections:
  - block: collection
    content:
      title: Published Papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Working Papers
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    content:
      title: Other Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
