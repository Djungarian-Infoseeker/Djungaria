---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography
    content:
      # The user's folder name in `content/authors/`
      username: admin
      # Show a call-to-action button under your biography? (optional)
      # To link to a file, upload it to your `static/uploads/` folder
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
        filename: ''
      biography:
        # Customize the CSS style of your biography text (optional)
        style: ''
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            Websites built  
            with Hugo Blox
        - statistic: "10k+"
          description: |
            GitHub stars  
            since 2016
        - statistic: "3k+"
          description: |
            Discord community  
            for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: resume-experience
    content:
      # The user's folder name in `content/authors/`
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      # Note: `username` refers to the user's folder name in `content/authors/`
      username: admin
  - block: resume-languages
    content:
      title: Languages
      # Note: `username` refers to the user's folder name in `content/authors/`
      username: admin
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
