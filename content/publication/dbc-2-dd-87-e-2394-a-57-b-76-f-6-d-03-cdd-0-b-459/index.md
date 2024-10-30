---
title: Pareto Set Learning for Neural Multi-Objective Combinatorial Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xi Lin
- Zhiyuan Yang
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.350690Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*ICLR 2022 - 10th International Conference on Learning Representations*'
publication_short: ''

doi: ''

abstract: Multiobjective combinatorial optimization (MOCO) problems can be found in
  many real-world applications. However, exactly solving these problems would be very
  challenging, particularly when they are NP-hard. Many handcrafted heuristic methods
  have been proposed to tackle different MOCO problems over the past decades. In this
  work, we generalize the idea of neural combinatorial optimization, and develop a
  learning-based approach to approximate the whole Pareto set for a given MOCO problem
  without further search procedure. We propose a single preference-conditioned model
  to directly generate approximate Pareto solutions for any trade-off preference,
  and design an efficient multiobjective reinforcement learning algorithm to train
  this model. Our proposed method can be treated as a learning-based extension for
  the widely-used decomposition-based multiobjective evolutionary algorithm (MOEA/D).
  It uses a single model to accommodate all the possible preferences, whereas other
  methods use a finite number of solutions to approximate the Pareto set. Experimental
  results show that our proposed method significantly outperforms some other methods
  on the multiobjective traveling salesman problem, multiobjective vehicle routing
  problem, and multiobjective knapsack problem in terms of solution quality, speed,
  and model efficiency. © 2022 ICLR 2022 - 10th International Conference on Learning
  Representationss. All rights reserved.

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
  url: https://iclr.cc/Conferences/2022, https://openreview.net/group?id=ICLR.cc/2022
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
