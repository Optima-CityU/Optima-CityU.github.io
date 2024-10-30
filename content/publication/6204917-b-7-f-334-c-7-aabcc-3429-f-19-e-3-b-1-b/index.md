---
title: Novel Multitask Conditional Neural-Network Surrogate Models for Expensive Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jianping Luo
- Liang Chen
- Xia Li
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.398723Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2020.3014126

abstract: Multiple-related tasks can be learned simultaneously by sharing information
  among tasks to avoid tabula rasa learning and to improve performance in the no transfer
  case (i.e., when each task learns in isolation). This study investigates multitask
  learning with conditional neural process (CNP) networks and proposes two multitask
  learning network models on the basis of CNPs, namely, the one-to-many multitask
  CNP (OMc-MTCNP) and the many-to-many MTCNP (MMc-MTCNP). Compared with existing multitask
  models, the proposed models add an extensible correlation learning layer to learn
  the correlation among tasks. Moreover, the proposed multitask CNP (MTCNP) networks
  are regarded as surrogate models and applied to a Bayesian optimization framework
  to replace the Gaussian process (GP) to avoid the complex covariance calculation.
  The proposed Bayesian optimization framework simultaneously infers multiple tasks
  by utilizing the possible dependencies among them to share knowledge across tasks.
  The proposed surrogate models augment the observed dataset with a number of related
  tasks to estimate model parameters confidently. The experimental studies under several
  scenarios indicate that the proposed algorithms are competitive in performance compared
  with GP-, single-task-, and other multitask model-based Bayesian optimization methods.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Task analysis
- Correlation
- Optimization
- Neural networks
- Bayes methods
- Linear programming
- Computational modeling
- Evolutionary optimization
- Gaussian process (GP)
- multitask
- neural network
- surrogate model
- ALGORITHM
- SEARCH

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
