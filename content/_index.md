---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-03-04
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: hero
    content:
      title: "Yorick Lambreghts"
      text: "Animal behaviour and evolution"
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["100px", "0", "320px", "0"]
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
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: |-
        My research focuses on the evolution of sociality in lizards with a particular interest in the role of kin recognition. 
        I am developing a method to make modifications to the genome of Australian lizards using CRISPR-Cas9 in collaboration with [Prof Martin Whiting](https://researchers.mq.edu.au/en/persons/martin-whiting/) and [Dr Oliver Griffith](https://researchers.mq.edu.au/en/persons/oliver-griffith/) at [Macquarie University](https://www.mq.edu.au/).
        This technique will open the door for a whole suit of new opportunities for research on social evolution/recognition, as well as virtually every other aspect of Australian reptile biology.

        During my PhD, I focussed on kin recognition itself, its importance in the early evolution of sociality and how it was refined as social systems became increasingly complex. 
        While I was based at the [University of Tasmania](https://www.utas.edu.au/) in Hobart ([BEER group](https://beergrouputas.wordpress.com/)), my field and experimental work took place at [Macquarie University](https://www.mq.edu.au/) in Sydney ([Lizardlab](https://whitinglab.com/)). 
        I am currently working on getting this work published!

        Before moving to Australia I completed my Bachelor's and Master's degrees at the [University of Antwerp](https://www.uantwerpen.be/en/) in Belgium. During this time, I studied urbanisation and island effects in lizards, and animal personalities in birds.
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: 'About Me'
        # education: ''
        interests: 'Expertise'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: false

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: collection
    id: science
    content:
      title: My Research
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
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
---
