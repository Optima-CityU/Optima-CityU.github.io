---
title: Improving Pareto Local Search Using Cooperative Parallelism Strategies for
  Multiobjective Combinatorial Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jialong Shi
- Jianyong Sun
- Qingfu Zhang
- Haotian Zhang
- Ye Fan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.446769Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2022.3226744

abstract: Pareto local search (PLS) is a natural extension of local search for multiobjective
  combinatorial optimization problems (MCOPs). In our previous work, we improved the
  anytime performance of PLS using parallel computing techniques and proposed a parallel
  PLS based on decomposition (PPLS/D). In PPLS/D, the solution space is searched by
  multiple independent parallel processes simultaneously. This article further improves
  PPLS/D by introducing two new cooperative process techniques, namely, a cooperative
  search mechanism and a cooperative subregion-adjusting strategy. In the cooperative
  search mechanism, the parallel processes share high-quality solutions with each
  other during the search according to a distributed topology. In the proposed subregion-adjusting
  strategy, a master process collects useful information from all processes during
  the search to approximate the Pareto front (PF) and redivide the subregions evenly.
  In the experimental studies, three well-known NP-hard MCOPs with up to six objectives
  were selected as test problems. The experimental results on the Tianhe-2 supercomputer
  verified the effectiveness of the proposed techniques.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Combinatorial optimization
- local search (LS)
- multiobjective optimization
- parallel metaheuristics
- Pareto LS (PLS)
- EVOLUTIONARY ALGORITHM
- DECOMPOSITION

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
