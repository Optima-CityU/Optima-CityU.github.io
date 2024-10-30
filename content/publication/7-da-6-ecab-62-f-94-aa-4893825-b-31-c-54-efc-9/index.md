---
title: Accelerate the optimization of large-scale manufacturing planning using game
  theory

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hui-Ling Zhen
- Zhenkun Wang
- Xijun Li
- Qingfu Zhang
- Mingxuan Yuan
- Jia Zeng

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.991087Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Complex & Intelligent Systems*'
publication_short: ''

doi: 10.1007/s40747-021-00352-7

abstract: This paper studies a real-world manufacturing problem, which is modeled
  as a bi-objective integer programming problem. The variables and constraints involved
  are usually numerous and dramatically vary according to the manufacturing data.
  It is very challenging to directly solve such large-scale problems using heuristic
  algorithms or commercial solvers. Considering that the decision space of such problems
  is usually sparse and has a block-like structure, we propose to use decomposition
  methods to accelerate the optimization process. However, the existing decomposition
  methods require that the problem has strict block structures, which is not suitable
  for our problem. To deal with problems with such block-like structures, we propose
  a game theory based decomposition algorithm. This new method can overcome the large-scale
  issue and guarantee convergence to some extent, as it can narrow down the search
  space and accelerate the convergence. Extensive experimental results on real-world
  industrial manufacturing planning problems show that our method is more effective
  than the world fastest commercial solver Gurobi. The results also indicate that
  our method is less sensitive to the problem scale comparing with Gurobi.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Large-scale optimization
- Game theory
- Decomposition

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
