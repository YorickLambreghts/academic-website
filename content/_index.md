---
date: "2022-10-24"
design:
  spacing: 6rem
title: ""
type: landing  
  
sections:
- block: hero
  content:
    title: "Yorick Lambreghts"
    text: "Evolution and Behavioural Biology"
  design:
    spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["100px", "0", "200px", "0"]
    columns: "1"
    background:
      image: 
        filename: home-banner.jpg
        filters:
          brightness: 1.2 # determines transparancy (1=transparent; 0=opaque)
        size: cover
        parallax: true
        text_color_light: false
- block: resume-biography-3
  id: aboutme
  content:
    # button:
    #   text: Download CV
    #   url: uploads/resume.pdf
    text: ""
    username: admin
  # design:
  #   background:
  #     color: black
  #     image:
  #       filename: stacked-peaks.svg
  #       filters:
  #         brightness: 1
  #       parallax: false
  #       position: center
  #       size: cover
  #   css_class: dark
# - block: markdown
#   content:
#     subtitle: ""
#     text: "Use this area to speak to your mission. I'm a research scientist in the
#       Moonshot team at DeepMind. I blog about machine learning, deep learning, and
#       moonshots.\n\nI apply a range of qualitative and quantitative methods to comprehensively
#       investigate the role of science and technology in the economy.\n\nPlease reach
#       out to collaborate \U0001F603"
#     title: "PhD research"
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       folders:
#       - research
#     title: Research
#   design:
#     columns: 2
#     view: article-grid 

# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: 2
#     view: article-grid
#   id: papers
# - block: collection
#   content:
#     filters:
#       exclude_featured: false
#       folders:
#       - publication
#     text: ""
#     title: Recent Publications
#   design:
#     view: citation
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: 1
#     view: article-grid
#   id: talks
# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     page_type: post
#     subtitle: ""
#     text: ""
#     title: Recent News
#   design:
#     spacing:
#       padding:
#       - 0
#       - 0
#       - 0
#       - 0
#     view: date-title-summary
#   id: news
---
