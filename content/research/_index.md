---
title: 'Research'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: markdown
    design:
      spacing:
        padding: ["400px", "0", "0", "0"]
      columns: "1"
      background:
        image:
          filename: liopholis-whitii.jpg
          size: cover
          parallax: false
  - block: collection
    content:
      title: Research Projects
      # text: Here are my main research projects.
      filters:
        folders:
          - research
    design:
      view: article-grid # card
      columns: 3
      fill-image: false
      show_date: false
      show_read_time: false
      show_read_more: false
---
