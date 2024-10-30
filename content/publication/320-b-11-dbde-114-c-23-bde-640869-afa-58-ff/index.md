---
title: Graph Neural Network Encoding for Community Detection in Attribute Networks

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jianyong Sun
- Wei Zheng
- Qingfu Zhang
- Zongben Xu

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.846013Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2021.3051021

abstract: In this article, we first propose a graph neural network encoding method
  for the multiobjective evolutionary algorithm (MOEA) to handle the community detection
  problem in complex attribute networks. In the graph neural network encoding method,
  each edge in an attribute network is associated with a continuous variable. Through
  nonlinear transformation, a continuous valued vector (i.e., a concatenation of the
  continuous variables associated with the edges) is transferred to a discrete valued
  community grouping solution. Further, two objective functions for the single-attribute
  and multiattribute network are proposed to evaluate the attribute homogeneity of
  the nodes in communities, respectively. Based on the new encoding method and the
  two objectives, a MOEA based upon NSGA-II, called continuous encoding MOEA, is developed
  for the transformed community detection problem with continuous decision variables.
  Experimental results on single-attribute and multiattribute networks with different
  types show that the developed algorithm performs significantly better than some
  well-known evolutionary- and nonevolutionary-based algorithms. The fitness landscape
  analysis verifies that the transformed community detection problems have smoother
  landscapes than those of the original problems, which justifies the effectiveness
  of the proposed graph neural network encoding method.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Community detection
- complex attribute network
- Complex networks
- Encoding
- Genetic algorithms
- graph neural network encoding
- Graph neural networks
- Image edge detection
- multiobjective evolutionary algorithm (MOEA)
- Optimization
- Sun

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
