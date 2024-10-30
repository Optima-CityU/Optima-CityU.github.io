---
title: Matching-Based Selection With Incomplete Lists for Decomposition Multiobjective
  Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Mengyuan Wu
- Ke Li
- Sam Kwong
- Yu Zhou
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2017-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.559816Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2017.2656922

abstract: 'The balance between convergence and diversity is the cornerstone of evolutionary
  multiobjective optimization (EMO). The recently proposed stable matching-based selection
  provides a new perspective to handle this balance under the framework of decomposition
  multiobjective optimization. In particular, the one-one stable matching between
  subproblems and solutions, which achieves an equilibrium between their mutual preferences,
  is claimed to strike a balance between convergence and diversity. However, the original
  stable marriage model has a high risk of matching a solution with an unfavorable
  subproblem, which finally leads to an imbalanced selection result. In this paper,
  we introduce the concept of incomplete preference lists into the stable matching
  model to remedy the loss of population diversity. In particular, each solution is
  only allowed to maintain a partial preference list consisting of its favorite subproblems.
  We implement two versions of stable matching-based selection mechanisms with incomplete
  preference lists: one achieves a two-level one-one matching and the other obtains
  a many-one matching. Furthermore, an adaptive mechanism is developed to automatically
  set the length of the incomplete preference list for each solution according to
  its local competitiveness. The effectiveness and competitiveness of our proposed
  methods are validated and compared with several state-of-the-art EMO algorithms
  on 62 benchmark problems.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Adaptive mechanism
- convergence and diversity
- decomposition
- multiobjective optimization
- stable matching with incomplete lists

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
