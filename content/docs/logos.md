---
isPage: true
draft: false
title: Logos
description: Add some logos in column or carousel.
icon: grip-horizontal
hero:
  surtitle: Blocks
  title: Block logos
  text: Add some logos in column or carousel.
  cta:
    text: See examples
    url: '#main'
    blank: false
  cta_second:
    blank: true
    text: Documentation
    url: https://www.hugolify.io/docs/blocks/logos/
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
      perMove: 1
      perPage: 8
      interval: 1000
      autoplay: true
      type: loop
      arrows: true
      gap: 1.5rem
      responsive:
        - breakpoint: 640
          carousel:
            perPage: 3
        - breakpoint: 768
          carousel:
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