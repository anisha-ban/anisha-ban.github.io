---
title: Correcting a Single Deletion in Reads from a Nanopore Sequencer

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yonatan Yehezkeally
- Antonia Wachter-Zeh
- Eitan Yaakobi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-07-27T07:57:05.930578Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2024 IEEE International Symposium on Information Theory (ISIT)*'
publication_short: ''

doi: 10.1109/ISIT57864.2024.10619468

abstract: Owing to its several merits over other DNA sequencing technologies, nanopore
  sequencers hold an immense potential to revolutionize the efficiency of DNA storage
  systems. However, their higher error rates necessitate further research to devise
  practical and efficient coding schemes that would allow accurate retrieval of the
  data stored. Our work takes a step in this direction by adopting a simplified model
  of the nanopore sequencer inspired by Mao et al., which incorporates some of its
  physical aspects. This channel model can be viewed as a sliding window of length
  $ell$ that passes over the incoming input sequence and produces the Hamming weight
  of the enclosed $ell$ bits, while shifting by one position at each time step. The
  resulting ($ell$ + 1)-ary vector, referred to as the $ell$-read vector, is susceptible
  to deletion errors due to imperfections inherent in the sequencing process. We establish
  that at least log n - $ell$ bits of redundancy are needed to correct a single deletion.
  An error-correcting code that is optimal up to an additive constant, is also proposed.
  Furthermore, we find that for $ell$ $≥$ 2, reconstruction from two distinct noisy
  $ell$-read vectors can be accomplished without any redundancy, and provide a suitable
  reconstruction algorithm to this effect.

# Summary. An optional shortened abstract.
summary: ''

tags:
- DNA
- Error analysis
- Receivers
- Reconstruction algorithms
- Redundancy
- Sequential analysis
- Vectors

# Display this page in a list of Featured pages?
featured: false

# Links
links:
 - name: arXiV
   url: https://arxiv.org/pdf/2401.15939
url_paper: 'https://ieeexplore.ieee.org/document/10619468'
url_slides: uploads/slides/isit24/anisha.pdf
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
