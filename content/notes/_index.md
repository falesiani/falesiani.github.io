---
title: Notes
summary: Pages with math and notes
type: landing

# High-quality cover from Unsplash (remote URL supported)
cover:
  image: https://images.unsplash.com/photo-1517842645767-c319542404ab?w=1920&q=90
  alt_text: Notes

# Card thumbnails still need a local file; keep notes.jpeg in assets/media/ for the grid
cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true
      image:
        filename: notes.jpeg

sections:
  - block: collection
    id: notes
    content:
      title: Notes
      text: Here some notes on various topics. Card thumbnails use the image set in each note's front matter (default above).
      filters:
        folders:
          - notes
      order: desc
    design:
      view: article-grid
      columns: 2
      background:
        image:
          filename: "https://images.unsplash.com/photo-1517842645767-c319542404ab?w=1920&q=90"
          size: cover
          position: center
---
