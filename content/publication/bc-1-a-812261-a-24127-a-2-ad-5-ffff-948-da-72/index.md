---
title: Crowd Counting via Perspective-Guided Fractional-Dilation Convolution

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhaoyi Yan
- Ruimao Zhang
- Hongzhi Zhang
- Qingfu Zhang
- Wangmeng Zuo

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.074086Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Multimedia*'
publication_short: ''

doi: 10.1109/TMM.2021.3086709

abstract: Crowd counting is critical for numerous video surveillance scenarios. One
  of the main issues in this task is how to handle the dramatic scale variations of
  pedestrians caused by the perspective effect. To address this issue, this paper
  proposes a novel convolution neural network-based crowd counting method, termed
  Perspective-guided Fractional-Dilation Network (PFDNet). By modeling the continuous
  scale variations, the proposed PFDNet is able to select the proper fractional-dilation
  kernels for adapting to different spatial locations. It significantly improves the
  flexibility of the most state-of-the-arts that only consider the discrete representative
  scales. In addition, by avoiding the multi-scale or multi-column architecture that
  used in other methods, it is computationally more efficient. In practice, the proposed
  PFDNet is constructed by stacking multiple Perspective-guided Fractional-Dilation
  Convolutions (PFC) on a VGG16-BN backbone. By introducing a novel generalized dilation
  convolution operation, the PFC can handle fractional dilation ratios in the spatial
  domain under the guidance of perspective annotations, achieving continuous scales
  modeling of pedestrians. To deal with the problem of unavailable perspective information
  in some cases, we further introduce an effective perspective estimation branch to
  the proposed PFDNet, which can be trained in either supervised or weakly-supervised
  setting once the branch has been pre-trained. Extensive experiments show that the
  proposed PFD-Net outperforms state-of-the-art methods on ShanghaiTech A, ShanghaiTech
  B, WorldExpo10, UCF-QNRF, UCFCC50 and TRANCOS dataset, achieving MAE53.8, 6.5, 6.8,
  84.3, 205.8, and 3.06 respectively. The pre-trained models and source code are online
  available at https://github.com/Zhaoyi-Yan/PFDNet.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Annotations
- Computer architecture
- Computer science
- Convolution
- Estimation
- Feature extraction
- Kernel

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
