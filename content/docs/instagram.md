---
isPage: true
draft: false
title: Instagram
description: Add instagram feed
icon: instagram
hero:
  surtitle: Blocks
  title: Block Instagram
  text: Add instagram feed (with Instafeed JS library).
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/instagram/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/instagram.md
      blank: true
    - text: Instafeed JS library
      url: https://instafeedjs.com
      blank: true
blocks:
  - type: alert
    state: danger
    text: A valid access_token from Instagram
  - type: instagram
    background: false
    heading:
      title: Instagram feed
    limit: 4
    ctas:
      - text: Discover on instagram
        url: https://www.instagram.com/sebouorhum
        blank: true
---
