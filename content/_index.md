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
      # Choose a user profile to display (a folder name within content/authors/)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/cv_7.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to assets/media/.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    #id: news
    content:
      title: ""
      text: |-
        <h2 style="margin-bottom: 1px; padding-bottom: 1.5rem; font-size: 2.5rem; text-align: center">Recent News</h2>

        - June 2025: Presented the following work at ISIT 2025
          - A.B., Yonatan Yehezkeally, Antonia Wachter-Zeh and Eitan Yaakobi, "Correcting Multiple Substitutions in Nanopore-Sequencing Reads."
          - A.B., Roni Con, Antonia Wachter-Zeh and Eitan Yaakobi, "Decoding Insertions/Deletions visa List Recovery."
        - June 2025: Research stay at School of Computing, Imperial College London
        - May 2025: Research stay at Computational Bioinformatics Lab, Dept. of Computing, Imperial College London
    design:
      columns: '1'
      css_class: news-section
      css_style: |
        max-width: 400rem;
        text-align: left;
        #font-family: 'Georgia', serif;
        font-size: 24px;
        padding: 20px 0;



  - block: markdown
    content:
      title: ""
      text: |
        <h2 style="margin-bottom: 1px; padding-bottom: 1; font-size: 2.5rem">Recent Publications</h2>
    design:
      columns: '1'
      css_style: |
        padding: 10px 0;
        margin-bottom: 0;
  - block: collection
    content:
      title: ""
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      css_style: |
        margin-top: 0;
        padding-top: 0;
---

