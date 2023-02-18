---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: about.avatar
    id: about
    text:
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: 
  - block: markdown
    id: education
    content:
      title: Education
      items:
        - title: PhD Student - Human-Computer Interaction
          company: University Wuerzburg
          company_url: ''
          company_logo: uniwue
          location: Wuerzburg
          date_start: '2020-04-01'
          date_end: ''
          description: 
        - title: Master of Science - Human-Computer Interaction
          company: University Wuerzburg
          company_url: ''
          company_logo: uniwue
          location: Wuerzburg
          date_start: '2017-10-01'
          date_end: '2020-11-01'
          description: Title Master Thesis
        - title: Bachelor of Science - Computer Science (KMI)
          company: University of Applied Science (h_da)
          company_url: ''
          company_logo: hda
          location: Darmstadt
          date_start: '2014-10-01'
          date_end: '2017-09-01'
          description: Title Bachelor Thesis
        - title: Abitur
          company: Karl Theodor von Dalberg Gymnasium
          company_url: ''
          company_logo: dalberg
          location: Aschaffenburg
          date_start: '2005-09-01'
          date_end: '2014-06-27'
          description: 
    design:
      columns: '2'
  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: (Social) VR Development
          description: Unity, C#, Photon
          icon: unity
          icon_pack: fab
        - name: Statistical Analysis
          description: R, SPSS, JASP
          icon: chart-line
          icon_pack: fas
        - name: MS Office
          description: 
          icon: microsoft
          icon_pack: fab
        - name: Design Tools
          description: Affinity Designer, Figma
          icon: figma
          icon_pack: fab
        - name: To Do
          description: -
          icon: edit
          icon_pack: far
        - name: To Do
          description: -
          icon: edit
          icon_pack: far
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
        - title: Research Assistant
          company: University Wuerzburg
          company_url: ''
          company_logo: org-gc
          location: Wuerzburg
          date_start: '2020-11-01'
          date_end: '2013-12-31'
          description: BMBF funded project - CoTeach
        - title: Internship - IT-Applications
          company: time:matters
          company_url: ''
          company_logo: org-x
          location: Neu-Isenburg
          date_start: '2017-01-01'
          date_end: '2017-07-01'
          description: 
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
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
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: publications
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
      coordinates:
        latitude: '49.78177'
        longitude: '9.973449'
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: rebecca.hein@uni-wuerzburg.de
      phone: 0931-31-96370
      address:
        street: Am Hubland
        city: Wuerzburg
        region: BY
        postcode: '97072'
        country: Germany
        country_code: Ger
      directions: Enter Building Z8 and take the stairs to Office 01.028 on Floor 1
      contact_links:
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
