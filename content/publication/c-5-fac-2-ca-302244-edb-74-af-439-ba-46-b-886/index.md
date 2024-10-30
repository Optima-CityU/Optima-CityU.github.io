---
title: Continuation Path Learning for Homotopy Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xi Lin
- Zhiyuan Yang
- Xiaoyuan Zhang
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.361742Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 40th International Conference on Machine Learning*'
publication_short: ''

doi: ''

abstract: Homotopy optimization is a traditional method to deal with a complicated
  optimization problem by solving a sequence of easy-to-hard surrogate subproblems.
  However, this method can be very sensitive to the continuation schedule design and
  might lead to a suboptimal solution to the original problem. In addition, the intermediate
  solutions, often ignored by classic homotopy optimization, could be useful for many
  real-world applications. In this work, we propose a novel model-based approach to
  learn the whole continuation path for homotopy optimization, which contains infinite
  intermediate solutions for any surrogate subproblems. Rather than the classic unidirectional
  easy-to-hard optimization, our method can simultaneously optimize the original problem
  and all surrogate subproblems in a collaborative manner. The proposed model also
  supports the real-time generation of any intermediate solution, which could be desirable
  for many applications. Experimental studies on different problems show that our
  proposed method can significantly improve the performance of homotopy optimization
  and provide extra helpful information to support better decision-making.© 2023 by
  the author(s).

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
  url: https://icml.cc/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
