---
title: Contact
date: 2023-07-18

type: landing

sections:
  - block: contact
    content:
      title: Contact
      email: test@ugr.es
      phone: '+34 958 248 994'
      address:
        street: 'Periodista Daniel Saucedo Aranda, s/n'
        city: Granada
        region: Granada
        postcode: '18071'
        country: Spain
        country_code: ES
      coordinates:
        latitude: '37.19722222'
        longitude: '-3.62388889'
      # contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
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
