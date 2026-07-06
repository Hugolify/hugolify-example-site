---
isPage: true
draft: false
title: Informations
description: Add some cards informations in column. Icon, images and button are available
icon: ellipsis
hero:
  surtitle: Blocks
  title: Block informations
  text: Add some cards informations in column. Icon, images and button are available.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/informations/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/informations.md
      blank: true
blocks:
  - type: informations
    column: 4
    background: false
    heading:
      title: 4 columns with icons
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        icon: cloud-rain
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        icon: cloud-sun
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        icon: cloudy
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        icon: sun
  - type: informations
    column: 3
    background: false
    heading:
      title: 3 columns with icons
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        icon: cloud-rain
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        icon: cloud-sun
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        icon: cloudy
  - type: informations
    column: 4
    background: true
    heading:
      title: 4 columns with icons and background
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        icon: cloud-rain
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        icon: cloud-sun
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        icon: cloudy
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
  - type: informations
    column: 4
    background: false
    heading:
      title: 4 columns with images
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: informations
    ui:
      column: 4
      offset: center
      grid: large
      theme: light
      ratio: 1
    heading:
      surtitle: Ratio 1, Grid large, Offset center, theme light
      title: 4 columns with images
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: informations
    ui:
      column: 4
      offset: center
      grid: medium
      theme: accent
      ratio: 1.5
    heading:
      surtitle: Theme accent, Grid medium, Offset center, ratio 1.5
      title: 4 columns with images 
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: informations
    ui:
      column: 4
      grid: full
      theme: dark
    heading:
      surtitle: Grid full, theme dark
      title: 4 columns with images in dark theme
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
  - type: informations
    column: 4
    background: false
    heading:
      title: 4 columns with logos
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
  - type: informations
    column: 4
    background: false
    heading:
      title: 4 columns mixed
      text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
    items:
      - title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782294171/anders-jilden-Sc5RKXLBjGg-unsplash_rafux6.jpg
      - text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc
        title: Faucibus maximus nunc
        image:
          src: https://res.cloudinary.com/uncinq/image/upload/v1782295060/logo-black_e1lfvo.svg
          isLogo: true
      - title: Aliquam velit magna
        text: Donec ut eros sit amet ipsum pulvinar sagittis.
        icon: cloudy
      - title: Curabitur non ante purus
        text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
        cta:
          blank: false
          url: '#'
          text: Lorem ipsum
---
