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
        - name: Conventional Microbiology
          description: 20%
          icon: bacterium
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
        - title: PhD Student
          company: APC Microbiome Ireland
          company_url: ''
          company_logo: 
          location: Cork, Ireland
          date_start: '2018-09-30'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Planning and running experiments
              * Bioinformatic processing and analysis of NGS datasets
              * Dissemination of research
           
        - title: Laboratory Demonstrator
          company: Munster Technological University
          company_url: ''
          company_logo: 
          location: Cork, Ireland
          date_start: '2020-09-01'
          date_end: '2021-06-30'
          description: Led practical laboratory sessions for undergraduate students.
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
          url: ''
        - certificate_url: https://www.futurelearn.com/certificates/e3ul19t
          date_end: '2019-02-01'
          date_start: ''
          description: ''
          organization: Wellcome Connecting Science Courses and Conferences
          organization_url: https://www.wellcomeconnectingscience.org/
          title: 'Bacterial Genomes: Accessing and Analysing Microbial Genome Data'
          url: 
        - certificate_url: https://www.futurelearn.com/certificates/6iisgjm
          date_end: '2019-02-01'
          date_start: ''
          description: ''
          organization: Wellcome Connecting Science Courses and Conferences
          organization_url: https://www.wellcomeconnectingscience.org/
          title: 'Bacterial Genomes: From DNA to Protein Function using Bioinformatics'
          url: ''
        - certificate_url: 
          date_end: '2018-12-23'
          date_start: ''
          description: 'Credential ID 2622520722'
          organization: Epigeum
          organization_url: 
          title: 'Research Integrity - Natural and Physical Sciences'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
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
        Email is good, or feel free to drop a line via Twitter/Github.
      # Contact (add or remove contact options as necessary)
      address:
        city: Cork
        region:
        postcode: ''
        country: Ireland
        country_code: 
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/forestsomewhere'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---


