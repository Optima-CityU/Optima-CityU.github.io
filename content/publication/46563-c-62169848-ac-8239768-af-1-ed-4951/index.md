---
title: A Generator for Multiobjective Test Problems with Difficult-to-Approximate
  Pareto Front Boundaries

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenkun Wang
- Yew-Soon Ong
- Jianyong Sun
- Abhishek Gupta
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.736449Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2018.2872453

abstract: In some real-world applications, it has been found that the performance
  of multiobjective optimization evolutionary algorithms (MOEAs) may deteriorate when
  boundary solutions in the Pareto front (PF) are more difficult to approximate than
  others. Such a problem feature, referred to as difficult-to-approximate (DtA) PF
  boundaries, is seldom considered in existing multiobjective optimization test problems.
  To fill this gap and facilitate possible systematic studies, we introduce a new
  test problem generator. The proposed generator enables the design of test problems
  with controllable difficulties regarding the feature of DtA PF boundaries. Three
  representative MOEAs, NSGA-II, SMS-EMOA, and MOEA/D-DRA, are performed on a series
  of test problems created using the proposed generator. Experimental results indicate
  that all the three algorithms perform poorly on the new test problems. Meanwhile,
  a modified variant of MOEA/D-DRA, denoted as MOEA/D-DRA-UT, is validated to be more
  effective in dealing with these problems. Subsequently, it is concluded that the
  rational allocation of computational resources between different PF parts is crucial
  for MOEAs to handle the problems with DtA PF boundaries.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Difficult-to-approximate (DtA)
- evolutionary algorithm
- Generators
- Multiobjective optimization
- Pareto front (PF) boundaries
- Pareto optimization
- Resource management
- Shape
- Sun
- Systematics
- test problem

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
