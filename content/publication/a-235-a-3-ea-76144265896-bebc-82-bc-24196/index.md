---
title: An evolutionary multi-objective optimization framework of discretization-based
  feature selection for classification

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yu Zhou
- Junhao Kang
- Sam Kwong
- Xu Wang
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.398723Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Swarm and Evolutionary Computation*'
publication_short: ''

doi: 10.1016/j.swevo.2020.100770

abstract: Feature selection (FS) aims to identify the most relevant and non-redundant
  feature subset for improving the classification accuracy, which is regarded as a
  NP-hard problem. Some heuristic methods, such as particle swarm optimization (PSO)
  have achieved great success, however, with the increase of feature quantity, the
  solution space is too large, resulting in lower search efficiency. Recent discretization-based
  FS methods map the search of feature domain into cut-point domain, which shrinks
  the solution space and improve the performances significantly. In this paper, considering
  the conflicts between different objectives, we proposed an evolutionary multi-objective
  optimization framework for discretization-based FS. To obtain the Pareto solutions,
  a flexible cut-point PSO (FCPSO) which can select an arbitrary number of cut-points
  for discretization is introduced to help better explore the relevant features. In
  FCPSO, a particle update and a novel adaptive mutation operator are alternatively
  used to effectively find the relevant features and remove the redundant features.
  At last, to select the best feature subset, a Pareto ensemble method is designed
  to generate a number of feasible solutions based on Pareto set followed by a hierarchical
  solution selection process. We implemented the proposed framework by using three
  representative multi-objective evolutionary algorithms and compared them with some
  state-of-the-art methods. Experimental results on ten benchmark microarray gene
  datasets demonstrate that our proposed framework significantly outperforms other
  methods in terms of test classification accuracy with a competitive size of feature
  subset.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Discretization
- Evolutionary multi-objective algorithms
- Feature selection
- Pareto ensemble
- Particle swarm optimization
- Discretization
- Evolutionary multi-objective algorithms
- Feature selection
- Pareto ensemble
- Particle swarm optimization
- Discretization
- Evolutionary multi-objective algorithms
- Feature selection
- Pareto ensemble
- Particle swarm optimization

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
