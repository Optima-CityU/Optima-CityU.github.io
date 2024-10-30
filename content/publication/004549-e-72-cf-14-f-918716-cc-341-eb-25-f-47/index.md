---
title: Semisupervised Affinity Matrix Learning via Dual-Channel Information Recovery

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

date: '2022-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.575662Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2020.3041493

abstract: This article explores the problem of semisupervised affinity matrix learning,
  that is, learning an affinity matrix of data samples under the supervision of a
  small number of pairwise constraints (PCs). By observing that both the matrix encoding
  PCs, called pairwise constraint matrix (PCM) and the empirically constructed affinity
  matrix (EAM), express the similarity between samples, we assume that both of them
  are generated from a latent affinity matrix (LAM) that can depict the ideal pairwise
  relation between samples. Specifically, the PCM can be thought of as a partial observation
  of the LAM, while the EAM is a fully observed one but corrupted with noise/outliers.
  To this end, we innovatively cast the semisupervised affinity matrix learning as
  the recovery of the LAM guided by the PCM and EAM, which is technically formulated
  as a convex optimization problem. We also provide an efficient algorithm for solving
  the resulting model numerically. Extensive experiments on benchmark datasets demonstrate
  the significant superiority of our method over state-of-the-art ones when used for
  constrained clustering and dimensionality reduction. The code is publicly available
  at https://github.com/jyh-learning/LAM.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Clustering
- graph learning
- semisupervised learning

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
