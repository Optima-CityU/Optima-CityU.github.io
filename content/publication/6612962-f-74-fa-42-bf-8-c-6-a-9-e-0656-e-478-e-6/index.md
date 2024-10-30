---
title: Entropy-Based Termination Criterion for Multiobjective Evolutionary Algorithms

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Dhish Kumar Saxena
- Arnab Sinha
- João A. Duro
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2016-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.894345Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2015.2480780

abstract: Multiobjective evolutionary algorithms evolve a population of solutions
  through successive generations toward the Pareto-optimal front (POF). One of the
  most critical questions faced by the researchers and practitioners in this domain
  relates to the number of generations that may be sufficient for an algorithm to
  offer a good approximation of the POF for a given problem. Ironically, to date,
  this question largely remains unanswered and the number of generations are arbitrarily
  fixed a priori, with potentially punitive implications. If the a priori fixed generations
  are insufficient, then the algorithm reports suboptimal solutions. In contrast,
  if the a priori fixed generations are far too many, it implies waste of computational
  resources. This paper proposes a novel entropy-based dissimilarity measure that
  helps identify on the fly the number of generations beyond which an algorithm stabilizes,
  implying that either a good approximation has been obtained or that it cannot be
  obtained due to the stagnation of the algorithm in the search space. Given that
  in either case no further improvement in the approximation can be obtained, despite
  additional computational expense, the proposed dissimilarity measure provides a
  termination criterion and facilitates a termination detection algorithm. The generality,
  on-the-fly implementation, low-computational complexity, and the demonstrated efficacy
  of the proposed termination detection algorithm, on a wide range of multiobjective
  and many-objective test problems, define the novel contribution of this paper.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Entropy
- evolutionary multiobjective optimization
- many-objective optimization
- termination detection algorithm

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
