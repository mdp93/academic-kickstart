---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-06-16
type: landing

design:

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Recent News'
      subtitle: "[All news>>](/news)"
      text: |-
        {{< readfromfile "/content/newslist.dat" 5 >}} 
    design:
      columns: '1'
---