---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

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
        - title: Master's thesis
          company: ICMUV institute
          company_url: ''
          company_logo: icmuv
          location: Valencia, Spain
          date_start: '2023-03-20'
          date_end: '2023-08-20'
          description: Modeling ultra-high accelerating gradients in carbon-based nanostructures through an effective plasma-density approach.
        - title: Practical Researches
          company: CERN institute
          company_url: ''
          company_logo: cern-vector-logo
          location: Geneva, Switzerland
          date_start: '2023-02-04'
          date_end: '2023-02-28'
          description: |2-
              Responsibilities include:

              * RF measurement methods 
              * Beam Diagnostic of CLEAR beamline
        - title: Practical Researches
          company: SOLEIL institute
          company_url: ''
          company_logo: logo_0
          location: Saint-Aubin, France
          date_start: '2022-10-01'
          date_end: '2023-01-31'
          description: |2-
              Responsibilities include:

              * Crystallography by Low Energy Electron Diffraction
              * Longitudinal Beam measurement of SOLEIL synchrotron
        - title: Practical Researches
          company: INFN institute
          company_url: ''
          company_logo: infn
          location: Frascati, Italy
          date_start: '2022-03-01'
          date_end: '2022-07-30'
          description: |2-
              Responsibilities include:

              * Plasma Diagnostics for Plasma based Accelerators
              * Image denoising by Artificial Inteligent
        - title: Teaching assistant
          company: Urmia University
          company_url: ''
          company_logo: urmia
          location: Urmia, Iran
          date_start: '2019-08-01'
          date_end: '2019-12-28'
          description: |2-
              Responsibilities include:

              * Solving problems of "Mathematical Methods for Physics "
              * Performed all duties as a T.A. (for a class size of 43)
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Achievements'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.se.manchester.ac.uk/phds-science-engineering/funding/deans-doctoral-scholarship/
          date_end: ''
          date_start: '2023-09-05'
          description: ''
          organization: Manchester University
          organization_url: https://www.se.manchester.ac.uk/phds-science-engineering/funding/deans-doctoral-scholarship/
          title: Deans Doctoral Scholarship
          url: ''
        - certificate_url: hhttps://www.master-lascala.eu/
          date_end: '2023-09-01'
          date_start: '2021-09-01'
          description: ''
          organization: Erasmus+
          organization_url: https://erasmus-plus.ec.europa.eu/
          title: Erasmus Mundus Joint Masters scholarships for LASCALA program
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
        - name: Compact particle accelerators
          tag: '*'
        - name: THz acceleration
          tag: THz
        - name: NACANA
          tag: NACANA
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: collection
    id: publication
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: ''
      # Contact (add or remove contact options as necessary)
      email: aras.aminim@gmail.com
      # phone: 888 888 88 88
      address:
        street: Still looking for a place
        city: ''
        region: ''
        postcode: ''
        country: ''
        country_code: ''
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    design:
      columns: '2'
---
