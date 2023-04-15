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
          description: 40%
          icon: r-project
          icon_pack: fab
        - name: Bash/Python
          description: 40%
          icon: terminal
          icon_pack: fas
        - name: Microbiology
          description: 20%
          icon: bacterium
          icon_pack: fas
  - block: Experience
    content:
      title: Research Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD Student
          company: APC Microbiome Ireland
          company_url: ''
          company_logo: org-gc
          location: Cork, Ireland
          date_start: '2018-01-10'
          date_end: ''
          description: |2-
              Project Title: Antimicrobial Sensitisation through Quorum Quenching
              Responsibilities include:
              * Planning and running experiments
              * Bioinformatic processing and analysis of NGS datasets
              * Dissemination of research
              * Liaising with university administration e.g. IP, MTAs, Procurement
        - title: BSc (Hons) Nutrition and Health Science 
          company: Munster Technological University
          company_url: ''
          company_logo: org-x
          location: Cork, Ireland
          date_start: '2014-01-09'
          date_end: ''
          description: |2-
              Dissertation Title: Microbial Communities and Man: Predictions for Biofilm-Associated Effects
              Erasmus+ Traineeship: lab of Prof. Rosanna Tofalo at the Università degli Studi di Teramo
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url:
          date_end: ''
          date_start: '2022-07-30'
          description: ''
          organization: Smith College
          organization_url:
          title: New England Biolabs Molecular Biology Workshop
          url:
        - certificate_url: https://www.futurelearn.com/certificates/e3ul19t
          date_end: ''
          date_start: ''2019-02-01'
          description: 
          organization: Wellcome Connecting Science Courses and Conferences
          organization_url: https://www.wellcomeconnectingscience.org/
          title: Bacterial Genomes: Accessing and Analysing Microbial Genome Data
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url:
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Get in contact with me through the form below, or through linked social media.
      # Contact (add or remove contact options as necessary)
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/forestsomewhere'
        - icon: video
          icon_pack: fas
          name: Zoom
          link: 'https://us05web.zoom.us/j/7682670615?pwd=OEFDVW41eWdGa0JhbjBHUWZoSlduZz09'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
