---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-8-1
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: View or Download CV
        url: static/uploads/CV/NAJohnsonCV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: Sunny_boat.jpg
          filters:
            brightness: 0.5
          size: cover
          position: top
          parallax: true
  - block: markdown
    content:
      title: '🌿 My Research 🧬'
      subtitle: ''
      text: |-
        As a graduate research assistant in Dr. Eric Patterson's lab at Michigan State University, I utilize a range of computational approaches for comparative genomics of weedy and non-           weedy plant genomes to understand the adaptive capabilities of weeds. For this work I have performed analyses such as phyologeny, dN/dS, genome annotation, alignment, differential expression, enrichment, and a variety of visualization methods.

        I enjoy producing computational tools from my work with the aim of making computational analysis more approachable for non-computational biologists.
        
        Please reach out if you would like to collaborate!
    design:
      columns: '1'
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
  - block: collection
    id: papers
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Presentations
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
---
