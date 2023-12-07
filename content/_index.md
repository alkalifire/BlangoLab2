---
# Leave the homepage title empty to use the site title
title: The Blango Lab
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        RNA Biology of Fungal Infections @ Leibniz-HKI
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        At the intersection of RNA and fungal pathogenesis!
        
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
  
  - block: markdown
    content:
      title: Funding Sources
      subtitle: ''
      text:
        ![jpg](bmbflogo.jpg)
    design:
      columns: '2'
      background:
        image: 
          filename: bmbflogo.jpg
          filters:
            brightness: 1
          parallax: false
          position: left
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---