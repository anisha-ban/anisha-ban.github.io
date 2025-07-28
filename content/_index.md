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
      title: Recent News
      subtitle: ''
      text: |-
        - June 2025: Presented the following work at ISIT 2025
          - A.B., Yonatan Yehezkeally, Antonia Wachter-Zeh and Eitan Yaakobi, "Correcting Multiple Substitutions in Nanopore-Sequencing Reads."
          - A.B., Roni Con, Antonia Wachter-Zeh and Eitan Yaakobi, "Decoding Insertions/Deletions visa List Recovery."
        - June 2025: Research stay at School of Computing, Imperial College London
        - May 2025: Research stay at Computational Bioinformatics Lab, Dept. of Computing, Imperial College London
    design:
      columns: '1'
      css_class: news-section
      css_style: |
        max-width: 1000px;
        margin: 0 auto;
        width: 100%;
        text-align: left;
        #font-family: 'Georgia', serif;
        font-size: 22px;
        padding: 30px 0;
        min-height: 50px;
        .markdown ul {
          padding-left: 40px;
          margin: 10px 0;
          text-align: left;
          width: 100%;
        }
        .markdown li {
          margin-bottom: 8px;
          line-height: 1.6;
        }
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---

