---
title: Incorporating structural constraints into continuous optimization for causal
  discovery

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zidong Wang
- Xiaoguang Gao
- Xiaohan Liu
- Xinxin Ru
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.041163Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Neurocomputing*'
publication_short: ''

doi: 10.1016/j.neucom.2024.127902

abstract: Directed Acyclic Graphs (DAGs) provide an efficient framework to describe
  the causal relations in actual applications, and it appears more and more important
  to learn a DAG from training data in causal discovery. Recently, a novel methodology,
  which projects the acyclic constraints by an algebraic characterization and employs
  continuous optimization to carry the causal discovery, gradually became the mainstream.
  However, such methods focus on a best-fitting to the training data and cannot utilize
  the prior knowledge in an efficient way. To resolve this problem, we suggest incorporating
  structural constraints into continuous optimization. For edge constraints, we regard
  the activation value of the difference between the constraint matrix after thresholding
  and the weight matrix as the optimization goal. For path constraints, we use the
  deviation concluded from the power matrix on kth path graphs to design the penalty
  functions. For ordering constraints, we exploit the representation based on the
  negative edge/path constraints. The mathematical derivations prove that equality
  constraint program (ECP), in which proposed equality constraints powerfully embody
  the required structural restrictions, are solvable. Furthermore, the experimental
  evaluations indicate that the proposed method develops higher scalability and accuracy
  against state-of-the-art algorithms. © 2024 Elsevier B.V.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Causal discovery
- Constraints
- Continuous optimization
- Directed acyclic graphs

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
