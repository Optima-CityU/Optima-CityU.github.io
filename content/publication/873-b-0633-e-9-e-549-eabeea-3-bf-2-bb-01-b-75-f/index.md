---
title: Approximating robust Pareto fronts by the MEOF-based multiobjective evolutionary
  algorithm with two-level surrogate models

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yuxiang Shui
- Hui Li
- Jianyong Sun
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.471415Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Information Sciences*'
publication_short: ''

doi: 10.1016/j.ins.2023.119946

abstract: The multiobjective optimization problems (MOPs) under uncertain environments
  are very challenging to be solved due to the sensitivities of some robust decision
  variables. To find the robust Pareto fronts (PFs) of these MOPs, the mean effective
  objective function (MEOF) is often used for evaluating the qualities of solutions
  in the existing evolutionary multiobjective optimization (EMO) algorithms. In the
  MEOF evaluation, the objective function values of multiple solutions in the neighborhood
  of a certain solution should be averaged. As a result, the MEOF-based EMO algorithms
  consume a large number of function evaluations to find robust PFs with high qualities.
  To overcome this weakness, we propose a new MEOF-based EMO framework with two-level
  surrogate models, denoted by EMO-MEOF/TS, which utilizes radial basis function and
  Gaussian process model to predict high-quality robust solutions at the levels of
  global search and local search. Some experiments are conducted to evaluate the performance
  of the proposed framework on some modified MOPs with robust decision variables.
  Our experimental results demonstrate that EMO-MEOF/TS is advantageous against several
  robust MOEAs in approximating the PFs of MOPs with robust characteristics. © 2023
  Elsevier Inc.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Evolutionary algorithm
- Mean effective objective function
- Robust multiobjective optimization
- Surrogate model

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
