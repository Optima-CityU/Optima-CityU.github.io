---
title: MOEA/D with chain-based random local search for sparse optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hui Li
- Jianyong Sun
- Mingyang Wang
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2018-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.574208Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Soft Computing*'
publication_short: ''

doi: 10.1007/s00500-018-3460-y

abstract: The goal in sparse approximation is to find a sparse representation of a
  system. This can be done by minimizing a data-fitting term and a sparsity term at
  the same time. This sparse term imposes penalty for sparsity. In classical iterative
  thresholding methods, these two terms are often combined into a single function,
  where a relaxed parameter is used to balance the error and the sparsity. It is acknowledged
  that the setting of relaxed parameter is sensitive to the performance of iterative
  thresholding methods. In this paper, we proposed to address this difficulty by finding
  a set of nondominated solutions with different sparsity levels via multiobjective
  evolutionary algorithms (MOEAs). A new MOEA/D is developed specifically for sparse
  optimization, in which a chain-based random local search (CRLS) is employed for
  optimizing subproblems with various sparsity levels. The performance of the proposed
  algorithm, denoted by MOEA/D-CRLS, is tested on a set of sixteen noise-free or noisy
  test problems. Our experimental results suggest that MOEA/D-CRLS is competitive
  regarding the solution precision on the noise-free test problems, and clearly superior
  on the noisy test problems against three existing representative sparse optimization
  methods.

# Summary. An optional shortened abstract.
summary: ''

tags:
- CRLS
- HALF
- MOEA/D
- Multiobjective optimization
- Sparse optimization
- SPLS

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
