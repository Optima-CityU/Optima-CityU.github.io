---
title: On the use of random weights in MOEA/D

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hui Li
- Min Ding
- Jingda Deng
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2015-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.350690Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2015 IEEE Congress on Evolutionary Computation, CEC 2015 - Proceedings*'
publication_short: ''

doi: 10.1109/CEC.2015.7256996

abstract: MOEA/D is a decomposition-based multiobjective evolutionary algorithm that
  has attracted much attention in recent years. Its performance depends on the setting
  of weight vectors which are used for defining subproblems. In the case of irregular
  Pareto fronts (e.g, disconnected or degenerated), fixed setting of weight vectors
  in MOEA/D may not work well. In this paper, we propose an improved MOEA/D with both
  random and fixed weight vectors. Moreover, an external archive based on a modified
  ϵ-dominance strategy is used for storing nondominated solutions found by the proposed
  algorithm and assisting the generation of random weight vectors. Some experiments
  have been conducted to verify the efficiency and effectiveness of the improved MOEA/D
  on benchmark multiobjective test problems with irregular Pareto fronts. The experimental
  results show that the overall performance of the proposed algorithm is better than
  baseline MOEA/D and NSGA-II.

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
