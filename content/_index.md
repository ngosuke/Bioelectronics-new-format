---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-17
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{< figure src="Website pictures-01.png" class="img-lg">}}
    design:
      # background:
      #   # Choose colors such as from https://html-color-codes.info
      #   gradient_start: '#F7BE81'
      #   gradient_end: '#819FF7'
      #   # The gradient angle from 0-360 degrees
      #   gradient_angle: 90
      #   # Text color (true=light, false=dark, or remove for the dynamic theme color).
      #   text_color_light: true
      css_style: 'custom.css'
      position: 'center'
  - block: hero
    content:
      title: |
        Bioelectronics Group
      image:
        filename: Website pictures-01.png
      text: |
        <br>
        
        Welcome to the **Bioelectronics** Group at MIT.
        
        Our lab works at the interface of materials science, electronics, and neurobiology with the goal of advancing the understanding and treatment of disorders of the nervous system.
        We design, synthesize, and fabricate optoelectronic and magnetic devices that manipulate and record neuronal activity and development.
  - block: markdown
    content:
      text: <a class="twitter-timeline" data-width="400" data-height="800" data-theme="light" href="https://twitter.com/AnikeevaLab?ref_src=twsrc%5Etfw">Tweets by AnikeevaLab</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

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
      # view: card
      view: 3
      columns: 2
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---