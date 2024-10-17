---
title: ""
date: 2022-10-24
type: page

design:
  spacing: "3rem"
      
sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/CV-Saito-2024.pdf
    design:
      css_class: dark
      background:
        color: black
        video:
          filename: dada.mp4
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: A Piece of Dada (2018)
          summary: about the film above
          text: In a city torn apart by a mad scramble for celebrity, Lady Dada seemingly has it all. The enigmatic performance artist lures her audience by ingesting vast amounts of money...
          image: dada.jpg
          button:
            text: Read More
            url: https://www.clarasaito.com/project/a-piece-of-dada/
    design:
      spacing:
        padding: [0]
  - block: collection
    content:
      title: Selected Works
      text: Here are a selection of projects that I have worked on over the years.
      count: 3
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: collection
    content:
      title: Selected Workshops
      text: Here are a selection of workshops that I have worked on over the years.
      count: 2
      filters:
        folders:
          - workshops
    design:
      view: article-grid
      fill_image: false
      columns: 2
---
