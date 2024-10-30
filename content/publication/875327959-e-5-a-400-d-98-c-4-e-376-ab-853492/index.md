---
title: Decomposition-Based-Sorting and Angle-Based-Selection for Evolutionary Multiobjective
  and Many-Objective Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xinye Cai
- Zhixiang Yang
- Zhun Fan
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2017-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.452309Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2016.2586191

abstract: Multiobjective evolutionary algorithm based on decomposition (MOEA/D) decomposes
  a multiobjective optimization problem (MOP) into a number of scalar optimization
  subproblems and then solves them in parallel. In many MOEA/D variants, each subproblem
  is associated with one and only one solution. An underlying assumption is that each
  subproblem has a different Pareto-optimal solution, which may not be held, for irregular
  Pareto fronts (PFs), e.g., disconnected and degenerate ones. In this paper, we propose
  a new variant of MOEA/D with sorting-and-selection (MOEA/D-SAS). Different from
  other selection schemes, the balance between convergence and diversity is achieved
  by two distinctive components, decomposition-based-sorting (DBS) and angle-based-selection
  (ABS). DBS only sorts L closest solutions to each subproblem to control the convergence
  and reduce the computational cost. The parameter L has been made adaptive based
  on the evolutionary process. ABS takes use of angle information between solutions
  in the objective space to maintain a more fine-grained diversity. In MOEA/D-SAS,
  different solutions can be associated with the same subproblems; and some subproblems
  are allowed to have no associated solution, more flexible to MOPs or many-objective
  optimization problems (MaOPs) with different shapes of PFs. Comprehensive experimental
  studies have shown that MOEA/D-SAS outperforms other approaches; and is especially
  effective on MOPs or MaOPs with irregular PFs. Moreover, the computational efficiency
  of DBS and the effects of ABS in MOEA/D-SAS are also investigated and discussed
  in detail.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Angle-based-selection (ABS)
- decomposition-based-sorting (DBS)
- diversity
- evolutionary multiobjective optimization
- many-objective optimization

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
