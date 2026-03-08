---
title: Publications
summary: Peer-reviewed publications by Yorick Lambreghts
cms_exclude: true

# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''

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
      - publications
    title: Peer-reviewed Publications
    count: 10
  design:
    columns: 1
    view: citation
    background:
      gradient_mesh:
        enable: false
---
