---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Opto-Mechatronic Laboratory
      # image:
      #   filename: welcome.jpg
      text: |
        <br>
        The Opto-Mechatronic Laboratory is at the forefront of advanced optical and mechatronic research, combining cutting-edge technologies to push the boundaries of science and engineering.

        {{% callout note %}}
        Our key research areas include:
        - 🔬 Optical Laser Systems & Applications
        - 💡 Semiconductor Device Development
        - 🦿 Medical Implant Technologies
        - 🖨️ Advanced 3D Printing & Manufacturing
        - 🤖 Machine Learning & Deep Learning Integration
        {{% /callout %}}

        Our interdisciplinary approach brings together expertise in optics, electronics, mechanical engineering, and artificial intelligence to develop innovative solutions for real-world challenges.
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '2'

  - block: markdown
    content:
      title: Members
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
