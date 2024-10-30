---
title: Problem Specific MOEA/D for Barrier Coverage with Wireless Sensors

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xiao Zhang
- Yu Zhou
- Qingfu Zhang
- Victor C. S. Lee
- Minming Li

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2017-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.654922Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2016.2585745

abstract: "Barrier coverage with wireless sensors aims at detecting intruders who
  attempt to cross a specific area, where wireless sensors are distributed remotely
  at random. This paper considers limited-power sensors with adjustable ranges deployed
  along a linear domain to form a barrier to detect intruding incidents. We introduce
  three objectives to minimize: 1) total power consumption while satisfying full coverage;
  2) the number of active sensors to improve the reliability; and 3) the active sensor
  nodes' maximum sensing range to maintain fairness. We refer to the problem as the
  tradeoff barrier coverage (TBC) problem. With the aim of obtaining a better tradeoff
  among the three objectives, we present a multiobjective optimization framework based
  on multiobjective evolutionary algorithm (MOEA)/D, which is called problem specific
  MOEA/D (PS-MOEA/D). Specifically, we define a 2-tuple encoding scheme and introduce
  a cover-shrink algorithm to produce feasible and relatively optimal solutions. Subsequently,
  we incorporate problem-specific knowledge into local search, which allows search
  procedures for neighboring subproblems collaborate each other. By considering the
  problem characteristics, we analyze the complexity and incorporate a strategy of
  computational resource allocation into our algorithm. We validate our approach by
  comparing with four competitors through several most-used metrics. The experimental
  results demonstrate that PS-MOEA/D is effective and outperforms the four competitors
  in all the cases, which indicates that our approach is promising in dealing with
  TBC."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Barrier coverage
- evolutionary algorithms
- multiobjective optimization
- wireless sensor networks (WSNs)

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
