---
title: Controlling Sequential Hybrid Evolutionary Algorithm by Q-Learning

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Haotian Zhang
- Jianyong Sun
- Thomas Back
- Qingfu Zhang
- Zongben Xu

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.100282Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Computational Intelligence Magazine*'
publication_short: ''

doi: 10.1109/MCI.2022.3222057

abstract: Many state-of-the-art evolutionary algorithms (EAs) can be categorized as
  sequential hybrid EAs, in which various EAs are sequentially executed. The timing
  to switch from one EA to another is critical to the performance of the hybrid EA
  because the switching time determines the allocation of computational resources
  and thereby it helps balance exploration and exploitation. In this article, a framework
  for adaptive parameter control for hybrid EAs is proposed, in which the switching
  time is controlled by a learned agent rather than a manually designed scheme. First
  the framework is applied to an adaptive differential evolution algorithm, LSHADE,
  to control when to use the scheme to reduce the population. Then the framework is
  applied to the algorithm that won the CEC 2018 competition, i.e., the hybrid sampling
  evolution strategy (HSES), to control when to switch from the univariate sampling
  phase to the Covariance Matrix Adaptation Evolution Strategy phase. The agents for
  parameter control in LSHADE and HSES are trained by using Q-learning and deep Q-learning
  to obtain the learned algorithms Q-LSHADE and DQ-HSES. The results of experiments
  on the CEC 2014 and 2018 test suites show that the learned algorithms significantly
  outperform their counterparts and some state-of-the-art EAs. © 2005-2012 IEEE.

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
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
