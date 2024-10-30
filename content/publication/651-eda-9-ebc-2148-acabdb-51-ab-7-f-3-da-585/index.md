---
title: Biased Multiobjective Optimization and Decomposition Algorithm

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hui Li
- Qingfu Zhang
- Jingda Deng

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2017-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.981277Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2015.2507366

abstract: The bias feature is a major factor that makes a multiobjective optimization
  problem (MOP) difficult for multiobjective evolutionary algorithms (MOEAs). To deal
  with this problem feature, an algorithm should carefully balance between exploration
  and exploitation. The decomposition-based MOEA decomposes an MOP into a number of
  single objective subproblems and solves them in a collaborative manner. Single objective
  optimizers can be easily used in this algorithm framework. Covariance matrix adaptation
  evolution strategy (CMA-ES) has proven to be able to strike good balance between
  the exploration and the exploitation of search space. This paper proposes a scheme
  to use both differential evolution (DE) and covariance matrix adaptation in the
  MOEA based on decomposition. In this scheme, single objective optimization problems
  are clustered into several groups. To reduce the computational overhead, only one
  subproblem from each group is selected to optimize by CMA-ES while other subproblems
  are optimized by DE. When an evolution strategy procedure meets some stopping criteria,
  it will be reinitialized and used for solving another subproblem in the same group.
  A set of new multiobjective test problems with bias features are constructed in
  this paper. Extensive experimental studies show that our proposed algorithm is suitable
  for dealing with problems with biases.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Bias feature
- covariance matrix adaptation evolution strategy (CMA-ES)
- decomposition
- multiobjective evolutionary algorithms (MOEAs)

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
