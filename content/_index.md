---
title: Home
white_header: true
sections:
  - type: hero_section
    template: hero_section
    section_id: hero_section
    background_image: images/header.jpg
    background_image_opacity: 65
    content: >-
      # Real, beautiful plants right to your door

      Don't forget to add your Snipcart API key to the site's configuration to
      enable Cart actions.
    actions:
      - type: action
        template: action
        title: See all items
        url: /store
        style: primary
        arrow: true
  - type: featured_products_section
    template: featured_products_section
    title: Best sellers
    section_id: best_sellers_section
    light_title: true
    icon: true
    featured_products:
      - content/products/plant1.md
      - content/products/plant3.md
      - content/products/plant5.md
      - content/products/plant7.md
  - type: featured_categories_section
    template: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - content/category/bigplants.md
      - content/category/cactuses.md
  - type: testimonials_section
    template: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - text: >-
          I didn't know the Snipcart guys were into herbs as well! How beautiful
          is that Planty theme. I'm going to launch a killer JAMstack e-commerce
          store using this for sure.
        author:
          name: John Dope
          location: 'Colorado, USA'
      - text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
        author:
          name: Major Payne
          location: 'VA, USA'
  - type: promotion_section
    template: promotion_section
    section_id: promotion_section
    title: A new home interior for summer
    subtitle: from $149.99
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      type: action
      template: action
      title: Discover
      url: /store
      style: secondary
      arrow: true
layout: home
---
