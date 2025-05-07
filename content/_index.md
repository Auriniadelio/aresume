---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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
        text: intro video!
        url: https://youtu.be/CwoTlvE2A9Q?si=4LigRw0sQNGLp6bg
      button:
        text: Intro Video!
        url: https://youtu.be/CwoTlvE2A9Q?si=4LigRw0sQNGLp6bg
    design:
      css_class: dark
     
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: blue.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Aspirations'
      subtitle: ''
      text: |-
        As a dedicated full-time student and an aspiring future dietitian that is willing to give out the best for the sake of public’s health. Someone that takes pride in nutrition and how it affects one’s way of living. Is optimistic in finding opportunities to apply knowledge in real-world and professional setting.
    design:
      columns: '1'
  - block: markdown
    id: resume
    content:
      title: '📜 My Resume'
      subtitle: ''
      text: |-
        
        [🔗 Download Resume](/uploads/resume.pdf)

        Click the button above to see and download my resume!
      align: center
      button:
        text: 📄 Download Resume
        url: uploads/resume.pdf  
    design:
      columns: '1'

  - block: collection
    id: activities
    content:
      title: Activities
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 3


---
