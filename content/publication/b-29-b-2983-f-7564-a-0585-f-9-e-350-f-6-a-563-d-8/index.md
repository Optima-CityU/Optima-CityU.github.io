---
title: 'Many-to-Few Decomposition: Linking R2-based and Decomposition-based Multiobjective
  Efficient Global Optimization Algorithms'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Liang Zhao
- Xiaobin Huang
- Chao Qian
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.721690Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2024.3434511

abstract: In multiobjective optimization, the R2 indicator is widely used for designing
  indicator-based algorithms, and the Tchebycheff approach is commonly employed in
  decomposition-based algorithms. Despite their wide use, the connection between these
  two different paradigms is still not well understood, particularly in the field
  of multiobjective efficient global optimization (MOEGO). Considering that expected
  improvement (EI) is a cornerstone in efficient global optimization, this paper first
  studies the relationship between R2-based EI and Tchebycheff-based EI. Then, we
  introduce a Many-to-Few (M2F) decomposition framework, offering a new perspective
  for linking the R2-based method and the Tchebycheff decomposition approach. By incorporating
  M2F decomposition into MOEGO, a new algorithm called R2/D-EGO is proposed. At each
  iteration, R2/D-EGO utilizes the Tchebycheff decomposition paradigm to generate
  a set of candidate solutions, each one corresponding to a different weight vector.
  Subsequently, a subset of query points is selected from the candidates based on
  the lower bound of R2-based EI. Empirical results indicate that the proposed R2/D-EGO
  is highly competitive in comparison with both R2-based and decomposition-based MOEGO
  algorithms in the parallel (or batch) setting. © 2024 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- R2 indicator
- decomposition
- Efficient Global Optimization (EGO)
- expensive multiobjective optimization

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
