---
title: Multi-View Spectral Clustering Tailored Tensor Low-Rank Representation

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yuheng Jia
- Hui Liu
- Junhui Hou
- Sam Kwong
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.586602Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Circuits and Systems for Video Technology*'
publication_short: ''

doi: 10.1109/TCSVT.2021.3055039

abstract: This paper explores the problem of multi-view spectral clustering (MVSC)
  based on tensor low-rank modeling. Unlike the existing methods that all adopt an
  off-the-shelf tensor low-rank norm without considering the special characteristics
  of the tensor in MVSC, we design a novel structured tensor low-rank norm tailored
  to MVSC. Specifically, we explicitly impose a symmetric low-rank constraint and
  a structured sparse low-rank constraint on the frontal and horizontal slices of
  the tensor to characterize the intra-view and inter-view relationships, respectively.
  Moreover, the two constraints could be jointly optimized to achieve mutual refinement.
  On basis of the novel tensor low-rank norm, we formulate MVSC as a convex low-rank
  tensor recovery problem, which is then efficiently solved with an augmented Lagrange
  multiplier-based method iteratively. Extensive experimental results on seven commonly
  used benchmark datasets show that the proposed method outperforms state-of-the-art
  methods to a significant extent. Impressively, our method is able to produce perfect
  clustering. In addition, the parameters of our method can be easily tuned, and the
  proposed model is robust to different datasets, demonstrating its potential in practice.
  The code is available at https://github.com/jyh-learning/MVSC-TLRR.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Multi-view spectral clustering
- tensor low-rank representation
- tensor low-rank norm

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
