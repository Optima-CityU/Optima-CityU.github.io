---
title: A Multiobjective Evolutionary Algorithm for Network Planning in In-Building
  Distributed Antenna Systems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pei-Qiu Huang
- Shaoda Zeng
- Xilei Wu
- Hai-Lin Liu
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.302967Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Network Science and Engineering*'
publication_short: ''

doi: 10.1109/TNSE.2024.3356652

abstract: Deploying in-building distributed antenna systems (IB-DAS) is a crucial
  step towards providing ubiquitous wireless services. In this paper, we study the
  multiobjective network planning problem, aiming to minimize both construction costs
  and average power loss. The main challenge in solving this problem is efficiently
  representing the network structure. To address this, we encode the network structure
  as a spanning tree, with the root node connecting to the signal source, and leaf
  and non-leaf nodes representing all floors and power devices, respectively. Compared
  to existing encodings, this tree encoding offers several advantages, including improved
  locality and the ability to easily generate valid solutions. Additionally, we propose
  a tree-encoded evolutionary algorithm called TMOEA. Since the standard operators
  cannot be applied, we devise problem-specific crossover and mutation operators to
  produce tree-encoded solutions. Moreover, the Tchebycheff approach is employed to
  update solutions. Comprehensive experiments on 11 test instances with up to 30 floors
  demonstrate that the proposed algorithm outperforms four compared algorithms in
  terms of both the hypervolume indicator and the inverted generational distance indicator
  for each test instance. © 2013 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- In-building distributed antenna system (IB-DAS)
- network planning
- multiobjective optimization
- evolutionary algorithm
- encoding

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
