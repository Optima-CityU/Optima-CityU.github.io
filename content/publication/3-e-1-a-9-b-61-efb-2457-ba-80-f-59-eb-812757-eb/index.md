---
title: Context-content collaborative network for building extraction from high-resolution
  imagery

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Maoguo Gong
- Tongfei Liu
- Mingyang Zhang
- Qingfu Zhang
- Di Lu
- Hanhong Zheng
- Fenlong Jiang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.417431Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Knowledge-Based Systems*'
publication_short: ''

doi: 10.1016/j.knosys.2023.110283

abstract: In practical applications, different application fields have various requirements
  regarding the precision and completeness of building extraction. Too low precision
  or completeness may limit the application and promotion of building extraction.
  Obtaining a good trade-off between the precision and com-pleteness of building extraction
  is still a challenging issue. To deal with this issue, this paper proposes a context-content
  collaborative network (C3Net) with an encoder-decoder structure. It consists of
  a context-content aware module (C2AM) and an edge residual refinement module (ER2M).
  In the C2AM, a context-aware block and a content-aware block complement each other
  and capture the localization information of buildings and long-range dependencies
  between the locations of each building, respectively. Thanks to the capability of
  the conventional filter, the ER2M can refine the features of decoder output by deploying
  a residual atrous spatial pyramid pooling with feature edges at the scale of the
  original image. To explicitly guide the function of the ER2M, we introduce a separated
  deep supervision strategy before and after the ER2M, which can consciously refine
  our C3Net towards the precision or completeness of building extraction to a certain
  extent, and improve the overall detection performance. Compared with several classical
  and state-of-the-art methods, extensive experiments on three open and challenging
  datasets demonstrate that the proposed C3Net not only acquires competitive performance
  but also achieves a better trade-off between precision and completeness of building
  extraction. The source code is released at https://github.com/TongfeiLiu/ C3Net-for-building-extraction.©
  2023 Elsevier B.V. All rights reserved. 

# Summary. An optional shortened abstract.
summary: ''

tags:
- Building extraction
- Deep learning
- Self-attention
- High-resolution remote sensing images
- SATELLITE IMAGES
- INFORMATION

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
