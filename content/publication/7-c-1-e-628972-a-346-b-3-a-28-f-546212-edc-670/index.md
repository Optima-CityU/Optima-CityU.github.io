---
title: Performance analysis of evolutionary algorithms for steiner tree problems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xinsheng Lai
- Yuren Zhou
- Xiaoyun Xia
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2017-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.622606Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Evolutionary Computation*'
publication_short: ''

doi: 10.1162/EVCO_a_00200

abstract: The Steiner tree problem (STP) aims to determine some Steiner nodes such
  that the minimum spanning tree over these Steiner nodes and a given set of special
  nodes has the minimum weight, which is NP-hard. STP includes several important cases.
  The Steiner tree problem in graphs (GSTP) is one of them. Many heuristics have been
  proposed for STP, and some of them have proved to be performance guarantee approximation
  algorithms for this problem. Since evolutionary algorithms (EAs) are general and
  popular randomized heuristics, it is significant to investigate the performance
  of EAs for STP. Several empirical investigations have shown that EAs are efficient
  for STP. However, up to now, there is no theoretical work on the performance of
  EAs for STP. In this article, we reveal that the (1+1) EA achieves 3/2-approximation
  ratio for STP in a special class of quasi-bipartite graphs in expected runtime O(r(r
  + s − 1) · wmax), where r, s, and wmax are, respectively, the number of Steiner
  nodes, the number of special nodes, and the largest weight among all edges in the
  input graph. We also show that the (1+1) EA is better than two other heuristics
  on two GSTP instances, and the (1+1) EA may be inefficient on a constructed GSTP
  instance.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Approximation ratio
- Computational complexity
- Evolutionary algorithms
- Multi-objective
- Steiner tree

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
