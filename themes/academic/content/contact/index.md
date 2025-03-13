---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
  - block: contact
    content:
      title: 联系我们
      text: |-
        请通过以下详细信息联系我们：
      email: dingchunyu@szu.edu.cn
      phone: 185 1085 1750
      address:
        street: 南山区南海大道3688号
        city: 深圳市
        region: 广东省
        postcode: '518060'
        country: 中国
        country_code: Ch
      coordinates:
        latitude: '70.9592'
        longitude: '-116.4193'
      directions: 深圳大学沧海校区致知楼729
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
