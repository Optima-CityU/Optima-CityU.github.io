---
title: Multiobjective Combinatorial Optimization Using a Single Deep Reinforcement
  Learning Model

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenkun Wang
- Shunyu Yao
- Genghui Li
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.021459Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2023.3312476

abstract: This article proposes utilizing a single deep reinforcement learning model
  to solve combinatorial multiobjective optimization problems. We use the well-known
  multiobjective traveling salesman problem (MOTSP) as an example. Our proposed method
  employs an encoder-decoder framework to learn the mapping from the MOTSP instance
  to its Pareto-optimal set. Specifically, it leverages a novel routing encoder to
  extract information for both the entire multiobjective aspect and every individual
  objective from the MOTSP instance. The global embeddings and each objectivetextquoterights
  embeddings are adaptively aggregated via a routing network to form the subproblemstextquoteright
  embedding that can well represent the MOTSP features. Using a modified context embedding,
  the subproblemstextquoteright embeddings are fed into a decoder to produce a set
  of approximate Pareto-optimal solutions in parallel. Additionally, we develop a
  Top-k baseline to enable more efficient data utilization and lightweight training
  for our proposed method. We compare our method with heuristic-based and learning-based
  ones on various types of MOTSP instances, and the experimental results show that
  our method can solve MOTSP instances in real-time and outperform the other algorithms,
  especially on large-scale problem instances. © 2023 IEEE

# Summary. An optional shortened abstract.
summary: ''

tags:
- Approximation algorithms
- Attention mechanism
- combinatorial optimization (CO)
- Decoding
- deep reinforcement learning
- Heuristic algorithms
- multiobjective optimization
- Optimization
- Routing
- routing network
- Training
- traveling salesman problem
- Urban areas

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
