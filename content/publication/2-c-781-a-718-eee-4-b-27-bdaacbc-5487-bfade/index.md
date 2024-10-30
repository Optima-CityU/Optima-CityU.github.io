---
title: Multi-objectivization inspired metaheuristics for the sum-of-the-parts combinatorial
  optimization problems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jialong Shi
- Jianyong Sun
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.750572Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Applied Soft Computing*'
publication_short: ''

doi: 10.1016/j.asoc.2021.107157

abstract: Multi-objectivization is a term used to describe strategies developed for
  optimizing single-objective problems by multi-objective algorithms. This paper focuses
  on multi-objectivizing the sum-of-the-parts combinatorial optimization problems,
  which include the traveling salesman problem, the unconstrained binary quadratic
  programming and other well-known combinatorial optimization problem. For a sum-of-the-parts
  combinatorial optimization problem, we propose to decompose its original objective
  into two sub-objectives with controllable correlation. Based on the decomposition
  method, two new multi-objectivization inspired single-objective optimization techniques
  called non-dominance search and non-dominance exploitation are developed, respectively.
  Non-dominance search is combined with two metaheuristics, namely iterated local
  search and iterated tabu search, while non-dominance exploitation is embedded within
  the iterated Lin–Kernighan metaheuristic. The resultant metaheuristics are called
  ILS+NDS, ITS+NDS and ILK+NDE, respectively. Empirical studies on some TSP and UBQP
  instances show that with appropriate correlation between the sub-objectives, there
  are more chances to escape from local optima when new starting solution is selected
  from the non-dominated solutions defined by the decomposed sub-objectives. Experimental
  results also show that ILS+NDS, ITS+NDS and ILK+NDE all significantly outperform
  their counterparts on most of the test instances.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Combinatorial optimization
- Local search
- Multi-objectivization
- Traveling salesman problem

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
