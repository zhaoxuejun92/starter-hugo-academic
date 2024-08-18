---
# Leave the homepage title empty to use the site title
title: Welcom to my site!
date: 2024-08-18
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: pub
    content:
      title: Publication
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: pub
    content:
      title: Working Paper
      filters:
        folders:
          - working_papers
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    id: teaching
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Teaching Experience'
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
          date_start: '2024-01-15'
          description: Spring 2024
          organization: University of North Carolina at Charlotte
          organization_url: 
          title: Instructor of Operations Management
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-08-15'
          description: Fall 2023, Spring 2024, Fall 2024
          organization: University of North Carolina at Charlotte
          organization_url: 
          title: Instructor of Operations Planning and Control
          url: ''
        - certificate_url: 
          date_end: '2020-06-15'
          date_start: '2020-05-15'
          description: Summer 2020
          organization: Purdue University
          organization_url: 
          title: Instructor of Operations Managmenet
          url: ''
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 3
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
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
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
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Honors & Awards'
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
          date_end: '2020-12-31'
          date_start: '2020-01-01'
          description: 
          organization: Purdue University
          organization_url: 
          title: Krannert Doctoral Research Funds
          url: ''
        - certificate_url: 
          date_end: '2020-08-01'
          date_start: '2020-05-01'
          description: 
          organization: Purdue University
          organization_url: 
          title: Krannert Certificate for Outstanding Teaching
          url: 
    design:
      columns: '2'
  # - block: experience
  #   content:
  #     title: 'Industry Eperience'
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: Data Scientist
  #         company: Verizon
  #         company_url: ''
  #         company_logo: ''
  #         location: Ashburn, Virginia
  #         date_start: '2023-01-01'
  #         date_end: '2023-05-01'
  #         description: ''
  #       - title: Data Scientist Intern
  #         company: Google
  #         company_url: ''
  #         company_logo: ''
  #         location: Sunnyvale, California
  #         date_start: '2022-07-15'
  #         date_end: '2022-09-30'
  #         description: ''
  #   design:
  #     columns: '2'
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
