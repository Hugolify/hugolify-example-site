---
isPage: true
draft: false
title: Pushes
aliases: 
  - /blocks/push
description: Add some cards push with image and button in column or carousel.
icon: captions
hero:
  surtitle: Blocks
  title: Block pushes
  text: Add some cards push with image and button in column or carousel.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/pushes/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/pushes.md
      blank: true
    - text: SplideJS library
      url: https://splidejs.com/
      blank: true
blocks:
  - type: alert
    state: warning
    text: Be careful to always have sufficient contrast between the text and the image for it to be readable.
  
  # CARD
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column with card
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column with card (align end)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: end
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column with card (align center)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  # CARD DARKEN
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column with card and media darken
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - darken: true
        card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column with card (align end) and media darken
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        darken: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: end
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column with card (align center) and media darken
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        darken: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  # DARKEN
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column and media darken
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: false
        darken: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column (align end) and media darken
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: false
        darken: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: end
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column (align center) and media darken
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: false
        darken: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  # CAROUSEL
  - type: pushes
    heading:
      title: Carousel
      text: Nam eleifend nisl tellus, porta lacinia
    ui:
      layout: carousel
    carousel:
      params:
        autoplay: true
        gap: 3rem
        arrow: true
        pagination: true
        perPage: 2
      responsive:
        - breakpoints: 640
          params:
            arrows: false
            gap: 0
            perPage: 1
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        darken: true
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        card: true
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.

  - type: pushes
    heading:
      title: Carousel
      text: Nam eleifend nisl tellus, porta lacinia
    ui:
      layout: carousel
    carousel:
      params:
        arrow: true
        pagination: true
      responsive:
        - breakpoints: 640
          params:
            arrows: false
            gap: 0
            perPage: 1
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        darken: true
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        card: true
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.

  - type: pushes
    heading:
      title: Carousel
      text: Nam eleifend nisl tellus, porta lacinia
    ui:
      layout: carousel
      grid: medium
      offset: center
      theme: light
    carousel:
      params:
        arrow: true
        pagination: true
      responsive:
        - breakpoints: 640
          params:
            arrows: false
            gap: 0
            perPage: 1
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        darken: true
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        card: true
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
  
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column (align center)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  # 2 COLUMNS
  - type: pushes
    column: 2
    background: false
    heading:
      title: 2 columns
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        darken: true
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - cta:
          blank: false
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
        offset: start
        darken: true
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.
  
  - type: pushes
    column: 2
    background: false
    heading:
      title: 2 columns with card
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        offset: start
        card: true
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - cta:
          blank: false
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
          alt: ''
        offset: start
        card: true
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.
  
  - type: pushes
    column: 2
    background: false
    heading:
      title: 2 columns without images
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - cta:
          blank: false
        offset: center
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.
  
  - type: pushes
    background: true
    heading:
      title: 1 column with legacy background
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
  
  # 2 columns and custom colors
  - type: pushes
    column: 2
    background: false
    heading:
      title: 2 columns without images and custom colors
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        background_color: '#A90940'
        color: '#FFFFFF'
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - cta:
          blank: false
        offset: center
        background_color: '#56f6bf'
        color: '#000000'
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.

  # THEME
  - type: pushes
    column: 1
    ui:
      theme: accent
    heading:
      title: 1 column with card (theme accent)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: pushes
    column: 1
    ui:
      theme: dark
    heading:
      title: 1 column with card (theme dark)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: pushes
    column: 1
    ui:
      theme: light
    heading:
      title: 1 column with card (theme light)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  # CARD
  - type: pushes
    column: 1
    ui:
      grid: full
    heading:
      title: 1 column with card (full)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: pushes
    column: 1
    ui:
      grid: medium
      offset: center
    heading:
      title: 1 column with card (medium, offset center)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - card: true
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
---
