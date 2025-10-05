---
title: 'Home'
date: 2025-09-04
type: landing

design:
  # Default section spacing
  spacing: '4rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: rounded # Options: circle (default), square, rounded
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0px', '20px', '0px']
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: collection
    content:
      title: Publications
      username: admin
      count: 20
      filters:
        folders:
          - publication
    design:
      # Choose your content listing view - here we use the `showcase` view
      view: citation
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0px', '20px', '0px']
  # - block: languages
  #   content:
  #     title: Languages
  #     username: admin
---
