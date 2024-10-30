---
title: A Simple Yet Efficient Evolution Strategy for Large-Scale Black-Box Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenhua Li
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2018-10-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.705088Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2017.2765682

abstract: We propose an evolution strategy algorithm using a sparse plus low rank
  model for large scale optimization in this paper. We first develop a rank one evolution
  strategy (R1-ES) using a single principal search direction. It is of linear complexity.
  Then we extend it to multiple search directions, and develop a rank-m evolution
  strategy (Rm-ES). We illustrate that the principal search direction accumulates
  the natural gradients with respect to the distribution mean, and acts as a momentum
  term. Further, we analyze the optimal low rank approximation to the covariance matrix,
  and experimentally show that the principal search direction can effectively learn
  the long valley of the function with predominant search direction. Then we investigate
  the effects of Hessian on the algorithm performance. We conduct experiments on a
  class of test problems and the CECtextquoteright2010 LSGO benchmarks. The experimental
  results validate the effectiveness of our proposed algorithms.

# Summary. An optional shortened abstract.
summary: ''

tags:
- evolution path
- evolution strategy
- low rank model
- principal search direction

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
