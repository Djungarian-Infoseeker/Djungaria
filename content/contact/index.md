---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=nEHw8740WQungj9ay1bY-OHYfJhxEQkfKYiqFdxZU2c&cl=ffffff&w=a"></script>
      # Contact (add or remove contact options as necessary)
      email: wangyinjie@tongji.edu.cn
      #phone: 888 888 88 88
      address:
        street: 1239 Siping Road
        city: Yangpu District
        region: Shanghai
        postcode: '200092'
        country: P.R. China
        country_code: CN
      directions: Ocean Building
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '31.284906919181495'
        longitude: '121.50147636149214'  
      directions: Ocean Building
      #appointment_url: 'https://calendly.com'
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
