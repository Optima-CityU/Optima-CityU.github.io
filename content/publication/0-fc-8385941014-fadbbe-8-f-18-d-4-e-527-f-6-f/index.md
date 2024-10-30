---
title: Efficient Nondomination Level Update Method for Steady-State Evolutionary Multiobjective
  Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Ke Li
- Kalyanmoy Deb
- Qingfu Zhang
- Qiang Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2017-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.510230Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2016.2621008

abstract: Nondominated sorting (NDS), which divides a population into several nondomination
  levels (NDLs), is a basic step in many evolutionary multiobjective optimization
  (EMO) algorithms. It has been widely studied in a generational evolution model,
  where the environmental selection is performed after generating a whole population
  of offspring. However, in a steady-state evolution model, where a population is
  updated right after the generation of a new candidate, the NDS can be extremely
  time consuming. This is especially severe when the number of objectives and population
  size become large. In this paper, we propose an efficient NDL update method to reduce
  the cost for maintaining the NDL structure in steady-state EMO. Instead of performing
  the NDS from scratch, our method only updates the NDLs of a limited number of solutions
  by extracting the knowledge from the current NDL structure. Notice that our NDL
  update method is performed twice at each iteration. One is after the reproduction,
  the other is after the environmental selection. Extensive experiments fully demonstrate
  that, comparing to the other five state-of-the-art NDS methods, our proposed method
  avoids a significant amount of unnecessary comparisons, not only in the synthetic
  data sets, but also in some real optimization scenarios. Last but not least, we
  find that our proposed method is also useful for the generational evolution model.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computational complexity
- nondominated sorting (NDS)
- nondomination level (NDL)
- Pareto dominance
- steady-state evolutionary multiobjective optimization (EMO)

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
