---
title: Adaptive operator selection with bandits for a multiobjective evolutionary
  algorithm based on decomposition

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Ke Li
- Alvaro Fialho
- Sam Kwong
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2014-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.736449Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2013.2239648

abstract: Adaptive operator selection (AOS) is used to determine the application rates
  of different operators in an online manner based on their recent performances within
  an optimization process. This paper proposes a bandit-based AOS method, fitness-rate-rank-based
  multiarmed bandit (FRRMAB). In order to track the dynamics of the search process,
  it uses a sliding window to record the recent fitness improvement rates achieved
  by the operators, while employing a decaying mechanism to increase the selection
  probability of the best operator. Not much work has been done on AOS in multiobjective
  evolutionary computation since it is very difficult to measure the fitness improvements
  quantitatively in most Pareto-dominance-based multiobjective evolutionary algorithms.
  Multiobjective evolutionary algorithm based on decomposition (MOEA/D) decomposes
  a multiobjective optimization problem into a number of scalar optimization subproblems
  and optimizes them simultaneously. Thus, it is natural and feasible to use AOS in
  MOEA/D. We investigate several important issues in using FRRMAB in MOEA/D. Our experimental
  results demonstrate that FRRMAB is robust and its operator selection is reasonable.
  Comparison experiments also indicate that FRRMAB can significantly improve the performance
  of MOEA/D. © 2013 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Adaptive operator selection (AOS)
- decomposition
- multiarmed bandit
- multiobjective evolutionary algorithm based on decomposition (MOEA/D)
- multiobjective optimization

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
