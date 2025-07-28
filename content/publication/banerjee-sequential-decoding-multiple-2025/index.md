---
title: Sequential Decoding of Multiple Traces Over the Syndrome Trellis for Synchronization
  Errors

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lorenz Welter
- Alexandre Graell I Amat
- Antonia Wachter-Zeh
- Eirik Rosnes

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-07-27T07:57:05.956916Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2025 IEEE International Conference on Acoustics, Speech and Signal
  Processing (ICASSP)*'
publication_short: ''

doi: 10.1109/ICASSP49660.2025.10889909

abstract: Standard decoding approaches for convolutional codes, such as the Viterbi
  and BCJR algorithms, entail significant complexity when correcting synchronization
  errors. The situation worsens when multiple received sequences should be jointly
  decoded, as in DNA storage. Previous work has attempted to address this via separate-BCJR
  decoding, i.e., combining the results of decoding each received sequence separately.
  Another attempt to reduce complexity adapted sequential decoders for use over channels
  with insertion and deletion errors. However, these decoding alternatives remain
  prohibitively expensive for high-rate convolutional codes. To address this, we adapt
  sequential decoders to decode multiple received sequences jointly over the syndrome
  trellis. For the short blocklength regime, this decoding strategy can outperform
  separate-BCJR decoding under certain channel conditions, in addition to reducing
  decoding complexity. To mitigate the occurrence of a decoding timeout, formally
  called erasure, we also extend this approach to work bidirectionally, i.e., deploying
  two independent stack decoders that simultaneously operate in the forward and backward
  directions.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Complexity theory
- Convolutional codes
- Decoding
- DNA
- Signal processing
- Signal processing algorithms
- Speech processing
- Standards
- Synchronization
- Viterbi algorithm

# Display this page in a list of Featured pages?
featured: false

# Links
links:
 - name: arXiV
   url: https://arxiv.org/abs/2410.07120
url_paper: 'https://ieeexplore.ieee.org/document/10889909'
url_slides: uploads/slides/icassp25/seq_icassp.pdf
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
