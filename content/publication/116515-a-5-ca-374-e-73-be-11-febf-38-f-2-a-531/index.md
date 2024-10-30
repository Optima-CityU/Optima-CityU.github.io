---
title: Learning From a Stream of Nonstationary and Dependent Data in Multiobjective
  Evolutionary Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jianyong Sun
- Hu Zhang
- Aimin Zhou
- Qingfu Zhang
- Ke Zhang
- Zhenbiao Tu
- Kai Ye

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.526141Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2018.2865495

abstract: Combining machine learning techniques has shown great potentials in evolutionary
  optimization since the domain knowledge of an optimization problem, if well learned,
  can be a great help for creating high-quality solutions. However, existing learning-based
  multiobjective evolutionary algorithms spend too much computational overhead on
  learning. To address this problem, we propose a learning-based multiobjective evolutionary
  algorithm where an online learning algorithm is embedded within the evolutionary
  search procedure. The online learning algorithm takes the stream of sequentially
  generated solutions along the evolution as its training data. It is noted that the
  stream of solutions are temporal, dependent, non-stationary and non-static. These
  data characteristics make existing online learning algorithm not suitable for the
  evolution data. We hence modify an existing online agglomerative clustering algorithm
  to accommodate these characteristics. The modified online clustering algorithm is
  applied to adaptively discover the structure of the Pareto optimal set; and the
  learned structure is used to guide new solution creation. Experimental results have
  shown significant improvement over four state-of-the-art multiobjective evolutionary
  algorithms on a variety of benchmark problems.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Clustering algorithms
- Convergence
- Evolutionary Algorithms
- Evolutionary computation
- Machine Learning
- Multiobjective Optimization
- Online Agglomerative Clustering.
- Optimization
- Sociology
- Statistics
- Training

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
