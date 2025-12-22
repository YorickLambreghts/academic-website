---
date: "2024-05-19"
design:
  spacing: 4rem
title: publications
type: landing

sections:
- block: markdown
  design:
    spacing:
      padding: ["400px", "0", "0", "0"]
    columns: "1"
    background:
      image:
        filename: tiliqua-rugosa.jpg
        size: cover
        parallax: false
- block: collection
  content:
    filters:
      featured_only: false
      folders:
      - publication
    title: Peer-reviewed Publications
    count: 6
  design:
    columns: 2
    view: citation
---