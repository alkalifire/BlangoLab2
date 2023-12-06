---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        We are always happy to discuss new project ideas!
      email: matthew.blango@leibniz-hki.de
      phone: 
      address:
        street: Adolf-Reichwein-Str. 23
        city: Jena
        region: Th
        postcode: '07745'
        country: Germany
        country_code: DE
      coordinates:
        latitude: '50.90888808927618'
        longitude: '11.572532528421092'
      directions: 
      office_hours:
      appointment_url: 
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
