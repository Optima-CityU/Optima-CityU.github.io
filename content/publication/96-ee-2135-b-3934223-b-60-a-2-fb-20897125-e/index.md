---
title: Decomposition-based algorithms using pareto adaptive scalarizing methods

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Rui Wang
- Qingfu Zhang
- Tao Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2016-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.425652Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2016.2521175

abstract: Decomposition-based algorithms have become increasingly popular for evolutionary
  multiobjective optimization. However, the effect of scalarizing methods used in
  these algorithms is still far from being well understood. This paper analyzes a
  family of frequently used scalarizing methods, the Lp methods, and shows that the
  p value is crucial to balance the selective pressure toward the Pareto optimal and
  the algorithm robustness to Pareto optimal front (PF) geometries. It demonstrates
  that an Lp method that can maximize the search ability of a decomposition-based
  algorithm exists and guarantees that, given some weight, any solution along the
  PF can be found. Moreover, a simple yet effective method called Pareto adaptive
  scalarizing (PaS) approximation is proposed to approximate the optimal p value.
  In order to demonstrate the effectiveness of PaS, we incorporate PaS into a state-of-the-art
  decomposition-based algorithm, i.e., multiobjective evolutionary algorithm based
  on decomposition (MOEA/D), and compare the resultant MOEA/D-PaS with some other
  MOEA/D variants on a set of problems with different PF geometries and up to seven
  conflicting objectives. Experimental results demonstrate that the PaS is effective.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Decomposition
- evolutionary computation
- multiobjective evolutionary algorithm based on decomposition (MOEA/D)
- multiobjective optimization
- scalarizing method

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
