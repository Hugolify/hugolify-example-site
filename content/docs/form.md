---
isPage: true
draft: false
title: Form
description: Add form
icon: input-cursor-text
hero:
  surtitle: Blocks
  title: Block form
  text: Add form (connect with netlify), input, textarea and select available. 4 widths available.
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/form/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/form.md
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
    heading:
      surtitle: velit quis consequat
      title: Lorem ipsum dolor sit amet.
      text: Suspendisse sollicitudin dignissim velit quis consequat
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
    name: contact
    submit: Send message
    offset: center
    grid: large
    heading:
      title: Lorem ipsum dolor sit amet.
      text: Semper urna enim, viverra faucibus tellus bibendum sed
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
      - type: number
        name: number
        label: Number
        required: false
      - type: url
        name: url
        label: URL
        required: false
      - type: date
        name: date
        label: Date
        required: false
      - type: time
        name: time
        label: Time
        required: false
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        required: false
      - type: checkbox
        name: checkbox
        label: Checkbox - Semper urna enim
        required: false
      - type: switch
        name: checkbox
        label: Switch
        required: false
      - type: radio
        name: radio
        label: Radio - Viverra faucibus tellus bibendum sed
        required: false
      - type: range
        name: range
        label: Range
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        required: true
      - type: text
        name: readonly
        label: Read only
        value: Read only
        readonly: true
  - type: form
    background: false
    name: contact
    submit: Send message
    offset: center
    grid: large
    heading:
      title: Lorem ipsum dolor sit amet.
      text: Semper urna enim, viverra faucibus tellus bibendum sed
    items:
      - type: text
        name: name
        label: Name
        placeholder: John Doe
        autocomplete: name
        disabled: true
      - type: email
        name: email
        label: Email
        placeholder: john.doe@domain.com
        autocomplete: email
        disabled: true
      - type: tel
        name: telephone
        label: Telephone
        placeholder: +33 6 12 34 56 78
        autocomplete: tel
        disabled: true
      - type: number
        name: number
        label: Number
        disabled: true
      - type: url
        name: url
        label: URL
        disabled: true
      - type: date
        name: date
        label: Date
        disabled: true
      - type: time
        name: time
        label: Time
        disabled: true
      - type: select
        name: subject
        label: Subject
        options:
          - title: Lorem
          - title: Ipsum
        disabled: true
      - type: checkbox
        name: checkbox
        label: Checkbox - Semper urna enim
        disabled: true
      - type: switch
        name: checkbox
        label: Switch
        disabled: true
      - type: radio
        name: radio
        label: Radio - Viverra faucibus tellus bibendum sed
        disabled: true
      - type: range
        name: range
        label: Range
        disabled: true
      - type: textarea
        full: true
        name: comment
        label: Message
        placeholder: Your message…
        disabled: true
---
