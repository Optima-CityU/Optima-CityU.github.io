---
title: Investigating the Properties of Indicators and an Evolutionary Many-Objective
  Algorithm Using Promising Regions

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jiawei Yuan
- Hai-Lin Liu
- Fangqing Gu
- Qingfu Zhang
- Zhaoshui He

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.334895Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2020.2999100

abstract: This article investigates the properties of ratio and difference-based indicators
  under the Minkovsky distance and demonstrates that a ratio-based indicator with
  infinite norm is the best for solution evaluation among these indicators. Accordingly,
  a promising-region-based evolutionary many-objective algorithm with the ratio-based
  indicator is proposed. In our proposed algorithm, a promising region is identified
  in the objective space using the ratio-based indicator with infinite norm. Since
  the individuals outside the promising region are of poor quality, we can discard
  these solutions from the current population. To ensure the diversity of population,
  a strategy based on the parallel distance is introduced to select individuals in
  the promising region. In this strategy, all individuals in the promising region
  are projected vertically onto the normal plane so that crowded distances between
  them can be calculated. Afterward, two solutions with a smaller distance are selected
  from the candidate solutions each time, and the solution with the smaller indicator
  fitness value is removed from the current population. Empirical studies on various
  benchmark problems with 3-20 objectives show that the proposed algorithm performs
  competitively on all test problems. Compared with a number of other state-of-The-Art
  evolutionary algorithms, the proposed algorithm is more robust on these problems
  with various Pareto fronts.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Evolutionary algorithm
- indicators
- many-objective optimization
- multiobjective optimization
- robustness

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
