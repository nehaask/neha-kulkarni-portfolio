---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/NEHA_KULKARNI_MLE.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '📚 My Work'
      subtitle: ''
      text: |-
       This site serves as my personal mindtrace—a space where I document things I find interesting, whether it's something I’ve been reading, watching, or exploring — ranging from recent AI breakthroughs to emerging research in computer vision, robotics, and autonomous systems.
        
        🔍 Always open to discussing ideas and research! Let’s connect and collaborate! 😃
    design:
      columns: '1'

#   - block: collection
#     demo: false
#     id: papers
#     content:
#       title: Featured Publications
#       filters:
#         folders:
#           - publication
#         featured_only: true
#     design:
#       view: article-grid
#       columns: 2

#   - block: collection
#     demo: false
#     content:
#       title: Recent Publications
#       text: ""
#       filters:
#         folders:
#           - publication
#         exclude_featured: false
#     design:
#       view: masonry

#   - block: collection
#     demo: false
#     id: talks
#     content:
#       title: Recent & Upcoming Talks
#       filters:
#         folders:
#           - event
#     design:
#       view: article-grid
#       columns: 1

#   - block: collection
#     id: news
#     content:
#       title: Recent News
#       subtitle: ''
#       text: ''
#       # Page type to display. E.g. post, talk, publication...
#       page_type: post
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 5
#       # Filter on criteria
#       filters:
#         author: ""
#         category: ""
#         tag: ""
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#         publication_type: ""
#       # Choose how many pages you would like to offset by
#       offset: 0
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a layout view
#       view: date-title-summary
#       # Reduce spacing
#       spacing:
#         padding: [0, 0, 0, 0]
        
---