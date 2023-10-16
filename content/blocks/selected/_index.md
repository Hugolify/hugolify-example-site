---
isPage: true
draft: false
title: Selected
description: Add selected items section (posts, projects, publications, casestudies…)
image:
  src: /images/uploads/check-all.svg
hero:
  surtitle: Blocks
  title: Selected sections
  text: Add selected items section (posts, projects, publications, casestudies…)
  image:
    src: /images/uploads/check-all.svg
  cta:
    text: See examples
    blank: false
    url: "#main"
  cta_second:
    blank: true
    text: Documentation
    url: https://github.com/hugolify/hugolify-template/wiki/block-selected
blocks:
  - type: selected-projects
    background: false
    section: projects
    items:
      - 2022/aliquet-facilisis
      - 2022/fusce-ut-sapien-massa
      - 2022/proin-massa-enim-lobortis-et-vehicula-non
    heading:
      title: 3 selected projects
    show_more: true
  - type: selected-casestudies
    section: casestudies
    show_more: true
    background: true
    items:
      - 2022/maecenas-semper-urna-enim
      - 2022/viverra-nisi-at-sagittis
    heading:
      title: 2 selected case studies
  - type: selected-posts
    section: posts
    show_more: true
    background: false
    items:
      - 2022/09/2022-09-05-aliquam-a-scelerisque-dolor-proin-maximus-eros-et-pellentesque
      - 2022/10/2022-10-04-aliquam-a-scelerisque-dolor-proin-maximus-eros-et-pellentesque-rhoncus
      - 2022/10/2022-10-04-lorem-ipsum
      - 2022/10/2022-10-03-nullam-lacinia-ligula
    heading:
      title: 4 selected posts
      text: Duis nisl odio, blandit vel quam eget
  - type: selected-publications
    section: publications
    show_more: false
    background: true
    heading:
      surtitle: Lorem ipsum
      title: 1 selected publication
    items:
      - 2022/11/2022-11-21-maecenas-ut-sodales-arcu
---
