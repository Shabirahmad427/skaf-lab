---
# Leave the homepage title empty to use the site title
title:
date: 2024-01-01
type: landing

sections:
  - block: hero
    content:
      title: Skaf Lab
      text: |
        **Computational Biophysical Chemistry**  
        Institute of Chemistry · University of Campinas (Unicamp) · Brazil
      cta:
        label: Meet the Team
        url: people
      cta_alt:
        label: Our Research
        url: '#projects'
    design:
      background:
        color: '#7A2E2E'
        text_color_light: true

  - block: markdown
    id: about
    content:
      title: About the Group
      text: |
        We are a computational chemistry research group at the **Institute of Chemistry (IQ)**,
        University of Campinas (Unicamp), Brazil. Our work focuses on understanding molecular-level
        phenomena in biological and chemical systems through **molecular dynamics simulations**
        and theoretical methods.

        Our research spans enzymes, proteins, nanomaterials, cellulose, and liquids — with the
        goal of connecting molecular structure to macroscopic properties and biological function.

        We are part of the [CEPID/FAPESP Center for Computing in Engineering and Sciences](https://bv.fapesp.br/en/pesquisador/2269/munir-salomao-skaf).

        {{% affiliations %}}
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Research Lines
      subtitle: ''
      text: ''
      filters:
        folders:
          - project
    design:
      columns: '2'
      view: card

  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        featured_only: false
      count: 5
    design:
      columns: '2'
      view: citation

  - block: collection
    content:
      title: Software & Tools
      filters:
        folders:
          - software
    design:
      columns: '2'
      view: card

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      email: skaf@iqm.unicamp.br
      address:
        street: Instituto de Química, Rua Josué de Castro, s/n
        city: Campinas
        region: SP
        postcode: '13083-861'
        country: Brazil
        country_code: BR
      coordinates:
        latitude: '-22.8185'
        longitude: '-47.0664'
      directions: Instituto de Química (IQ) - Unicamp Campus
      office_hours:
        - 'Monday–Friday, 09:00–18:00'
      contact_links:
        - icon: graduation-cap
          icon_pack: fas
          name: Google Scholar
          link: 'https://scholar.google.com/citations?user=yyRa2dcAAAAJ'
        - icon: github
          icon_pack: fab
          name: GitHub (cepid-cces)
          link: 'https://github.com/cepid-cces'
    design:
      columns: '2'
---
