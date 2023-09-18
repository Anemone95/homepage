---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    headless: true
    content:
      title: Recent & Upcoming Events
      text: |-
        * (2023.09) I will attend [PLISS 2023](https://pliss.org/2023/) soon!
        * (2023.05) Our team won the 1st place in ChalmersGU-KTH-Aarhus CTF competition!
        * (2022.08) I will be a Ph.D. Student at Computer Science Department at Aarhus University!
    design:
      columns: 2
  - block: collection
    # id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
        # exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    headless: true
    id: service
    content:
      title: 'Service & Teaching'
      text: |-
        ## TA
        * Compiler, 2022 Autumn 
    design:
      columns: 2
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
        - title: Ph.D. Student \(in [CASA](https://casa.au.dk/), Advisor:&nbsp;[Anders Møller](https://cs.au.dk/~amoeller/)\)
          company: Aarhus University
          company_url: 'https://cs.au.dk/'
          location: Aarhus, Denmark
          date_start: '2022-08-01'
          date_end: ''
          # description: |-
          #   * Pointer Analysis for JavaScript
          #   * Malicious Code Detection for NPM package
        - title: Security Engineer
          company: Alibaba Security Department
          company_url: 'https://s.alibaba.com/'
          location: Hangzhou, China
          date_start: '2020-08-01'
          date_end: '2022-07-01'
          # description: |- 
          #   * Mainly working on static program analysis.
        - title: Graduate Student in Software Engineering (in [iSE](http://www.iselab.cn/) Lab, Leader:&nbsp;[Zhenyu Chen](http://www.iselab.cn/html/people/faculty/ZhenyuChen.html))
          company: Nanjing University
          company_url: 'https://software.nju.edu.cn/English/index.html'
          location: Nanjing, China 
          date_start: '2018-09-01'
          date_end: '2020-07-01'
          # description: |1-
          #   * Taint Analysis for Java Web and Android Application
        - title: Undergraduate Student in Network Engineering (in [RiSAME](https://risame.github.io/) Group, Leader:&nbsp;[Xiaobing Sun](https://risame.github.io/sun/index.html))
          company: Yangzhou University
          company_url: 'http://english.yzu.edu.cn/'
          location: Yangzhou, China 
          date_start: '2014-09-01'
          date_end: '2018-06-30'
    design:
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
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact Me
      address:
        street: Turning-222, IT-parken, Aabogade 34
        city: Aarhus
        # region: CA
        postcode: '8200'
        country: Denmark
        country_code: DK
      email: wenyuan.xu@cs.au.dk
      phone: +45 50 34 19 71
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/wyxu95'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://aarhusuniversity.zoom.us/my/wenyuanxu'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
  #       

  # TODO: reprensentitive work!!!
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
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
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact

  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
---
