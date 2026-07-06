---
isPage: true
draft: false
title: Testimonials
description: Add some testimonials in grid or carousel
icon: message-square-quote
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
    heading:
      surtitle: Grid layout, Container grid
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    ui:
      layout: grid
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit

  - type: testimonials
    heading:
      surtitle: List layout, Light theme, Container grid
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    ui:
      theme: light
      layout: list
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
  
  - type: testimonials
    heading:
      surtitle: Carousel, Container grid
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    ui:
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
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit

  - type: testimonials
    heading:
      surtitle: Accent, List, Medium Grid, Offset Center
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    ui:
      theme: accent
      layout: list
      grid: medium
      offset: center
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: testimonials
    heading:
      surtitle: Dark, List, Small Grid, Offset Center
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    ui:
      theme: dark
      layout: list
      offset: center
      grid: small
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: testimonials
    heading:
      surtitle: Light, Grid, Full width
      title: Duis nisl odio, blandit vel quam eget
      text: Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi. Blandit dapibus erat.
    ui:
      theme: light
      layout: grid
      grid: full
    items:
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, rhoncus non diam vitae, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          text: Vivamus non mauris elit
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - quote: Nullam pretium eleifend lectus, at semper nulla egestas a. Praesent condimentum nibh erat, eget interdum nisi auctor eget. Vestibulum ex metus, euismod posuere mi.
        author:
          title: Aenean commodo
          image:
            src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
---
