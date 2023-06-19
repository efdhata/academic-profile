---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: python
          description: time-series data, machine learning, visualization
          icon: python
          icon_pack: fab
        - name: Resource assessment
          description: Solar irradiance
          icon: cloud-sun
          icon_pack: fas
        - name: Renewable Energy
          description: feasibility study
          icon: solar-panel
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate student researcher
          company: Korea Institute of Energy Research
          company_url: 'https://www.kier.re.kr/eng/'
          company_logo: logo_kier_3
          location: Daejeon, South Korea
          date_start: '2021-03-01'
          date_end: ''
          description: |2-
              Current research topic includes:

              * Correction of satellite-derived solar irradiance data using statistical methods
              * Feasibility study of photovoltaic and concentrator solar power
        - title: Laboratory assistant
          company: Institut Teknologi Bandung
          company_url: 'https://tf.itb.ac.id/en/'
          company_logo: logo_itb
          location: Bandung, Indonesia
          date_start: '2020-01-01'
          date_end: '2020-05-31'
          description: Supervised and assessed students' performance in carrying out room acoustic measurements.
    design:
      columns: '2'
  - block: collection
    content:
      title: Publications
      id: publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact 
  
---
