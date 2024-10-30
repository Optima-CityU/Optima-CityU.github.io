---
title: 'Neural Combinatorial Optimization with Heavy Decoder: Toward Large Scale Generalization'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Fu Luo
- Xi Lin
- Fei Liu
- Qingfu Zhang
- Zhenkun Wang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.029501Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Advances in Neural Information Processing Systems 36 (NeurIPS 2023)*'
publication_short: ''

doi: ''

abstract: Neural combinatorial optimization (NCO) is a promising learning-based approach
  for solving challenging combinatorial optimization problems without specialized
  algorithm design by experts. However, most constructive NCO methods cannot solve
  problems with large-scale instance sizes, which significantly diminishes their usefulness
  for real-world applications. In this work, we propose a novel Light Encoder and
  Heavy Decoder (LEHD) model with a strong generalization ability to address this
  critical issue. The LEHD model can learn to dynamically capture the relationships
  between all available nodes of varying sizes, which is beneficial for model generalization
  to problems of various scales. Moreover, we develop a data-efficient training scheme
  and a flexible solution construction mechanism for the proposed LEHD model. By training
  on small-scale problem instances, the LEHD model can generate nearly optimal solutions
  for the Travelling Salesman Problem (TSP) and the Capacitated Vehicle Routing Problem
  (CVRP) with up to 1000 nodes, and also generalizes well to solve real-world TSPLib
  and CVRPLib problems. These results confirm our proposed LEHD model can significantly
  improve the state-of-the-art performance for constructive NCO. The code is available
  at https://github.com/CIAM-Group/NCO_code/tree/main/single_objective/LEHD. © 2023
  Neural information processing systems foundation.

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
  url: https://papers.nips.cc/paper_files/paper/2023, https://nips.cc/Conferences/2023
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
