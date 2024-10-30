---
title: Pareto Set Learning for Expensive Multi-Objective Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xi Lin
- Zhiyuan Yang
- Xiaoyuan Zhang
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.340482Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*36th Conference on Neural Information Processing Systems (NeurIPS 2022)*'
publication_short: ''

doi: ''

abstract: Expensive multi-objective optimization problems can be found in many real-world
  applications, where their objective function evaluations involve expensive computations
  or physical experiments. It is desirable to obtain an approximate Pareto front with
  a limited evaluation budget. Multi-objective Bayesian optimization (MOBO) has been
  widely used for finding a finite set of Pareto optimal solutions. However, it is
  well-known that the whole Pareto set is on a continuous manifold and can contain
  infinite solutions. The structural properties of the Pareto set are not well exploited
  in existing MOBO methods, and the finite-set approximation may not contain the most
  preferred solution(s) for decision-makers. This paper develops a novel learning-based
  method to approximate the whole Pareto set for MOBO, which generalizes the decomposition-based
  multi-objective optimization algorithm (MOEA/D) from finite populations to models.
  We design a simple and powerful acquisition search method based on the learned Pareto
  set, which naturally supports batch evaluation. In addition, with our proposed model,
  decision-makers can readily explore any trade-off area in the approximate Pareto
  set for flexible decision-making. This work represents the first attempt to model
  the Pareto set for expensive multi-objective optimization. Experimental results
  on different synthetic and real-world problems demonstrate the effectiveness of
  our proposed method. © 2022 Neural Information Processing Systems Foundation. All
  rights reserved.

# Summary. An optional shortened abstract.
summary: ''

tags: []

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
links:
- name: URL
  url: https://neurips.cc/, https://nips.cc/Conferences/2022, https://proceedings.neurips.cc/paper_files/paper/2022
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
