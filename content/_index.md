---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: files/citations/CV_Kriwoluzky_03_24.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: working-papers
    content:
      title: Working Papers
      subtitle: ''
      text: |
        *(Section to be updated)*
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |
        **Current Teaching**

        Winter term: Monetary theory (B.Sc.)

        [Syllabus_monetary_theory_2024.pdf](https://github.com/user-attachments/files/16944807/Syllabus_monetary_theory_2024.pdf)

        Summer term: Advanced Macroeconomics Analysis II (Ph.D.)

        **Past Teaching**

        - Applied Macroeconometrics (B.Sc. / M.Sc.)
        - Bayesian DSGE Model Estimation (Ph.D.)
        - Dynamic Macroeconomics (M.Sc. / Ph.D.)
        - Interactions of Fiscal and Monetary Policy (M.Sc.)
        - Introduction into Quantitative Macroeconomics (B.Sc.)
        - Monetary Economics (B.Sc. / M.Sc.)
        - Monetary Macro and Beyond: Faust II (B.Sc.)
        - Topics in Macroeconomics (Ph.D.)
        - Frontier paper in Macroeconomics (Ph.D.)
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      email: akriwoluzky@diw.de
      address:
        street: Mohrenstr. 58
        city: Berlin
        postcode: '10117'
        country: Germany
        country_code: DE
      coordinates:
        latitude: '52.512269'
        longitude: '13.388648'
      contact_links: []
      autolink: true
    design:
      columns: '1'
---
