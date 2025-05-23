---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Welcome to Zihan's Website
      # image:
      #  filename: hero-academic.png
      
      text: |-
        **My research focuses on the sensing systems and data solutions for embodied AI**

    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
#  - block: features
#    content:
#      title: Expertise
#      items:
#        - name: LabVIEW
#          description: 
#          icon: labview-blue
#          icon_pack: custom
#        - name: Embedded Systems
#          description: 
#          icon: microchip-ai
#          icon_pack: custom
#        - name: Soft Robot Fabrication
#          description: 
#          icon: soft_robot
#          icon_pack: custom
  - block: experience
    content:
      title: Education & Working Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Researcher
          company: UC Berkeley
          company_url: ''
          company_logo: UC-Berkeley-Emblem
          location: California, USA
          date_start: '2024-07-01'
          date_end: ''
          description: |2-
              Research topics include:
              * Sensing systems for robots
              * Data solutions for embodied AI

        - title: Ph.D. in Data Science and Information Technology
          company: Tsinghua University
          company_url: ''
          company_logo: Tsinghua_University_Logo
          location: China
          date_start: '2019-09-01'
          date_end: '2024-07-01'
          description: Thesis - Research on Key Technologies of Flexible Triboelectric Sensors for Robotic Applications

        - title: B.Eng. in Telecommunications Engineering
          company: Herriot-Watt University
          company_url: ''
          company_logo: HWU_Logo
          location: Scotland, UK
          date_start: '2015-08-30'
          date_end: '2019-06-01'
          description: Thesis - Motion Primitives Extraction in MIS Instrument Trajectories for Pattern Recognition

        - title: B.Eng. in Telecommunications Engineering
          company: Xidian University
          company_url: ''
          company_logo: Xidian_Logo
          location: China
          date_start: '2015-08-30'
          date_end: '2019-06-01'
          description: Joint dual-degree programme with Herriot-Watt University
        
        - title: Visiting Student
          company: Boston University
          company_url: ''
          company_logo: BU_Logo
          location: Massachusetts, USA
          date_start: '2018-07-01'
          date_end: '2018-08-01'
          description: English for STEM leaders  
          
    design:
      columns: '2'
  #- block: accomplishments
  #  content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #    title: 'Accomplish&shy;ments'
  #    subtitle:
  #    # Date format: https://wowchemy.com/docs/customization/#date-format
  #    date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
   #   items:
   #     - certificate_url: https://www.coursera.org
   #       date_end: ''
   #       date_start: '2021-01-25'
   #       description: ''
   #       organization: Coursera
   #       organization_url: https://www.coursera.org
   #       title: Neural Networks and Deep Learning
   #       url: ''
   # design:
   #   columns: '2'
  #- block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
      # Choose how many pages you would like to display (0 = all pages)
   #   count: 5
      # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: compact
  #    columns: '2'
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
   #   buttons:
   #     - name: All
   #       tag: '*'
   #     - name: Deep Learning
   #       tag: Deep Learning
   #     - name: Other
   #       tag: Demo
   # design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
   #   columns: '1'
   #   view: showcase
      # For Showcase view, flip alternate rows?
   #   flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Selected Photograph
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      text: |-
        {{% callout note %}}
        Full list of my publication can be found [here](./publication/).
        {{% /callout %}}
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
        Full list of my publication can be found [here](./publication/).
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
      title: Recent & Upcoming Talks
      filters:
        folders:
          - talks
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Research Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Leave a message here
      # Contact (add or remove contact options as necessary)
      email: zihan.wang@berkeley.edu
      # phone: (582)213-1207
      #appointment_url: 'https://calendly.com'
      address:
        street: 2521 Hearst Ave
        city: Berkeley
        region: CA
        postcode: '94709'
        country: United States
        country_code: US
      directions: Etchevery Hall 1113
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
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
