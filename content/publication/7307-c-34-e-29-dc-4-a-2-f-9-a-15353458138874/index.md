---
title: Choose Appropriate Subproblems for Collaborative Modeling in Expensive Multiobjective
  Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenkun Wang
- Qingfu Zhang
- Yew-Soon Ong
- Shunyu Yao
- Haitao Liu
- Jianping Luo

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.446769Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2021.3126341

abstract: In dealing with the expensive multiobjective optimization problem, some
  algorithms convert it into a number of single-objective subproblems for optimization.
  At each iteration, these algorithms conduct surrogate-assisted optimization on one
  or multiple subproblems. However, these subproblems may be unnecessary or resolved.
  Operating on such subproblems can cause server inefficiencies, especially in the
  case of expensive optimization. To overcome this shortcoming, we propose an adaptive
  subproblem selection (ASS) strategy to identify the most promising subproblems for
  further modeling. To better leverage the cross information between the subproblems,
  we use the collaborative multioutput Gaussian process surrogate to model them jointly.
  Moreover, the commonly used acquisition functions (also known as infill criteria)
  are investigated in this article. Our analysis reveals that these acquisition functions
  may cause severe imbalances between exploitation and exploration in multiobjective
  optimization scenarios. Consequently, we develop a new acquisition function, namely,
  adaptive lower confidence bound (ALCB), to cope with it. The experimental results
  on three different sets of benchmark problems indicate that our proposed algorithm
  is competitive. Beyond that, we also quantitatively validate the effectiveness of
  the ASS strategy, the CoMOGP model, and the ALCB acquisition function.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Optimization
- Predictive models
- Computational modeling
- Training
- Linear programming
- Gaussian processes
- Computer science
- Adaptive lower confidence bound (ALCB)
- expensive optimization
- multiobjective optimization
- multioutput Gaussian process (GP)
- subproblem selection
- EVOLUTIONARY ALGORITHMS
- FITNESS APPROXIMATION
- GAUSSIAN-PROCESSES
- SURROGATE MODEL
- MOEA/D

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
