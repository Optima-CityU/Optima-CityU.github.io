---
title: A Grid Weighted Sum Pareto Local Search for Combinatorial Multi and Many-Objective
  Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xinye Cai
- Haoran Sun
- Qingfu Zhang
- Yuhua Huang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.888172Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2018.2849403

abstract: Combinatorial multiobjective optimization problems (CMOPs) are very popular
  due to their widespread applications in the real world. One common method for CMOPs
  is Pareto local search (PLS), a natural extension of single-objective local search
  (LS). However, classical PLS tends to reserve all of the nondominated solutions
  for LS, which causes the inefficient LS, as well as unbearable computational and
  space cost. Due to the aforementioned reasons, most PLS approaches can only handle
  CMOPs with no more than two objectives. In this paper, by combining the Pareto dominance
  and weighted sum (WS) approach in a grid system, the grid weighted sum dominance
  (gws-dominance) is proposed and integrated into PLS for CMOPs with multiple objectives.
  In the grid system, at most one representative solution is maintained in each grid
  for more efficient LS, thus largely reducing the computational and space complexity.
  The grid-based WS approach can further guide the LS in different grids for maintaining
  more widely and uniformly distributed Pareto front approximations. In the experimental
  studies, the grid WS PLS is compared with the classical PLS, three decomposition-based
  LS approaches [multiobjective evolutionary algorithm based on decomposition-LS (WS,
  Tchebycheff, and penalty-based boundary intersection)], a grid-based algorithm (ε-MOEA),
  and a state-of-the-art hybrid approach (multiobjective memetic algorithm based on
  decomposition) on two sets of benchmark CMOPs. The experimental results show that
  the grid weighted sum Pareto local search significantly outperforms the compared
  algorithms and remains effective and efficient on combinatorial multiobjective and
  even many-objective optimization problems.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Combinatorial many-objective optimization
- combinatorial multiobjective optimization
- grid weighted sum dominance (gws-dominance)
- Pareto local search (PLS)

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
