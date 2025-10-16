---
isPage: true
draft: false
title: Logos
description: Add some logos in grid or carousel.
icon: grip-horizontal
hero:
  surtitle: Blocks
  title: Block logos
  text: Add some logos in grid or carousel.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/logos/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/logos.md
      blank: true
    - text: SplideJS library
      url: https://splidejs.com/
      blank: true
blocks:
  - type: logos
    column: 6
    background: false
    heading:
      title: Grid (6 columns)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
  - type: logos
    column: 8
    background: true
    heading:
      title: Grid (8 columns)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
  - type: logos
    layout: carousel
    background: false
    carousel:
      params:
        perMove: 1
        perPage: 8
        interval: 2000
        autoplay: true
        type: loop
        arrows: true
        gap: 1.5rem
      responsive:
        - breakpoints: 640
          params:
            perPage: 3
        - breakpoints: 768
          params:
            perPage: 4
    heading:
      title: Carousel (8 columns)
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
      - src: /images/uploads/instagram.svg
---
