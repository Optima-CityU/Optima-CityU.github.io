---
title: Multi-objective decomposition evolutionary algorithm with objective modification-based
  dominance and external archive

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenkun Wang
- Qingyan Li
- Genghui Li
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.087316Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Applied Soft Computing*'
publication_short: ''

doi: 10.1016/j.asoc.2023.111006

abstract: In practice, the multi-objective optimization problem (MOP) is typically
  challenging in two aspects. On the one hand, its Pareto front has imbalanced search
  difficulties; on the other hand, its search space contains many dominance resistant
  solutions (DRSs). Decomposing a complicated MOP into several simple MOPs for collaborative
  optimization (M2M) has been acknowledged to be efficient in coping with the imbalanced
  search difficulty. Nevertheless, the convergence efficiency of the M2M-based multi-objective
  evolutionary algorithm (MOEA) is rarely investigated, especially on the MOP with
  DRSs. This paper reveals two convergence challenges faced by M2M-based MOEAs. Subsequently,
  a variant called MOEA/D-OMDEA is proposed to achieve better convergence efficiency
  without sacrificing advantages in diversity preservation. MOEA/D-OMDEA integrates
  a new relaxed dominance criterion, namely the OM-dominance criterion, into its environmental
  selection to alleviate the negative influence of inferior solutions (e.g., DRSs)
  as well as to better balance convergence and diversity. MOEA/D-OMDEA is compared
  with ten state-of-the-art MOEAs on two sets of MOP benchmarks with different characteristics
  and a real-world problem. Experimental results indicate that MOEA/D-OMDEA can significantly
  outperform the other ten competitors on these problems. In addition, this paper
  provides a thorough analysis of the effectiveness of each new algorithmic component
  and the sensitivity of each newly-introduced parameter. © 2023 Published by Elsevier
  B.V.

# Summary. An optional shortened abstract.
summary: ''

tags:
- External archive
- MOP with different search difficulties
- Multi-objective decomposition evolutionary algorithm
- Objective modification-based dominance

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
