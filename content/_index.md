---
date: "2022-10-24"
sections:

- block: about.biography
  content:
    title: Biography
    username: admin
  id: about

- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Working Paper
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects

- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Publications
  design:
    columns: "2"
    view: citation
  

- block: contact
  content:
    address:
      city: Chicago
      country: United States
      country_code: US
      postcode: "60637"
      region: IL
      street: 5807 South Woodlawn Avenue

    
    email: Jungeum.Kim@chicagobooth.edu
    title: Contact
    
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
