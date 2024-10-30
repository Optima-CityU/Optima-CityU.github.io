---
title: An efficient rank-1 update for Cholesky CMA-ES using auxiliary evolution path

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

date: '2017-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.671846Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2017 IEEE Congress on Evolutionary Computation (CEC) : Proceedings*'
publication_short: ''

doi: 10.1109/CEC.2017.7969406

abstract: Covariance matrix adaptation evolution strategies (CMA-ES) is a powerful
  optimizer. In this paper, we propose an efficient rank-1 update for the Cholesky
  covariance matrix adaptation evolution strategy (Cholesky CMA-ES) using an auxiliary
  evolution path. It accumulates the average mutation vector corresponding to the
  current search direction, which is used to update the evolution path. It is used
  to update the Cholesky factor. It avoids to maintain the additional inverse Cholesky
  factor, and reduces the computational complexity in the update procedure to a half.
  Further, we experimentally show that the auxiliary evolution path approximates to
  the inverse vector of the evolution path in terms of inverse Cholesky factor in
  the procedure. We experimentally show that the proposed method achieves comparative
  or even better performances on the test problems.

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
links:
- name: URL
  url: http://www.cec2017.org/, http://www.cec2017.org/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
