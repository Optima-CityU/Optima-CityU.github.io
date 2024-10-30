---
title: Push and pull search for solving constrained multi-objective optimization problems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhun Fan
- Wenji Li
- Xinye Cai
- Hui Li
- Caimin Wei
- Qingfu Zhang
- Kalyanmoy Deb
- Erik Goodman

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.638745Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Swarm and Evolutionary Computation*'
publication_short: ''

doi: 10.1016/j.swevo.2018.08.017

abstract: 'This paper proposes a push and pull search (PPS) framework for solving
  constrained multi-objective optimization problems (CMOPs). To be more specific,
  the proposed PPS divides the search process into two different stages: push and
  pull search stages. In the push stage, a multi-objective evolutionary algorithm
  (MOEA) is used to explore the search space without considering any constraints,
  which can help to get across infeasible regions very quickly and to approach the
  unconstrained Pareto front. Furthermore, the landscape of CMOPs with constraints
  can be probed and estimated in the push stage, which can be utilized to conduct
  the parameter setting for the constraint-handling approaches to be applied in the
  pull stage. Then, a modified form of a constrained multi-objective evolutionary
  algorithm (CMOEA), with improved epsilon constraint-handling, is applied to pull
  the infeasible individuals achieved in the push stage to the feasible and non-dominated
  regions. To evaluate the performance regarding convergence and diversity, a set
  of benchmark CMOPs and a real-world optimization problem are used to test the proposed
  PPS (PPS-MOEA/D) and state-of-the-art CMOEAs, including MOEA/D-IEpsilon, MOEA/D-Epsilon,
  MOEA/D-CDP, MOEA/D-SR, C-MOEA/D and NSGA-II-CDP. The comprehensive experimental
  results show that the proposed PPS-MOEA/D achieves significantly better performance
  than the other six CMOEAs on most of the tested problems, which indicates the superiority
  of the proposed PPS method for solving CMOPs.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Constrained multi-objective evolutionary algorithms
- Constraint-handling mechanisms
- Multiobjective evolutionary algorithm based on decomposition (MOEA/D)
- Push and pull search

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
