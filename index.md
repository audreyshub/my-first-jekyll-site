---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    title: 'Hi, I''m Audrey.'
    content: >-    
      I'm a web designer, developer, artist and tinkerer. I geek out over code as much as design. I build pretty rad websites and applications for entrepreneurs, artists and organizations that do good.
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
    subtitle:
    serviceslist:
      - title: Website Design
        content: >-
          I build modern JAMstack websites that are fast, secure and dynamic. Think websites/blogs that don't don't rely on WordPress, Wix or SquareSpace. All designs include web hosting, DNS setup, SSL certificates and SEO optimization.
      - title: Landing Page Design
        content: >-
          A landing page is your handshake, greeting, or smile. I design landing pages that captures the imagination and converts visitors.
      - title: Technical Integrations
        content: >-
          Need Aweber, Acuity, Calendly or some other integration but stuck on the how? No worries, sit back and let me handle the technical integrations for you.
  - section_id: testimonials
    component: testimonials_block.html
    type: testimonialsblock
    title: Testimonials
    subtitle:
    testimonialslist:
      - author: Lego Elvis
        avatar: images/legoman.jpg
        content: >-
          Audrey is so awesome to work with. I love her chilled, laid back vibe. Whatever you need she finds a way to get it done.
      - author: Lego Good Wizard
        avatar: images/legowizard.jpg
        content: >-
          Audrey's work is magic. She spins code into art and does so with love and heart. It's clear that she loves her craft. I endorse her magic.
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
