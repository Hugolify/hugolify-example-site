---
isPage: true
draft: false
title: Selected
description: Add selected items section (posts, projects, publications, casestudies…)
icon: check-check
hero:
  surtitle: Blocks
  title: Selected sections
  text: Add selected items section (posts, projects, publications, casestudies…).
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/selected/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/selected.md
      blank: true
blocks:
  
  - type: selected-posts
    section: posts
    show_more: true
    ui:
      align: center
    items:
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
    heading:
      surtitle: Layout grid, Align center
      title: 3 selected posts
      text: Duis nisl odio, blandit vel quam eget
  
  - type: selected-posts
    section: posts
    ui:
      layout: list
    show_more: true
    items:
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
    heading:
      surtitle: Layout list, Grid container
      title: 3 selected posts
      text: Duis nisl odio, blandit vel quam eget
  
  - type: selected-publications
    section: publications
    show_more: false
    heading:
      surtitle: Layout grid
      title: 1 selected publication
      text: Duis nisl odio, blandit vel quam eget
    items:
      - 2023/01/2023-01-12-sed-metus-quam-imperdiet-ut-enim-vitae
  
  # THEME
  - type: selected-posts
    section: posts
    ui:
      theme: accent
      layout: list
      grid: medium
      offset: center
    show_more: true
    heading:
      surtitle: Layout list, Offset center, Theme accent, Grid medium
      title: 3 selected posts
      text: Duis nisl odio, blandit vel quam eget
    items:
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
  - type: selected-posts
    section: posts
    ui:
      theme: dark
      layout: list
      grid: small
      offset: center
    show_more: true
    heading:
      surtitle: List layout, Offset center, Dark theme, Small grid
      title: 3 selected posts
      text: Duis nisl odio, blandit vel quam eget
    items:
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
  - type: selected-posts
    section: posts
    ui:
      theme: light
      layout: grid
      grid: small
      offset: center
    show_more: true
    heading:
      surtitle: Grid layout, Offset center, Light theme, Small grid
      title: 3 selected posts
      text: Duis nisl odio, blandit vel quam eget
    items:
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
  - type: selected-posts
    section: posts
    ui:
      layout: grid
      grid: full
    show_more: false
    heading:
      surtitle: Grid layout, No Offset, Light theme, Small grid
      title: 6 selected posts
      text: Duis nisl odio, blandit vel quam eget
    items:
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
---
