---
title: Insertion and Deletion Correction in Polymer-Based Data Storage

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Antonia Wachter-Zeh
- Eitan Yaakobi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-07-27T09:03:35.748597Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Information Theory*'
publication_short: ''

doi: 10.1109/TIT.2023.3252045

abstract: Synthetic polymer-based data storage seems to be a particularly promising
  candidate that could help to cope with the ever-increasing demand for archival storage
  requirements. It involves designing molecules of distinct masses to represent the
  respective bits 0,1, followed by the synthesis of a polymer of molecular units that
  reflects the order of bits in the information string. Reading out the stored data
  requires the use of a tandem mass spectrometer, that fragments the polymer into
  shorter substrings and provides their corresponding masses, from which the composition,
  i.e. the number of 1s and 0s in the concerned substring can be inferred. Prior works
  have dealt with the problem of unique string reconstruction from the set of all
  possible compositions, called composition multiset. This was accomplished either
  by determining which string lengths always allow unique reconstruction, or by formulating
  coding constraints to facilitate the same for all string lengths. Additionally,
  error-correcting schemes to deal with substitution errors caused by imprecise fragmentation
  during the readout process, have also been suggested. This work builds on this research
  by extending previously considered error models, mainly confined to substitution
  of compositions. To this end, we define new error models that consider insertions
  of spurious compositions and deletions of existing ones, thereby corrupting the
  composition multiset. We analyze if the reconstruction codebook proposed by Pattabiraman
  et al. is indeed robust to such errors, and if not, propose new coding constraints
  to remedy this.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Codes
- composition errors
- deletions
- Encoding
- insertions
- Mass spectroscopy
- Memory
- Polymer-based data storage
- Polymers
- Redundancy
- string reconstruction
- Termination of employment

# Display this page in a list of Featured pages?
featured: false

# Links
links:
 - name: arXiV
   url: https://arxiv.org/abs/2201.08612
url_paper: 'https://ieeexplore.ieee.org/document/10058572'
url_slides: uploads/slides/isit22/anisha.pdf
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

