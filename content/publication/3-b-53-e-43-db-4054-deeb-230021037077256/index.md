---
title: Adaptively Allocating Search Effort in Challenging Many-Objective Optimization
  Problems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hai-Lin Liu
- Lei Chen
- Qingfu Zhang
- Kalyanmoy Deb

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2018-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.340482Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2017.2725902

abstract: An effective allocation of search effort is important in multi-objective
  optimization, particularly in many-objective optimization problems. This paper presents
  a new adaptive search effort allocation strategy for MOEA/D-M2M, a recent MOEA/D
  algorithm for challenging Many-Objective Optimization Problems (MaOPs). This proposed
  method adaptively adjusts the subregions of its subproblems by detecting the importance
  of different objectives in an adaptive manner. More specifically, it periodically
  resets the subregion setting based on the distribution of the current solutions
  in the objective space such that the search effort is not wasted on unpromising
  regions. The basic idea is that the current population can be regarded as an approximation
  to the Pareto front (PF) and thus one can implicitly estimate the shape of the PF
  and such estimation can be used for adjusting the search focus. The performance
  of proposed algorithm has been verified by comparing it with eight representative
  and competitive algorithms on a set of degenerated many-objective optimization problems
  with disconnected and connected PFs. Performances of the proposed algorithm on a
  number of non-degenerated test instances with connected and disconnected PFs are
  also studied.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Adaptive allocation
- evolutionary algorithm
- many-objective optimization
- multiobjective evolutionary algorithm based on decomposition (MOEA/D)

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
