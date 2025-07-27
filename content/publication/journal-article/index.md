---
title: "Error-Correcting Codes for Nanopore Sequencing"
authors:
- admin
- Yonatan Yehezkeally
- Antonia Wachter-Zeh
- Eitan Yaakobi
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Theory, 70*(7)"
publication_short: ""

abstract: Nanopore sequencing, superior to other sequencing technologies for DNA storage in multiple aspects, has recently attracted considerable attention. Its high error rates, however, demand thorough research on practical and efficient coding schemes to enable accurate recovery of stored data. To this end, we consider a simplified model of a nanopore sequencer inspired by Mao et al., incorporating intersymbol interference and measurement noise. Essentially, our channel model passes a sliding window of length \ell over a q -ary input sequence that outputs the composition of the enclosed \ell bits, and shifts by \delta positions with each time step. In this context, the composition of a q-ary vector \boldsymbol x specifies the number of occurrences in \boldsymbol x of each symbol in łbrace 0,1,łdots, q-1\rbrace . The resulting compositions vector, termed the read vector, may also be corrupted by t substitution errors. By employing graph-theoretic techniques, we deduce that for \delta =1 , at least łog łog n symbols of redundancy are required to correct a single ( t=1 ) substitution. Finally, for \ell \geq 3 , we exploit some inherent characteristics of read vectors to arrive at an error-correcting code that is of optimal redundancy up to a (small) additive constant for this setting. This construction is also found to be optimal for the case of reconstruction from two noisy read vectors.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10478160
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
#url_poster: ''
#url_project: ''
url_slides: ''
url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
