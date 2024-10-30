---
title: Multiobjective Lipschitz Bandits under Lexicographic Ordering

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Bo Xue
- Ji Cheng
- Fei Liu
- Yimu Wang
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.163866Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 38th AAAI Conference on Artificial Intelligence*'
publication_short: ''

doi: 10.1609/aaai.v38i15.29558

abstract: This paper studies the multiobjective bandit problem under lexicographic
  ordering, wherein the learner aims to simultaneously maximize m objectives hierarchically.
  The only existing algorithm for this problem considers the multi-armed bandit model,
  and its regret bound is O∼((KT)2/3) under a metric called priority-based regret.
  However, this bound is suboptimal, as the lower bound for single objective multi-armed
  bandits is Ω(K logT). Moreover, this bound becomes vacuous when the arm number K
  is infinite. To address these limitations, we investigate the multiobjective Lipschitz
  bandit model, which allows for an infinite arm set. Utilizing a newly designed multi-stage
  decision-making strategy, we develop an improved algorithm that achieves a general
  regret bound of O∼(T(d z i+1)/(d z i+2)) for the i-th objective, where dzi is the
  zooming dimension for the i-th objective, with i ∈ 1,2,...,m. This bound matches
  the lower bound of the single objective Lipschitz bandit problem in terms of T,
  indicating that our algorithm is almost optimal. Numerical experiments confirm the
  effectiveness of our algorithm. © 2024, Association for the Advancement of Artificial
  Intelligence (www.aaai.org). All rights reserved.

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
links:
- name: URL
  url: https://aaai.org/aaai-conference/, https://ojs.aaai.org/index.php/AAAI/issue/archive
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
