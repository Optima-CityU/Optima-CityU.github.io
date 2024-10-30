---
title: 'Homotopic Convex Transformation: A New Landscape Smoothing Method for the
  Traveling Salesman Problem'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jialong Shi
- Jianyong Sun
- Qingfu Zhang
- Kai Ye

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.846013Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2020.2981385

abstract: 'This article proposes a novel landscape smoothing method for the symmetric
  traveling salesman problem (TSP). We first define the homotopic convex (HC) transformation
  of a TSP as a convex combination of a well-constructed simple TSP and the original
  TSP. The simple TSP, called the convex-hull TSP, is constructed by transforming
  a known local or global optimum. We observe that controlled by the coefficient of
  the convex combination, with local or global optimum: 1) the landscape of the HC
  transformed TSP is smoothed in terms that its number of local optima is reduced
  compared to the original TSP and 2) the fitness distance correlation of the HC transformed
  TSP is increased. Furthermore, we observe that the smoothing effect of the HC transformation
  depends highly on the quality of the used optimum. A high-quality optimum leads
  to a better smoothing effect than a low-quality optimum. We then propose an iterative
  algorithmic framework in which the proposed HC transformation is combined within
  a heuristic TSP solver. It works as an escaping scheme from local optima aiming
  to improve the global searchability of the combined heuristic. Case studies using
  the 3-Opt and the Lin-Kernighan local search as the heuristic solver show that the
  resultant algorithms significantly outperform their counterparts and two other smoothing-based
  TSP heuristic solvers on most of the test instances with up to 20 000 cities.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Combinatorial optimization
- homotopic convex (HC) transformation
- landscape smoothing
- local search
- traveling salesman problem (TSP)

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
