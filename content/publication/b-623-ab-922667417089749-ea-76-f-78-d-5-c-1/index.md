---
title: A Constrained Decomposition Approach With Grids for Evolutionary Multiobjective
  Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xinye Cai
- Zhiwei Mei
- Zhun Fan
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2018-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.302967Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2017.2744674

abstract: Decomposition based multiobjective evolutionary algorithms (MOEAs) decompose
  a multiobjective optimization problem into a set of scalar objective subproblems
  and solve them in a collaborative way. Commonly used decomposition approaches originate
  from mathematical programming and the direct use of them may not suit MOEAs due
  to their population-based property. For instance, these decomposition approaches
  used in MOEAs may cause the loss of diversity and/or be very sensitive to the shapes
  of Pareto fronts (PFs). This paper proposes a constrained decomposition with grids
  (CDG) that can better address these two issues thus more suitable for MOEAs. In
  addition, different subproblems in CDG defined by the constrained decomposition
  constitute a grid system. The grids have an inherent property of reflecting the
  information of neighborhood structures among the solutions, which is a desirable
  property for restricted mating selection in MOEAs. Based on CDG, a constrained decomposition
  MOEA with grid (CDG-MOEA) is further proposed. Extensive experiments are conducted
  to compare CDG-MOEA with the domination-based, indicator-based and state-of-the-art
  decomposition-based MOEAs. The experimental results show that CDG-MOEA outperforms
  the compared algorithms in terms of both the convergence and diversity. More importantly,
  it is robust to the shapes of PFs and can still be very effective on MOPs with complex
  PFs (e.g., extremely convex, or with disparately scaled objectives).

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer science
- constrained decomposition
- Electronic mail
- Evolutionary multiobjective optimization
- grids
- Linear programming
- Pareto optimization
- robust to Pareto front (PF)
- Robustness
- Shape

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
