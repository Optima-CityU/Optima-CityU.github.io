---
title: Maximum Entropy Subspace Clustering Network

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhihao Peng
- Yuheng Jia
- Hui Liu
- Junhui Hou
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.559816Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Circuits and Systems for Video Technology*'
publication_short: ''

doi: 10.1109/TCSVT.2021.3089480

abstract: Deep subspace clustering networks have attracted much attention in subspace
  clustering, in which an auto-encoder non-linearly maps the input data into a latent
  space, and a fully connected layer named self-expressiveness module is introduced
  to learn the affinity matrix via a typical regularization term (e.g., sparse or
  low-rank). However, the adopted regularization terms ignore the connectivity within
  each subspace, limiting their clustering performance. In addition, the adopted framework
  suffers from the coupling issue between the auto-encoder module and the self-expressiveness
  module, making the network training non-trivial. To tackle these two issues, we
  propose a novel deep subspace clustering method named Maximum Entropy Subspace Clustering
  Network (MESC-Net). Specifically, MESC-Net maximizes the entropy of the affinity
  matrix to promote the connectivity within each subspace, in which its elements corresponding
  to the same subspace are uniformly and densely distributed. Meanwhile, we design
  a novel framework to explicitly decouple the auto-encoder module and the self-expressiveness
  module. Besides, we also theoretically prove that the learned affinity matrix satisfies
  the block-diagonal property under the assumption of independent subspaces. Extensive
  quantitative and qualitative results on commonly used benchmark datasets validate
  MESC-Net significantly outperforms state-of-the-art methods. The code is publicly
  available at https://github.com/ZhihaoPENG-CityU/MESC.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Deep learning
- subspace clustering
- maximum entropy regularization
- decoupling

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
