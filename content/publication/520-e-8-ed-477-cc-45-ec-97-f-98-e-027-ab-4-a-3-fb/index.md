---
title: Exploring interpretable evolutionary optimization via significance of each
  constraint and population diversity

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yalin Wang
- Xujie Tan
- Chenliang Liu
- Pei-Qiu Huang
- Qingfu Zhang
- Chunhua Yang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.710792Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Swarm and Evolutionary Computation*'
publication_short: ''

doi: 10.1016/j.swevo.2024.101679

abstract: Evolutionary algorithms (EAs) have been widely employed to solve complex
  constrained optimization problems (COPs). However, numerous EAs treat constraints
  as a collective black box, employing a uniform processing technique for all constraints.
  Generally, there exists variability in the significance of each constraint within
  COPs. To address this issue, this paper is the first attempt to investigate the
  significance of each constraint spontaneously during the evolution process, and
  then proposes a co-directed evolutionary algorithm (CdEA-SCPD) for exploring interpretable
  COPs. First, CdEA-SCPD develops an adaptive penalty function designed to assign
  different weights to constraints based on their violation severity, thereby varying
  the significance of each constraint to enhance interpretability and facilitate the
  algorithm to converge more rapidly toward the global optimum. In addition, a dynamic
  archiving strategy and a shared replacement mechanism are developed to improve the
  population diversity of CdEA-SCPD. Extensive experiments on benchmark functions
  from IEEE CEC2006, CEC2010, and CEC2017 and three engineering problems demonstrate
  the superiority of the proposed CdEA-SCPD compared to existing competitive EAs.
  Specifically, on the benchmark functions from IEEE CEC2010, the proposed method
  yields ρ values lower than 0.05 in the multiple-problem Wilcoxon's signed rank test
  and ranks first in the Friedman's test. Furthermore, ablation analysis and parameter
  analysis have demonstrated the beneficial effects of the proposed strategies. ©
  2024 Elsevier B.V.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Constrained optimization
- Evolutionary algorithm
- Population diversity
- Significance of each constraint

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
