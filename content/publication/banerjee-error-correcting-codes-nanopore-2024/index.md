---
title: Error-Correcting Codes for Nanopore Sequencing

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
publishDate: '2025-07-27T07:57:06.004279Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Information Theory*'
publication_short: ''

doi: 10.1109/TIT.2024.3380615

abstract: Nanopore sequencing, superior to other sequencing technologies for DNA storage
  in multiple aspects, has recently attracted considerable attention. Its high error
  rates, however, demand thorough research on practical and efficient coding schemes
  to enable accurate recovery of stored data. To this end, we consider a simplified
  model of a nanopore sequencer inspired by Mao et al., incorporating intersymbol
  interference and measurement noise. Essentially, our channel model passes a sliding
  window of length ell over a q -ary input sequence that outputs the composition of
  the enclosed ell bits, and shifts by delta positions with each time step. In this
  context, the composition of a q-ary vector boldsymbol x specifies the number of
  occurrences in boldsymbol x of each symbol in łbrace 0,1,łdots, q-1rbrace . The
  resulting compositions vector, termed the read vector, may also be corrupted by
  t substitution errors. By employing graph-theoretic techniques, we deduce that for
  delta =1 , at least łog łog n symbols of redundancy are required to correct a single
  ( t=1 ) substitution. Finally, for ell geq 3 , we exploit some inherent characteristics
  of read vectors to arrive at an error-correcting code that is of optimal redundancy
  up to a (small) additive constant for this setting. This construction is also found
  to be optimal for the case of reconstruction from two noisy read vectors.

# Summary. An optional shortened abstract.
summary: ''

tags:
- composition errors
- DNA
- DNA sequences
- Error correction codes
- error-correction codes
- Europe
- nanopore sequencing
- Noise measurement
- Sequence reconstruction
- Sequential analysis
- Symbols
- Vectors

# Display this page in a list of Featured pages?
featured: false

# Links
#links:
# - name: arXiV
#   url: https://arxiv.org/abs/2505.02452
url_paper: 'https://ieeexplore.ieee.org/document/10478160'
url_slides: uploads/slides/isit23/main_nanopore.pdf
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
