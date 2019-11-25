---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    title: 'Hi, I''m Audrey.'
    content: >-    
      I'm a web designer, developer, artist and tinkerer. I geek out over code as much as good design. I deploy pretty rad websites and applications for entrepreneurs and artists.
  - section_id: latest-projects
    component: portfolio_block.html
    type: portfolioblock
    layout_style: mosaic
    title: Recent Work
    subtitle: Take a look at the projects I've built below
    num_projects_displayed: 6
    view_all_text: View All
    view_all_url: portfolio/index.html
  - section_id: services
    component: services_block.html
    type: servicesblock
    title: What I Do
    subtitle: An optional subtitle of the section
    serviceslist:
      - title: Website Design
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla, fringilla tortor at, pulvinar orci.
      - title: Landing Pages Design
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - title: Technical Integrations
        content: >-
          Aliquam pulvinar, orci ac scelerisque tempus, felis leo sagittis
          justo, sit amet condimentum lorem nibh vel quam. Duis consectetur
          lorem ipsum, non efficitur urna viverra et.
  - section_id: testimonials
    component: testimonials_block.html
    type: testimonialsblock
    title: Testimonials
    subtitle: My clients love me
    testimonialslist:
      - author: John Doe
        avatar: images/john_doe.jpg
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - author: Jane Roe
        avatar: images/jane_roe.jpg
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam. Integer commodo sem at
          dui sollicitudin, vel posuere justo laoreet.
  - section_id: latest-posts
    component: posts_block.html
    type: postsblock
    title: Latest from the Blog
    subtitle: My thoughts on design, code, life
    num_posts_displayed: 2
    actions:
      - label: View Blog
        url: blog/index.html
  - section_id: contact
    component: contact_block.html
    type: contactblock
    title: Contact Me
    subtitle: Hi there! Thank you so much for your interest in working together. Please tell me a bit about your project here. Looking forward to hearing from you!
menus:
  main:
    weight: 1
    title: Home
layout: home
---
