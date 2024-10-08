---
isPage: true
draft: false
title: Selected
description: Add selected items section (posts, projects, publications, casestudies…)
icon: check-all
hero:
  surtitle: Blocks
  title: Selected sections
  text: Add selected items section (posts, projects, publications, casestudies…)
  cta:
    text: See examples
    blank: false
    url: '#main'
  cta_second:
    blank: true
    text: Documentation
    url: https://www.hugolify.io/docs/blocks/selected/
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
  - type: selected-projects
    background: false
    layout: list
    section: projects
    items:
      - 2022/aliquet-facilisis
      - 2022/fusce-ut-sapien-massa
      - 2022/proin-massa-enim-lobortis-et-vehicula-non
    heading:
      title: 3 selected projects in list
      text:
        Curabitur nec ipsum sit amet tellus *sagittis* blandit. Nulla massa nibh,
        cursus a arcu et, viverra sodales ipsum. Duis id congue metus. In commodo
        lectus ut **ligula elementum**, ac commodo tortor rhoncus. Vivamus
        sollicitudin eu magna sed interdum. Mauris lobortis pulvinar lectus at
        semper. Proin ac nunc urna. In placerat lorem ut tempus interdum. Maecenas
        nec iaculis lorem.
    show_more: false
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
  - type: selected-posts
    section: posts
    layout: list
    show_more: true
    background: false
    items:
      - 2022/09/2022-09-05-aliquam-a-scelerisque-dolor-proin-maximus-eros-et-pellentesque
      - 2022/10/2022-10-04-aliquam-a-scelerisque-dolor-proin-maximus-eros-et-pellentesque-rhoncus
      - 2022/10/2022-10-04-lorem-ipsum
      - 2022/10/2022-10-03-nullam-lacinia-ligula
    heading:
      title: 4 selected posts in list
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
