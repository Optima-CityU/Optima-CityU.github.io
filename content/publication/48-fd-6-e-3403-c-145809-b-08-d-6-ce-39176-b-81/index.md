---
title: A Constrained Multiobjective Evolutionary Algorithm with Detect-and-Escape
  Strategy

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Qingling Zhu
- Qingfu Zhang
- Qiuzhen Lin

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-10-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.686778Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2020.2981949

abstract: 'Overall constraint violation functions are commonly used in multiobjective
  evolutionary algorithms for handling constraints. Constraints could cause these
  algorithms stuck in two stagnation states: (1) since the feasible region of a multiobjective
  optimization problem can consist of several disconnected feasible subregions, the
  search can be easily trapped in a feasible subregion which does not contain all
  the global Pareto optimal solutions; and (2) an overall constraint violation function
  may have many non-zero minimal points, it can make the search stuck in an unfeasible
  area. To address these two issues, this paper proposes a strategy to detect whether
  or not the search is stuck in these two stagnation states and then escape from them.
  Our proposed detect-and-escape strategy uses the feasible ratio and the change rate
  of overall constraint violation to detect stagnation, and adjusts the weight of
  the constraint violation for guiding the search to escape from stagnation states.
  We develop and implement a decomposition-based constrained multiobjective evolutionary
  algorithm with this strategy. Extensive experiments on a number of benchmark problems
  demonstrate the competitiveness of our proposed algorithm when compared to five
  other state-of-the-art constrained evolutionary algorithms.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Constraint handling technique
- MOEA/D
- Multiobjective optimization.

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
