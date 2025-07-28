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

date: '2022-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-07-27T07:57:06.056458Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2022 IEEE International Symposium on Information Theory (ISIT)*'
publication_short: ''

doi: 10.1109/ISIT50566.2022.9834352

abstract: Synthetic polymer-based storage promises to accommodate the ever-increasing
  demand for archival storage. It involves designing molecules of distinct masses
  to represent the respective bits 0, 1, followed by the synthesis of a polymer of
  molecular units that reflects the order of bits in the information string. The stored
  data can be read by means of a tandem mass spectrometer, that fragments the polymer
  into shorter substrings and provides their corresponding masses, from which the
  composition, i.e., the number of 1s and 0s in the concerned substring can be inferred.
  Prior works tackled the problem of unique string reconstruction from the set of
  all possible compositions, called the composition multiset. This was accomplished
  either by determining which string lengths always allow unique reconstruction, or
  by formulating coding constraints to facilitate the same for all string lengths.
  Additionally, error-correcting schemes to deal with substitution errors caused by
  imprecise fragmentation during the readout process, have also been suggested. This
  work extends previously considered error models that were mainly confined to substitutions
  of compositions. Our new error models consider insertions and deletions of compositions.
  The robustness of the reconstruction codebook proposed by Pattabiraman et al. to
  such errors is examined, and whenever necessary, new coding constraints are proposed
  to ensure unique reconstruction.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Encoding
- Memory
- Polymers
- Robustness

# Display this page in a list of Featured pages?
featured: false

# Links
links:
 - name: arXiV
   url: https://arxiv.org/abs/2505.02447
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

