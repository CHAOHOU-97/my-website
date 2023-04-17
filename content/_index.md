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
          description: Anticipated graduation--Jul 2023
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

  - block: accomplishments
    content:
      title: Tools
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhaSepDB--A database of phase separation related proteins
          certificate_url: ''
          date_end: ''
          date_start: '2022-06-07'
          description: PhaSepDB provides a collection of manually curated phase separation (PS) proteins and Membraneless organelles (MLOs) related proteins. As of June 2022, 1419 PS entries, 73 MLOs, 770 low throughput MLO related entries and 7303 high throughput MLO related entries were included.
          organization: ''
          organization_url: ''
          url: http://db.phasep.pro/
        
        - title: PhaSePred--Predictors of phase separating proteins
          certificate_url: ''
          date_end: ''
          date_start: '2021-08-31'
          description: PhaSePred is a centralized resource that provides self-assembling and partner-dependent phase-separating protein prediction and integrates scores from several PS-related predicting tools.
          organization: ''
          organization_url: ''
          url: http://predict.phasep.pro/
        
        - title: Degpred--Systematic Prediction of Degrons and Binding E3 ligases
          certificate_url: ''
          date_end: ''
          date_start: '2022-05-11'
          description: Degrons are short linear motifs, bound by E3 ubiquitin ligases to target proteins to be degraded by the ubiquitin-proteasome system. Deregulation of degron disrupts control of protein abundance and commonly contributes to diseases. Despite with important functions, only a limited number of degrons have been identified by experiment, the widely used motif matching prediction method is limited by few motifs and high false positive rate. Here, we developed a deep learning model Degpred to predict degrons directly from protein sequences. Leveraging abundant protein features provided by the BERT based model, Degpred predicts degrons beyond those from known motifs and greatly expands the degron landscape. Degpred outperformed motif-based methods in capturing well-known degron properties. Furthermore, we calculated motifs for 39 E3s using our collected E3-substrate interaction dataset and assigned predicted degrons to specific E3s. In summary, we presented an efficient and general tool to predict degrons and binding E3s, both collected and predicted datasets were integrated in this website.
          organization: ''
          organization_url: ''
          url: http://degron.phasep.pro/
        
        - title: MloDisDB--A manually curated DataBase of the relations between MembraneLess Organelles and DISeases
          certificate_url: ''
          date_end: ''
          date_start: '2020-09-14'
          description: Membraneless organelles (MLOs) play important roles in the temporal and spatial regulation of various biological processes, and emerging evidence supports that liquid-liquid phase separation (LLPS) is underlying the assembly of MLOs. Dysfunction of MLOs and LLPS are associated with various pathological processes. MloDisDB aims to gather MLOs and LLPS related diseases from the dispersed literature. Each entry was assigned with one of the three evidence levels based on original publication--Direct experiment, Indirect experiment, Clinical Investigation. The functional factors, changes of MLOs and changes of the factors were recorded, the components of MLOs and LLPS related predictions were integrated.
          organization: ''
          organization_url: ''
          url: http://mlodis.phasep.pro/
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
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

  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'

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
