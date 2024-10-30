---
title: Fast Covariance Matrix Adaptation for Large-Scale Black-Box Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenhua Li
- Qingfu Zhang
- Xi Lin
- Hui-Ling Zhen

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.543799Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2018.2877641

abstract: Covariance matrix adaptation evolution strategy (CMA-ES) is a successful
  gradient-free optimization algorithm. Yet, it can hardly scale to handle high-dimensional
  problems. In this paper, we propose a fast variant of CMA-ES (Fast CMA-ES) to handle
  large-scale black-box optimization problems. We approximate the covariance matrix
  by a low-rank matrix with a few vectors and use two of them to generate each new
  solution. The algorithm achieves linear internal complexity on the dimension of
  search space. We illustrate that the covariance matrix of the underlying distribution
  can be considered as an ensemble of simple models constructed by two vectors. We
  experimentally investigate the algorithm's behaviors and performances. It is more
  efficient than the CMA-ES in terms of running time. It outperforms or performs comparatively
  to the variant limited memory CMA-ES on large-scale problems. Finally, we evaluate
  the algorithm's performance with a restart strategy on the CEC'2010 large-scale
  global optimization benchmarks, and it shows remarkable performance and outperforms
  the large-scale variants of the CMA-ES.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Adaptation models
- Complexity theory
- Covariance matrices
- Ensemble model
- evolution strategies
- large scale optimization
- low-rank model
- Matrix decomposition
- Optimization
- Search problems
- Task analysis

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
