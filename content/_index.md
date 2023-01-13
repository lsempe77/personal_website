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
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Econometrics
          description: 80%
          icon: chart-line
          icon_pack: fas
        - name: Psychometrics
          description: 80%
          icon: chart-bar
          icon_pack: fas
  # - block: experience
  #   content:
  #     title: Experience
  #     date_format: Jan 2006
  #     items:
  #       - title: Research Fellow
  #         company: Queen Margaret University
  #         location: Musselburgh, Scotland, UK
  #         date_start: '2022-02-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:
  #             * Quantitative evaluation of skin NTDs health system intervention in Liberia
  #             * Teaching quantitative methods modules
  #             * De
  #       - title: Research Fellow & Associate Tutor
  #         company: University of East Anglia
  #         company_url: ''
  #         company_logo: 
  #         location: Norwich, UK
  #         date_start: '2017-10-01'
  #         date_end: '2022-01-31'
  #         description: |2-
  #             Responsibilities include:
  #             * Taught in human geography, rural development, econometrics and education and development modules
  #             * Evaluation of interventions integrating social protection and health in older people in Brazil
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     # text: |-
  #     #   L
  #     # Contact (add or remove contact options as necessary)
  #     email: lsempe [at] qmu [dot] ac [dot] uk
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/lsempe'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     # form:
  #     #   provider: netlify
  #     #   formspree:
  #     #     id:
  #     #   netlify:
  #     #     # Enable CAPTCHA challenge to reduce spam?
  #     #     captcha: false
  #   design:
  #     columns: '2'
---
