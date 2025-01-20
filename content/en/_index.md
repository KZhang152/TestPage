---
# Leave the homepage title empty to use the site title
title: ""
date: ''
type: landing

design:
  # Default section spacing
  spacing: "0rem"
  # spacing:
  #   padding: ['0rem', '0rem', '0rem', '0rem']
  # background:
  #   image:
  #     filename: # background.png

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: huqinghua
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: system
      background:
        image:
          # Add your image background to `assets/media/`.
          filename:  # stacked-peaks.svg
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: false

  # - block: markdown
  #   content:
  #     title: 'Research'
  #     subtitle: ''
  #     text: |-
  #       mardown text

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '2'

  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  # - block: collection
  #   content:
  #     title: "Recent Publications"
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1

  - block: collection
    id: news
    content:
      title: Recent Publications
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: publication
      # Choose how many pages you would like to display (0 = all pages)
      count: 4
      # Filter on criteria
      filters:
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
      # view: date-title-summary
      view: article-grid
      # Reduce spacing
      spacing:
        padding: [5rem, 0, 0, 0]

  - block: experience
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: experience
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      spacing:
        padding: [5rem, 0, 0, 0]
      css_class: system
      background:
        image:
          # Add your image background to `assets/media/`.
          filename:  # stacked-peaks.svg
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: false

---
