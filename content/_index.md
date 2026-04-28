---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ' I completed my PhD  at the University of Illinois at Chicago. I have worked on several projects that sit at the intersections of Learning Sciences, Human-Computer Interaction, Computing Education, and Social Robotics. My research examines how learning environments can support girls’ participation in computing, with a focus on interest development and belonging. My dissertation introduces the MyTurn social robotics program, which integrates material and social scaffolds to engage middle school girls in CS through open-ended and collaborative project work that supports knowledge, value and belonging in CS.'
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'About'
        education: 'Education'
        interests: 'Research Interests'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
       My research sits at the intersection of Human-Computer Interaction, computing education, and learning sciences. I design and study learning environments that broaden participation in computing, particularly for girls.

  Grounded in the DICE framework, my work examines how knowledge, value, and belonging can be supported through both material and social scaffolds. Through the MyTurn social robotics program, I explore how collaborative design, storytelling, and mentorship can reshape how young learners perceive computing and their place within it.

  I use a combination of qualitative and quantitative methods, including artifact analysis, thematic analysis, and design-based research, to understand how learners engage with and make meaning from these experiences.
        Please reach out to collaborate!
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  
