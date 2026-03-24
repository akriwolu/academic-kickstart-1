---
# Leave the homepage blank - sections handle everything
title: ''
date: 2024-01-01
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      title: Biography
      username: admin
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
      filters:
        folders:
          - publication
        publication_types:
          - 'article-journal'
    design:
      columns: '2'
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
