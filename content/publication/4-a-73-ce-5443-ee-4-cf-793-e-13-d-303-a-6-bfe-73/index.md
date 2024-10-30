---
title: Self-supervised Symmetric Nonnegative Matrix Factorization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yuheng Jia
- Hui Liu
- Junhui Hou
- Sam Kwong
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.750572Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Circuits and Systems for Video Technology*'
publication_short: ''

doi: 10.1109/TCSVT.2021.3129365

abstract: Symmetric nonnegative matrix factorization (SNMF) has demonstrated to be
  a powerful method for data clustering. However, SNMF is mathematically formulated
  as a non-convex optimization problem, making it sensitive to the initialization
  of variables. Inspired by ensemble clustering that aims to seek a better clustering
  result from a set of clustering results, we propose self-supervised SNMF (S3NMF),
  which is capable of boosting clustering performance progressively by taking advantage
  of the sensitivity to initialization characteristic of SNMF, without relying on
  any additional information. Specifically, we first perform SNMF repeatedly with
  a random positive matrix for initialization each time, leading to multiple decomposed
  matrices. Then, we rank the quality of the resulting matrices with adaptively learned
  weights, from which a new similarity matrix that is expected to be more discriminative
  is reconstructed for SNMF again. These two steps are iterated until the stopping
  criterion/maximum number of iterations is achieved. We mathematically formulate
  S3NMF as a constrained optimization problem, and provide an alternative optimization
  algorithm to solve it with the theoretical convergence guaranteed. Extensive experimental
  results on 10 commonly used benchmark datasets demonstrate the significant advantage
  of our S3NMF over 14 state-of-the-art methods in terms of 5 quantitative metrics.
  The source code is publicly available at https://github.com/jyh-learning/SSSNMF.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Symmetric nonnegative matrix factorization
- dimensionality reduction
- clustering

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
