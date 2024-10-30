---
title: Continuous Encoding for Overlapping Community Detection in Attributed Network

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Wei Zheng
- Jianyong Sun
- Qingfu Zhang
- Zongben Xu

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.013201Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2022.3155646

abstract: Detecting overlapping communities of an attribute network is a ubiquitous
  yet very difficult task, which can be modeled as a discrete optimization problem.
  Besides the topological structure of the network, node attributes and node overlapping
  aggravate the difficulty of community detection significantly. In this article,
  we propose a novel continuous encoding method to convert the discrete-natured detection
  problem to a continuous one by associating each edge and node attribute in the network
  with a continuous variable. Based on the encoding, we propose to solve the converted
  continuous problem by a multiobjective evolutionary algorithm (MOEA) based on decomposition.
  To find the overlapping nodes, a heuristic based on double-decoding is proposed,
  which is only with linear complexity. Furthermore, a postprocess community merging
  method in consideration of node attributes is developed to enhance the homogeneity
  of nodes in the detected communities. Various synthetic and real-world networks
  are used to verify the effectiveness of the proposed approach. The experimental
  results show that the proposed approach performs significantly better than a variety
  of evolutionary and nonevolutionary methods on most of the benchmark networks.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Attribute network
- Complex networks
- continuous encoding method
- Decoding
- Encoding
- Image edge detection
- Measurement
- multiobjective evolutionary algorithm (MOEA)
- Optimization
- overlapping communities
- Peer-to-peer computing

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
