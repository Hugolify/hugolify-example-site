---
isPage: true
draft: false
title: Latest
description: Add latest items section (posts, projects, publications, casestudies…)
icon: gallery-vertical-end
hero:
  surtitle: Blocks
  title: Block latest
  text: Add latest items section (posts, projects, publications, casestudies…).
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/latest/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/informatilatestons.md
      blank: true
blocks:
  - type: latest
    count: 3
    show_more: true
    ui:
      align: center
    section: posts
    heading:
      title: Dernières actualités
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  - type: latest
    count: 6
    show_more: true
    ui:
      layout: list
      offset: center
      grid: large
    section: posts
    heading:
      title: Dernières actualités
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  - type: latest
    count: 3
    show_more: true
    ui:
      align: center
      theme: light
    section: publications
    heading:
      title: Dernières parutions
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  - type: latest
    count: 3
    show_more: true
    ui:
      align: center
      theme: dark
    section: realestates
    heading:
      title: Dernières annonces
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  - type: latest
    count: 4
    show_more: true
    ui:
      align: center
      theme: light
    section: persons
    heading:
      title: Dernières personnes
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  - type: latest
    count: 4
    show_more: true
    ui:
      layout: list
      offset: center
      grid: medium
      theme: light
    section: persons
    heading:
      title: Dernières personnes
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  - type: latest
    count: 3
    show_more: true
    ui:
      align: center
      theme: accent
    section: publications
    heading:
      title: Dernières parutions
      text: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
---
