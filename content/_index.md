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
        text: Download CV
        url: uploads/resume.pdf
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
      title: '🖥️ My Research'
      subtitle: ''
      text: |-
        I'm a research scientist in the [Compilers Creating Custom Processors (CCCP)](https://cccp.eecs.umich.edu) group at the University of Michigan in the [Computer Engineering Lab](https://ce.engin.umich.edu) advised under [Prof. Scott Mahlke](https://web.eecs.umich.edu/~mahlke/). I also work closely unofficially with [Prof. Reetuparna Das](https://web.eecs.umich.edu/~reetudas/) for more computer architecture-focused insights. My goals are to combine my knowledge with compilers and computer architecture to make things go *zoom*.

        I am currently part of a collaboration with Los Alamos National Lab for accelerating their HPC applications. My current focus is on speeding up codes with indirect accesses by improving memory accesses. My current approach is exploring compiler optimizations that increase spatial locality.

        In the future, I intend to explore these techniques and how they can be extended to other applications, such as adaptive mesh refinement or in sparse LLM inference.
        
        Please reach out if you want to learn more or collaborate! 👍
    design:
      columns: '1'
  # - block: cta-button-list
  #   content:
  #     buttons:
  #       - text: Read my latest paper on LLMs
  #         icon: academicons/arxiv
  #         url: https://arxiv.org/abs/2304.01852
  #       - text: Watch my new YouTube video to achieve 20x productivity
  #         icon: brands/youtube
  #         url: https://youtube.com
  #       - text: Connect with me on LinkedIn
  #         icon: brands/linkedin
  #         url: https://linkedin.com
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
  #     title: Recent Publications
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
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
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
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
