---
title: A gaussian process surrogate model assisted evolutionary algorithm for medium
  scale expensive optimization problems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Bo Liu
- Qingfu Zhang
- Georges G.E. Gielen

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2014-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.782287Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2013.2248012

abstract: Surrogate model assisted evolutionary algorithms (SAEAs) have recently attracted
  much attention due to the growing need for computationally expensive optimization
  in many real-world applications. Most current SAEAs, however, focus on small-scale
  problems. SAEAs for medium-scale problems (i.e., 20-50 decision variables) have
  not yet been well studied. In this paper, a Gaussian process surrogate model assisted
  evolutionary algorithm for medium-scale computationally expensive optimization problems
  (GPEME) is proposed and investigated. Its major components are a surrogate model-aware
  search mechanism for expensive optimization problems when a high-quality surrogate
  model is difficult to build and dimension reduction techniques for tackling the
  'curse of dimensionality.' A new framework is developed and used in GPEME, which
  carefully coordinates the surrogate modeling and the evolutionary search, so that
  the search can focus on a small promising area and is supported by the constructed
  surrogate model. Sammon mapping is introduced to transform the decision variables
  from tens of dimensions to a few dimensions, in order to take advantage of Gaussian
  process surrogate modeling in a low-dimensional space. Empirical studies on benchmark
  problems with 20, 30, and 50 variables and a real-world power amplifier design automation
  problem with 17 variables show the high efficiency and effectiveness of GPEME. Compared
  to three state-of-the-art SAEAs, better or similar solutions can be obtained with
  12% to 50% exact function evaluations. © 1997-2012 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Dimension reduction
- expensive optimization
- Gaussian process
- prescreening
- space mapping
- surrogate model assisted evolutionary computation
- surrogate models

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
