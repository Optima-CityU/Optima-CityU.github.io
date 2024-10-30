---
title: Machine Learning Assisted Multiobjective Evolutionary Algorithm for Routing
  and Packing

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Fei Liu
- Qingfu Zhang
- Qingling Zhu
- Xialiang Tong
- Mingxuan Yuan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.295550Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2024.3357819

abstract: Many combinatorial multiobjective optimization problems involve very costly-to-evaluate
  objectives and constraints. It is very difficult, if not impossible, for traditional
  heuristics to solve these problems with an acceptable amount of computational time.
  In this paper, we show that offline machine learning can be very useful to assist
  multiobjective evolutionary algorithms to tackle this kind of problem. We take a
  complicated real-life multiobjective routing-packing problem as the test bed. We
  propose to use offline machine learning methods to replace time-consuming packing
  heuristics for packing feasibility prediction. Experiments show that the machine
  learning models can be 1,000 times faster than some commonly used packing heuristics
  and their accuracy can be as high as 98%. We adopt MOEA/D to decompose the problem
  into a number of single objective subproblems and solve them in a collaborative
  manner. We propose an encoding strategy to represent each routing scheme and use
  genetic operators to generate new routes. Experimental studies have been conducted
  on 100 instances from HUAWEItextquoterights real-world logistics application and
  two test suites from the literature. Our proposed method can solve each HUAWEI instance
  in around one minute. Our solutions on the two test suites are comparable to other
  existing algorithms, and the overall computational cost of our method is significantly
  lower than others. © 2024 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Evolutionary algorithm
- Multiobjective optimization
- Machine learning
- Vehicle routing
- Bin packing

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
