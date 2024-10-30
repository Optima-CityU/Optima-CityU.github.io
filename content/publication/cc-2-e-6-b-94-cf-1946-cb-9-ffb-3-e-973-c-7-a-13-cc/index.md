---
title: Learning Multi-Task Sparse Representation Based on Fisher Information

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yayu Zhang
- Yuhua Qian
- Guoshuai Ma
- Keyin Zheng
- Guoqing Liu
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.307376Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence*'
publication_short: ''

doi: 10.1609/aaai.v38i15.29632

abstract: Multi-task learning deals with multiple related tasks simultaneously by
  sharing knowledge. In a typical deep multitask learning model, all tasks use the
  same feature space and share the latent knowledge. If the tasks are weakly correlated
  or some features are negatively correlated, sharing all knowledge often leads to
  negative knowledge transfer among. To overcome this issue, this paper proposes a
  Fisher sparse multi-task learning method. It can obtain a sparse sharing representation
  for each task. In such a way, tasks share features on a sparse subspace. Our method
  can ensure that the knowledge transferred among tasks is beneficial. Specifically,
  we first propose a sparse deep multi-task learning model, and then introduce Fisher
  sparse module into traditional deep multi-task learning to learn the sparse variables
  of task. By alternately updating the neural network parameters and sparse variables,
  a sparse sharing representation can be learned for each task. In addition, in order
  to reduce the computational overhead, an heuristic method is used to estimate the
  Fisher information of neural network parameters. Experimental results show that,
  comparing with other methods, our proposed method can improve the performance for
  all tasks, and has high sparsity in multi-task learning. Copyright © 2024, Association
  for the Advancement of Artificial Intelligence (www.aaai.org). All rights reserved.

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
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
