---
title: A multiobjective optimization based framework to balance the global exploration
  and local exploitation in expensive optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhiwei Feng
- Qingbin Zhang
- Qingfu Zhang
- Qiangang Tang
- Tao Yang
- Yang Ma

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2015-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.902162Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Journal of Global Optimization*'
publication_short: ''

doi: 10.1007/s10898-014-0210-2

abstract: In many engineering optimization problems, objective function evaluations
  can be extremely computationally expensive. The effective global optimization (EGO)
  is a widely used approach for expensive optimization. Balance between global exploration
  and local exploitation is a very important issue in designing EGO-like algorithms.
  This paper proposes a multiobjective optimization based EGO (EGO-MO) for addressing
  this issue. In EGO-MO, a global surrogate model for the objective function is firstly
  constructed using some initial database of designs. Then, a multiobjective optimization
  problem (MOP) is formulated, in which two objectives measure the global exploration
  and local exploitation. At each generation, the multiobjective evolutionary algorithm
  based on decomposition is used for solving the MOP. Several solutions selected from
  the obtained Pareto front are evaluated. In such a way, it can generate multiple
  test solutions simultaneously to take the advantage of parallel computing and reduce
  the computational time. Numerical experiments on a suite of test problems have shown
  that EGO-MO outperforms EGO in terms of iteration numbers.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Efficient global optimization
- Expensive optimization
- Gaussian stochastic processes
- MOEA/D
- Multiobjective optimization

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
