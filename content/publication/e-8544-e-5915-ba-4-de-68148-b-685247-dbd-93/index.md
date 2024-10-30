---
title: Objective Extraction for Simplifying Many-Objective Solution Sets

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Genghui Li
- Zhenkun Wang
- Jianyong Sun
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.922976Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Emerging Topics in Computational Intelligence*'
publication_short: ''

doi: 10.1109/TETCI.2023.3301401

abstract: Multi-objective evolutionary algorithms (MOEAs) can find a set of Pareto
  solutions to the multi-objective optimization problem. However, it is still a challenge
  for the decision-maker to understand the relationship between various Pareto solutions
  and pick up the really preferred solution. This article proposes an objective extraction
  method to simplify the many-objective solution set by reducing the objective dimensionality
  but keeping the dominance and distribution relationships between solutions. First,
  a sparse regularized self-representation (SRSR) model is developed to learn the
  linear relationship among objectives, in which all objectives are determined by
  a set of base ones. Second, an alternating direction method of multipliers (ADMM)
  is constructed to solve such a model. Finally, an objective extraction method (SRSR-OE)
  that can preserve the dominance and distribution relationships between solutions
  is invented by exploiting the learned relationship. Experimental results show that
  our SRSR model and ADMM algorithm are efficient for extracting the linear objective
  relationship, and the developed objective extraction method also has advantages
  over some state-of-the-art ones in preserving dominance and distribution relationships
  between solutions after solution set simplification. © 2023 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Data mining
- dominance and distribution relationship preservation
- Feature extraction
- linear objective extraction
- Many-objective solution set simplification
- Object recognition
- Optimization
- Search problems
- Sparse matrices
- Task analysis

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
