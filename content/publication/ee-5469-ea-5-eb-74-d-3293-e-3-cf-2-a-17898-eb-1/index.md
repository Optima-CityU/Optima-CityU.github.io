---
title: Learning Low-rank Graph with Enhanced Supervision

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hui Liu
- Yuheng Jia
- Junhui Hou
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.542063Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Circuits and Systems for Video Technology*'
publication_short: ''

doi: 10.1109/TCSVT.2021.3089336

abstract: In this paper, we propose a new semi-supervised graph construction method,
  which is capable of adaptively learning the similarity relationship between data
  samples by fully exploiting the potential of pairwise constraints, a kind of weakly
  supervisory information. Specifically, to adaptively learn the similarity relationship,
  we linearly approximate each sample with others under the regularization of the
  low-rankness of the matrix formed by the approximation coefficient vectors of all
  the samples. In the meanwhile, by taking advantage of the underlying local geometric
  structure of data samples that is empirically obtained, we enhance the dissimilarity
  information of the available pairwise constraints via propagation. We seamlessly
  combine the two adversarial learning processes to achieve mutual guidance. We cast
  our method as a constrained optimization problem and provide an efficient alternating
  iterative algorithm to solve it. Experimental results on five commonly-used benchmark
  datasets demonstrate that our method produces much higher classification accuracy
  than state-of-the-art methods, while running faster.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Semi-supervised learning
- graph construction
- pairwise constraints
- low-rank
- propagation

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
