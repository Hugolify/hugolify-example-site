---
isPage: true
draft: false
title: Pushes
aliases: 
  - /blocks/push
description: Add some cards push with image and button in column or carousel.
icon: credit-card-2-front
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
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          alt: ''
  - type: pushes
    background: false
    heading:
      title: Carousel
      text: Nam eleifend nisl tellus, porta lacinia
    layout: carousel
    carousel:
      params:
        type: loop
        autoplay: true
        pagination: true
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
          src: /images/uploads/bernd-dittrich-tfwcwynxibw-unsplash.jpg
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
          src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          alt: ''
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column, align center
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
          src: /images/uploads/sebastien-jermer-ty9wjiijyj0-unsplash.jpg
          alt: ''
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column, align center, darken image
      text: Nam eleifend nisl tellus, porta lacinia
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
          src: /images/uploads/sebastien-jermer-ty9wjiijyj0-unsplash.jpg
          alt: ''
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column, align end
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: end
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: /images/uploads/robin-goutard-couufh79uzq-unsplash.jpg
          alt: ''
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column, in card
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        card: true
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: /images/uploads/lea-maruani-um-shmjr_no-unsplash.jpg
          alt: ''
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column, in card, align center
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        card: true
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: /images/uploads/sebastien-jermer-ty9wjiijyj0-unsplash.jpg
          alt: ''
  - type: pushes
    column: 1
    background: false
    heading:
      title: 1 column, in card, align end
      text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        card: true
        offset: end
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: /images/uploads/robin-goutard-couufh79uzq-unsplash.jpg
          alt: ''
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
          src: /images/uploads/bernd-dittrich-tfwcwynxibw-unsplash.jpg
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - cta:
          blank: false
        image:
          src: /images/uploads/balthazar-lelievre-zsozkbm7yy8-unsplash.jpg
          alt: ''
        offset: start
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.
  - type: pushes
    column: 2
    background: false
    heading:
      title: 2 columns, in card
      text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        image:
          src: /images/uploads/bernd-dittrich-tfwcwynxibw-unsplash.jpg
        offset: start
        card: true
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - cta:
          blank: false
        image:
          src: /images/uploads/balthazar-lelievre-zsozkbm7yy8-unsplash.jpg
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
    column: 2
    background: false
    heading:
      title: 2 columns without images and custom background color
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
      - cta:
          blank: false
          url: '#'
          text: Lorem ipsum
        offset: center
        background_color: '#56f6bf'
        color: '#000000'
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.
      - background_color: '#A90940'
        color: '#FFFFFF'
        offset: end
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
---
