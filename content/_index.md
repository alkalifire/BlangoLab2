---
# Leave the homepage title empty to use the site title
title: The Blango Lab
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: RNA Biology of Fungal Infections
        content: 
        align: left
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.8
          position: center
          color: '#666'
      - title: 
        content: ''
        align: center
        background:
          image:
            filename: preview.png
            filters:
              brightness: 0.8
          position: center
          color: '#555'
      - title: 
        content: ''
        align: right
        background:
          image:
            filename: page2.jpeg
            filters:
              brightness: 0.8
          position: center
          color: '#333'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '200px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000

  - block: hero
    content:
      title: |
        **<div style="text-align: center">The Blango Lab</div>** 
          ## <div style="text-align: center"><span style="color:darkred">Leibniz Institute for Natural Product Research and Infection Biology (Leibniz-HKI)</span></div> ##
      image:
        filename: afu2.jpg
      text: |
        
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---  