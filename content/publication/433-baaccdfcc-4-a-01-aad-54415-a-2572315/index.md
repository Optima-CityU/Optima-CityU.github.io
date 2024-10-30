---
title: What does the evolution path learn in CMA-ES?

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

date: '2016-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.542063Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Parallel Problem Solving from Nature*'
publication_short: ''

doi: 10.1007/978-3-319-45823-6_70

abstract: The Covariance matrix adaptation evolution strategy (CMA-ES) evolves a multivariate
  Gaussian distribution for continuous optimization. The evolution path, which accumulates
  historical search directions in successive generations, plays a crucial role in
  the adaptation of covariance matrix. In this paper, we investigate what the evolution
  path learns in the optimization procedure. We show that the evolution path accumulates
  natural gradient with respect to the distribution mean, and acts as a momentum under
  stationary condition. The experimental results suggest that the evolution path learns
  relative scales of the eigenvectors, expanded by singular values along corresponding
  eigenvectors of the inverse Hessian. Further, we show that the outer product of
  evolution path serves as a rank-1 momentum term for the covariance matrix.

# Summary. An optional shortened abstract.
summary: ''

tags: []

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
