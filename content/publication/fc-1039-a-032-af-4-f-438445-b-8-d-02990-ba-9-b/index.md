---
title: New techniques to improve neighborhood exploration in pareto local search

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yuhao Kang
- Jialong Shi
- Jianyong Sun
- Qingfu Zhang
- Ye Fan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.490223Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Expert Systems with Applications*'
publication_short: ''

doi: 10.1016/j.eswa.2024.124296

abstract: Pareto Local Search (PLS) is an extension of local search to multiobjective
  combinatorial optimization problems (MCOPs). It is widely used as a building block
  in many multiobjective metaheuristics. However, it suffers from poor anytime behavior
  and long convergence time. In this paper, we focus on improving the neighborhood
  exploration mechanism to accelerate PLS. In total, we propose three new search strategies,
  namely, Promising List, Don't Look Bits and Continuing Search and implement them
  on the multiobjective Traveling Salesman Problem (mTSP) and the multiobjective Unconstrained
  Binary Quadratic Programming (mUBQP) problem. In Promising List, features of problem
  structure are utilized to guide the local search. In Don't Look Bits, neighborhood
  moves that are less promising to produce improving solutions are skipped. In Continuing
  Search, the agent will start from where previous neighborhood exploration stops
  to avoid repetitive neighborhood moves. The experimental results verify the effectiveness
  of the three techniques both individually and collaboratively on most of the test
  instances. Besides, one proposed PLS variant outperforms two state-of-the-art PLS-based
  algorithms. © 2024 Elsevier Ltd.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Metaheuristics
- Multiobjective combinatorial optimization problem
- Neighborhood exploration mechanism
- Pareto local search

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
