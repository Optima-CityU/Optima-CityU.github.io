---
title: Evolutionary Many-objective Optimization based on Dynamical Decomposition

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xiaoyu He
- Yuren Zhou
- Zefeng Chen
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.323309Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2018.2865590

abstract: 'Decomposition-based many-objective evolutionary algorithms generally decompose
  the objective space into multiple subregions with the help of a set of reference
  vectors. The resulting subregions are fixed since the reference vectors are usually
  pre-defined. When the optimization problem has a complicated Pareto front, this
  decomposition may decrease the algorithm performance. To deal with this problem,
  this paper proposes a dynamical decomposition strategy. Instead of using pre-defined
  reference vectors, solution themselves are used as reference vectors. Thus, they
  are adapted to the shape of Pareto front automatically. Besides, the subregions
  are produced one by one through successively bipartitioning the objective space.
  The resulting subregions are not fixed but dynamically determined by the population
  solutions as well as the subregions produced previously. Based on this strategy,
  a solution ranking method, named DDR, is proposed which can be employed in the mating
  selection and environmental selection in commonly used algorithm frameworks. Compared
  with those in the other decomposition-based algorithms, DDR has the following properties:
  (1) no pre-defined reference vectors are required; (2) less parameters are involved
  and (3) the ranking results can not only be utilized directly to select solutions
  but also serve as a secondary criterion in traditional Pareto-based algorithms.
  In this paper, DDR is equipped in two algorithm frameworks for handling many-objective
  optimization problems. Comparisons with five state-of-the-art algorithms on 31 widely
  used test problems are carried out to test the performance of the proposed approach.
  The experimental results have shown the effectiveness of the proposed approach in
  keeping a good trade-off between convergence and diversity.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Convergence
- dynamical decomposition.
- evolutionary algorithm
- Evolutionary computation
- Heuristic algorithms
- Many-objective optimization
- Optimization
- Shape
- Sociology
- Statistics

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
