---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text:
      email: leonel.medina@usach.cl
      phone: +56 22 718 0925 
      address:
        street: Av Víctor Jara 3659
        city: Estación Central
        region: RM
        postcode: '9170124'
        country: Chile
        country_code: CL
      coordinates:
        latitude: '-33.449781'
        longitude: '-70.687296'
      directions: Sector EAO, por Metro U de Santiago
      #office_hours:
      #  - ''
      #  - ''
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: formspree.io
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
      # background:
      #   image: 
      #     filename: contact.jpg
      #     filters:
      #       brightness: 1
      #     parallax: false
      #     position: center
      #     size: cover
      #     text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
