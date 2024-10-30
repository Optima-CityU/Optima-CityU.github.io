---
title: Hybridization of decomposition and local search for multiobjective optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Liangjun Ke
- Qingfu Zhang
- Roberto Battiti

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2014-10-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.153348Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2013.2295886

abstract: 'Combining ideas from evolutionary algorithms, decomposition approaches,
  and Pareto local search, this paper suggests a simple yet efficient memetic algorithm
  for combinatorial multiobjective optimization problems: memetic algorithm based
  on decomposition (MOMAD). It decomposes a combinatorial multiobjective problem into
  a number of single objective optimization problems using an aggregation method.
  MOMAD evolves three populations: 1) population PLfor recording the current solution
  to each subproblem; 2) population PPfor storing starting solutions for Pareto local
  search; and 3) an external population PEfor maintaining all the nondominated solutions
  found so far during the search. A problem-specific single objective heuristic can
  be applied to these subproblems to initialize the three populations. At each generation,
  a Pareto local search method is first applied to search a neighborhood of each solution
  in PPto update PLand PE. Then a single objective local search is applied to each
  perturbed solution in PLfor improving PLand PE, and reinitializing PP. The procedure
  is repeated until a stopping condition is met. MOMAD provides a generic hybrid multiobjective
  algorithmic framework in which problem specific knowledge, well developed single
  objective local search and heuristics and Pareto local search methods can be hybridized.
  It is a population based iterative method and thus an anytime algorithm. Extensive
  experiments have been conducted in this paper to study MOMAD and compare it with
  some other state-of-the-art algorithms on the multiobjective traveling salesman
  problem and the multiobjective knapsack problem. The experimental results show that
  our proposed algorithm outperforms or performs similarly to the best so far heuristics
  on these two problems.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Decomposition
- local search
- multiobjective knapsack problem
- multiobjective optimization
- multiobjective traveling salesman problem

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
