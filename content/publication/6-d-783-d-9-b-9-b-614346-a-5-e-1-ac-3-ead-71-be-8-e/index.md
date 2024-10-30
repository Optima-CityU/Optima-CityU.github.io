---
title: Clustering Ensemble Meets Low-rank Tensor Approximation

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yuheng Jia
- Hui Liu
- Junhui Hou
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.511750Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence*'
publication_short: ''

doi: ''

abstract: This paper explores the problem of clustering ensemble, which aims to combine
  multiple base clusterings to produce better performance than that of the individual
  one. The existing clustering ensemble methods generally construct a coassociation
  matrix, which indicates the pairwise similarity between samples, as the weighted
  linear combination of the connective matrices from different base clusterings, and
  the resulting co-association matrix is then adopted as the input of an off-the-shelf
  clustering algorithm, e.g., spectral clustering. However, the co-association matrix
  may be dominated by poor base clusterings, resulting in inferior performance. In
  this paper, we propose a novel low-rank tensor approximation based method to solve
  the problem from a global perspective. Specifically, by inspecting whether two samples
  are clustered to an identical cluster under different base clusterings, we derive
  a coherent-link matrix, which contains limited but highly reliable relationships
  between samples. We then stack the coherent-link matrix and the co-association matrix
  to form a three-dimensional tensor, the low-rankness property of which is further
  explored to propagate the information of the coherent-link matrix to the co-association
  matrix, producing a refined co-association matrix. We formulate the proposed method
  as a convex constrained optimization problem and solve it efficiently. Experimental
  results over 7 benchmark data sets show that the proposed model achieves a breakthrough
  in clustering performance, compared with 11 state-of-the-art methods. To the best
  of our knowledge, this is the first work to explore the potential of low-rank tensor
  on clustering ensemble, which is fundamentally different from previous approaches.
  Last but not least, our method only contains one parameter, which can be easily
  tuned.

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
  url: https://aaai.org/Conferences/AAAI-21/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
