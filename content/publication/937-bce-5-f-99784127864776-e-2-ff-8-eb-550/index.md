---
title: Deep Amended Gradient Descent for Efficient Spectral Reconstruction from Single
  RGB Images

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhiyu Zhu
- Hui Liu
- Junhui Hou
- Sen Jia
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.430705Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Computational Imaging*'
publication_short: ''

doi: 10.1109/TCI.2021.3124364

abstract: This paper investigates the problem of recovering hyperspectral (HS) images
  from single RGB images. To tackle such a severely ill-posed problem, we propose
  a physically-interpretable, compact, efficient and end-to-end learning-based framework,
  namely AGD-Net. Precisely, by taking advantage of the imaging process, we first
  formulate the problem explicitly based on the classic gradient descent algorithm.
  Then, we design a lightweight neural network with a multi-stage architecture to
  mimic the formed amended gradient descent process, in which efficient convolution
  and novel spectral zero-mean normalization are proposed to effectively extract spatial-spectral
  features for regressing an initialization, a basic gradient, and an incremental
  gradient. Besides, based on the approximate low-rank property of HS images, we propose
  a novel rank loss to promote the similarity between the global structures of reconstructed
  and ground-truth HS images, which is optimized with our singular value weighting
  strategy during training. Moreover, AGD-Net, a single network after one-time training,
  is flexible to handle the reconstruction with various spectral response functions.
  Extensive experiments over three commonly-used benchmark datasets demonstrate that
  AGD-Net can improve the reconstruction quality more than 1.0 dB on average while
  saving 67x parameters and 32x FLOPs, compared with state-of-the-art methods. The
  code will be publicly available at https://github.com/zbzhzhy/GD-Net.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Hyperspectral imagery
- spectral reconstruction
- deep learning
- gradient descent
- rank loss

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
