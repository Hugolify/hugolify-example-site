---
isPage: true
draft: false
title: Form
description: Add form
image:
  src: /images/uploads/input-cursor-text.svg
hero:
  surtitle: Blocks
  title: Block form
  text: Add form (connect with netlify), input, textarea and select available. 4 widths available.
  image:
    src: /images/uploads/input-cursor-text.svg
  cta:
    blank: false
    text: See examples
    url: "#main"
  cta_second:
    text: Documentation
    url: https://github.com/hugolify/hugolify-template/wiki/block-form
    blank: true
  image:
    src: /images/uploads/input-cursor-text.svg
blocks:
  - type: form
    background: false
    name: contact
    submit: Send message
    offset: center
    grid: small
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true
  - type: form
    background: true
    name: contact
    submit: Send message
    offset: center
    grid: medium
    items:
      - type: text
        name: firstname
        label: Firstname
        placeholder: John
        autocomplete: given-name
        required: true
      - type: text
        name: lastname
        label: Lastname
        placeholder: Doe
        autocomplete: familly-name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        full: true
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true
  - type: form
    background: false
    title: Lorem ipsum
    text: Semper urna enim, viverra faucibus tellus bibendum sed
    name: contact
    submit: Send message
    offset: center
    grid: large
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        required: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        required: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true
---
