---
# Leave the homepage title empty to use the site title
title: Chao Hou's website
date: 2023-4-15
type: landing

sections:

  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:

  - block: experience
    id: experience
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
        - title: MD student
          company: Peking University
          location: Beijing
          date_start: '2020-09-01'
          date_end: ''
          description: |2-
            Advisor: prof. Tingting Li
            Anticipated graduation: Jul 2023
        - title: Bachelor of Medicine
          company: Peking University
          location: Beijing
          date_start: '2015-09-01'
          date_end: '2020-06-30'
        - title: Bachelor of Economics (double degree)
          company: Peking University
          location: Beijing
          date_start: '2016-09-01'
          date_end: '2020-06-30'
    design:
      columns: '2'

  - block: collection
    id: Publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation

  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas

  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: hou_chao@pku.edu.cn
      phone: +86 15810702076
      address:
        street: No.38, Xueyuan Road, Haidian District
        city: Beijing
        postcode: '100191'
        country: China
    design:
      columns: '2'
---
