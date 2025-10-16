---
isPage: true
draft: false
title: Testimonials
description: Add some testimonials in grid or carousel
icon: blockquote-left
hero:
  surtitle: Blocks
  title: Block testimonials
  text: Add some testimonials in grid or carousel.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/testimonials/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/testimonials.md
      blank: true
    - text: SplideJS library
      url: https://splidejs.com/
      blank: true
blocks:
  - type: testimonials
    background: false
    heading:
      surtitle: Blandit dapibus erat.
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    layout: grid
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          text: Vivamus non mauris elit
  - type: testimonials
    background: false
    heading:
      surtitle: Blandit dapibus erat.
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    layout: carousel
    carousel:
      params:
        type: loop
        focus: center
        perPage: 5
        arrows: false
        autoplay: true
        gap: 1.5rem
        padding: 3rem
      responsive:
        - breakpoints: 640
          params:
            perPage: 1
        - breakpoints: 1024
          params:
            perPage: 2
        - breakpoints: 1280
          params:
            perPage: 3
        - breakpoints: 1440
          params:
            perPage: 4
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          text: Vivamus non mauris elit
---
