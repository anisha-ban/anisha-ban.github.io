---
title: 'Decoding Insertions/Deletions via List Recovery'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Roni Con
  - Antonia Wachter-Zeh
  - Eitan Yaakobi

# Author notes (optional)
#author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'

date: '2025-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
#publication: In *Hugo Blox Builder Conference*
publication_short: In *ISIT 2025*

abstract: In this work, we consider the problem of efficient decoding of codes from insertions and deletions. Most of the known efficient codes are codes with synchronization strings which allow one to reduce the problem of decoding insertions and deletions to that of decoding substitution and erasures. Our new approach, presented in this paper, reduces the problem of decoding insertions and deletions to that of list recovery. Specifically, any \((\rho, 2\rho n + 1, L)\)-list-recoverable code is a \((\rho, L)\)-list decodable insdel code. As an example, we apply this technique to Reed-Solomon (RS) codes, which are known to have efficient list-recovery algorithms up to the Johnson bound. In the adversarial insdel model, this provides efficient (list) decoding from \(t\) insdel errors, assuming that \(t\cdot k = O(n)\). This is the first efficient insdel decoder for \([n, k]\) RS codes for \(k>2\). Additionally, we explore random insdel models, such as the Davey-MacKay channel, and show that for certain choices of \(\rho\), a \((\rho, n^{1/2+0.001}, L)\)-list-recoverable code of length \(n\) can, with high probability, efficiently list decode the channel output, ensuring that the transmitted codeword is in the output list. In the context of RS codes, this leads to a better rate-error tradeoff for these channels compared to the adversarial case. We also adapt the Koetter-Vardy algorithm, a famous soft-decision list decoding technique for RS codes, to correct insertions and deletions induced by the Davey-MacKay channel.

tags:
  - Reed-Solomon codes
  - List recovery
  - Insertions and deletions

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: ArXiV
   url: https://arxiv.org/abs/2505.02452

url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
