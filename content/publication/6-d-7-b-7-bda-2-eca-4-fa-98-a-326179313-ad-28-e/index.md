---
title: A new learning-based adaptive multi-objective evolutionary algorithm

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jianyong Sun
- Hu Zhang
- Aimin Zhou
- Qingfu Zhang
- Ke Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.786968Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Swarm and Evolutionary Computation*'
publication_short: ''

doi: 10.1016/j.swevo.2018.04.009

abstract: In this paper, we propose an adaptive multi-objective evolutionary algorithm
  for multi-objective optimization problems (MOPs). In the algorithm, a clustering
  approach is employed to learn the Pareto optimal set's manifold structure adaptively,
  in accordance with the regularity property of MOPs, along the evolution. An advanced
  sampling strategy is developed for the generation of promising offspring from the
  learned structure. To generate trial solution, each non-dominated solution at present
  generation is Gaussian-perturbed using the variance-covariance matrix within its
  cluster. The other new features include 1) an adaptive hybridization of the developed
  sampling strategy with a differential evolution (DE) operator which aims to combine
  local and global information; 2) a reusing scheme which is to reduce the computational
  cost on modeling (clustering); and 3) an adaptive strength Pareto based approach
  which is to adaptively determine the contribution of the developed sampling strategy
  and the DE operator for balancing exploration and exploitation. The developed algorithm
  was empirically compared with four well-known MOEAs on a number of test instances
  with complex Pareto optimal set structure and complicated Pareto fronts. Experimental
  results suggest that it outperforms the compared algorithms on these test instances
  in terms of two commonly-used measure metrics. The effectiveness of the developed
  sampling strategy, the reusing scheme, the hybrid strategy, and the adaptive strategy
  was also empirically validated.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Adaptive control mechanism
- Hybrid recombination operator
- Multi-objective optimization

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
