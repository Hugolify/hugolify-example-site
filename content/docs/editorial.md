---
isPage: true
draft: false
title: Editorial
description: Add section with content (texts and buttons) and media
icon: id-card
hero:
  surtitle: Blocks
  title: Block editorial
  text: Add section with content (texts and buttons) and media.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/editorial/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/editorial.md
      blank: true
blocks:

  # Classic
  - type: editorial
    direction: ltr
    ctas:
      - blank: false
        text: Button
        url: "#"
    background: false
    surtitle: Surtitle
    title: Text on the left, image on the right
    text: >-
      Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus
      nunc.


      Donec ut eros sit amet ipsum pulvinar sagittis.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: editorial
    direction: rtl
    ctas:
      - blank: false
        text: Button
        url: "#"
    background: false
    surtitle: Surtitle
    title: Text on the right, image on the left
    text: >-
      Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus
      nunc.


      Donec ut eros sit amet ipsum pulvinar sagittis.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  
  # Grid
  - type: editorial
    direction: ltr
    grid: small
    offset: center
    background: false
    surtitle: Surtitle
    title: Small editorial
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: editorial
    direction: ltr
    grid: medium
    offset: center
    background: true
    surtitle: Surtitle
    title: Medium editorial
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: editorial
    direction: ltr
    grid: large
    offset: center
    background: false
    surtitle: Surtitle
    title: Large editorial
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: editorial
    direction: ltr
    grid: container
    background: true
    surtitle: Surtitle
    title: Container editorial
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  - type: editorial
    direction: ltr
    grid: full
    offset: center
    background: false
    surtitle: Surtitle
    title: Full editorial
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: editorial
    direction: rtl
    grid: full
    offset: center
    background: false
    surtitle: Surtitle
    title: Full editorial
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg

  # Theme
  - type: editorial
    direction: rtl
    grid: container
    theme: accent
    surtitle: Surtitle
    title: Container editorial (theme accent)
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
    ctas:
      - blank: false
        text: Button
        url: "#"
  - type: editorial
    direction: rtl
    grid: container
    theme: dark
    surtitle: Surtitle
    title: Container editorial (theme dark)
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
    ctas:
      - blank: false
        text: Button
        url: "#"
  - type: editorial
    direction: rtl
    grid: container
    theme: light
    surtitle: Surtitle
    title: Container editorial (theme light)
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
    ctas:
      - blank: false
        text: Button
        url: "#"
  - type: editorial
    direction: rtl
    grid: container
    theme: highlight
    surtitle: Surtitle
    title: Container editorial (theme highlight)
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
    ctas:
      - blank: false
        text: Button
        url: "#"
  - type: editorial
    direction: rtl
    grid: container
    theme: black
    surtitle: Surtitle
    title: Container editorial (theme black)
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
    ctas:
      - blank: false
        text: Button
        url: "#"
  - type: editorial
    direction: rtl
    grid: container
    theme: white
    surtitle: Surtitle
    title: Container editorial (theme white)
    text: Phasellus **tellus** purus, pellentesque eu velit vel, faucibus maximus nunc.
    image:
      src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
    ctas:
      - blank: false
        text: Button
        url: "#"
---
