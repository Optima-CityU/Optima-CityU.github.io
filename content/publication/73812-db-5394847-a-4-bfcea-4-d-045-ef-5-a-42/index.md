---
title: Building Change Detection for VHR Remote Sensing Images via Local-Global Pyramid
  Network and Cross-Task Transfer Learning Strategy

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Tongfei Liu
- Maoguo Gong
- Di Lu
- Qingfu Zhang
- Hanhong Zheng
- Fenlong Jiang
- Mingyang Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.414537Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Geoscience and Remote Sensing*'
publication_short: ''

doi: 10.1109/TGRS.2021.3130940

abstract: Building change detection (BCD) for very-high-spatial-resolution (VHR) remote
  sensing images is very important and challenging in the field of remote sensing,
  as the building is one of the most significant and valuable man-made ground targets.
  This article proposes a local–global pyramid network (LGPNet) that combines a local
  feature pyramid module (LFPM) and a global spatial pyramid module (GSPM) for various
  building feature extraction. The LFPM is constructed using the convolutional kernel
  with three different pyramid scales, and then, the local pyramid features are obtained
  by adding features of each scale. In the GSPM, the global spatial pyramid features
  are extracted by adaptive average pooling to acquire global contextual information
  from different fields of view on deep features. The LFPM and the GSPM work in a
  parallel and complementary manner to capture discriminative features of various
  buildings. In addition to the LFPM and the GSPM, the proposed LGPNet also employs
  two general attention mechanisms, i.e., the position attention module and the channel
  attention module, which can select and emphasize adaptively some building features
  with high semantic responses. Besides, in order to mitigate the influence of other
  ground targets to a certain extent, a cross-task transfer learning strategy is introduced
  to make the LGPNet focus on the building, which significantly improves the performance
  of our method. Extensive experiments on two public available BCD datasets show that
  the proposed LGPNet can achieve significant improvement compared with eight other
  state-of-the-art methods. The source code and the pretrained model will be released
  at https://github.com/TongfeiLiu/LGPNet .

# Summary. An optional shortened abstract.
summary: ''

tags:
- attention mechanism
- Building change detection (BCD)
- Buildings
- Feature extraction
- Image color analysis
- Image segmentation
- pyramid network
- Remote sensing
- Semantics
- Transfer learning
- very-high-spatial-resolution (VHR) remote sensing images

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
