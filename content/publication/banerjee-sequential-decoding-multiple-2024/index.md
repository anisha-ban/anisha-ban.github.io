---
title: Sequential Decoding of Multiple Sequences for Synchronization Errors

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Andreas Lenz
- Antonia Wachter-Zeh

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-07-27T07:57:06.105478Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Communications*'
#publication_short: 'TCOMM'

doi: 10.1109/TCOMM.2024.3405322

abstract: Sequential decoding, commonly applied to substitution channels, is a sub-optimal
  alternative to Viterbi decoding with significantly reduced memory costs. This work
  describes and analyzes a sequential decoder for convolutional codes over channels
  prone to insertion, deletion, and substitution errors. Our decoder expands the code
  trellis by a new channel-state variable, called drift state, as proposed by Davey
  and MacKay. A suitable decoding metric on that trellis for sequential decoding is
  derived, generalizing the original Fano metric. The decoder is also extended to
  facilitate the simultaneous decoding of multiple received sequences that arise from
  a single transmitted sequence. Under low-noise environments, our decoding approach
  reduces the decoding complexity by multiple orders of magnitude compared to Viterbi's
  algorithm, albeit at slightly higher bit error rates. An analytical method to determine
  the computational cutoff rate is also suggested. This analysis is supported by numerical
  evaluations of bit error rates and computational complexity, compared to optimal
  Viterbi decoding.

# Summary. An optional shortened abstract.
summary: ''

tags:
- convolutional codes
- Convolutional codes
- Decoding
- deletion
- DNA storage
- Hidden Markov models
- insertion
- Measurement
- sequential decoding
- substitution (IDS) channel
- Symbols
- Vectors
- Viterbi algorithm

# Display this page in a list of Featured pages?
featured: false

links:
# - name: arXiV
#   url: https://arxiv.org/abs/2505.02452
url_paper: 'https://ieeexplore.ieee.org/document/10538284'
url_slides: uploads/slides/itw22/seq_itw.pdf
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
