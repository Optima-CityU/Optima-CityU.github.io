---
title: Cooperative Multiobjective Evolutionary Algorithm With Propulsive Population
  for Constrained Multiobjective Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jiahai Wang
- Yanyue Li
- Qingfu Zhang
- Zizhen Zhang
- Shangce Gao

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.543799Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Systems, Man, and Cybernetics: Systems*'
publication_short: ''

doi: 10.1109/TSMC.2021.3069986

abstract: Convergence, diversity and feasibility are three important issues when solving
  constrained multiobjective optimization problems (CMOPs). To deal with the balance
  among convergence, diversity and feasibility well, this article proposes a cooperative
  multiobjective evolutionary algorithm with propulsive population (CMOEA-PP) for
  solving CMOPs. CMOEA-PP has two populations, including propulsive population and
  normal population, and these two populations work cooperatively. Specifically, propulsive
  population focuses on convergence. Normal population gives priority to feasibility
  and is obligated to maintain diversity. To cross through the infeasible region and
  reach the Pareto front (PF), propulsive population does not consider constraints
  in the early stage and only considers constraints in the later stage. To further
  accelerate the speed of convergence, propulsive population only searches for corner
  solutions and center solutions, while normal population searches for the whole PF.
  As a result, propulsive population can cross through the infeasible region because
  of the lack of attention to feasibility. In addition, propulsive population also
  can guide and accelerate the convergence of the evolutionary process. Comprehensive
  experiment results on several sets of benchmark problems demonstrate that CMOEA-PP
  is better than existing state-of-the-art competitors.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer science
- Constrained multiobjective optimization
- constraint handling
- Convergence
- cooperative populations
- Linear programming
- Maintenance engineering
- Optimization
- propulsive population
- Sociology
- Statistics

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
