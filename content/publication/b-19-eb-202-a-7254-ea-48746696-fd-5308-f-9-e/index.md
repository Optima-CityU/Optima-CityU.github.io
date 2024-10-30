---
title: Multiple Penalties and Multiple Local Surrogates for Expensive Constrained
  Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Genghui Li
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.122791Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2021.3066606

abstract: 'This paper proposes an evolutionary algorithm using multiple penalties
  and multiple local surrogates (called MPMLS) for expensive constrained optimization.
  In each generation, MPMLS defines and optimizes a number of subproblems. Each subproblem
  penalizes the constraints in the original problem using a different penalty coefficient
  and has its own search subregion. A local surrogate is built for optimizing each
  subproblem. Two major advantages of MPMLS are: 1) it can maintain good population
  diversity so that the search can approach the optimal solution of the original problem
  from different directions, and 2) it only needs to build local surrogates so that
  the computational overhead of the model building can be reduced. Numerical experiments
  demonstrate that our proposed algorithm performs much better than some other state-of-the-art
  evolutionary algorithms.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Buildings
- Computational modeling
- Expensive constrained optimization
- Linear programming
- multiple local surrogates.
- multiple penalty functions
- Optimization
- Search problems
- Sociology
- Statistics

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
