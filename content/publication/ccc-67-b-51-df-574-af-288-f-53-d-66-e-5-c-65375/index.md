---
title: Evolutionary Many-Objective Optimization Based on Adversarial Decomposition

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Mengyuan Wu
- Ke Li
- Sam Kwong
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.510230Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2018.2872803

abstract: The decomposition-based evolutionary algorithm has become an increasingly
  popular choice for posterior multiobjective optimization. Facing the challenges
  of an increasing number of objectives, many techniques have been developed which
  help to balance the convergence and diversity. Nevertheless, according to a recent
  study by Ishibuchi et al., due to the predefined search directions toward the ideal
  point, their performance strongly depends on the Pareto front (PF) shapes, especially
  the orientation of the PFs. To balance the convergence and diversity for decomposition-based
  methods and to alleviate their performance dependence on the orientation of the
  PFs, this paper develops an adversarial decomposition method for many-objective
  optimization, which leverages the complementary characteristics of different subproblem
  formulations within a single paradigm. More specifically, two populations are co-evolved
  by two subproblem formulations with different contours and adversarial search directions.
  To avoid allocating redundant computational resources to the same region of the
  PF, the two populations are matched into one-to-one solution pairs according to
  their working regions upon the PF. Each solution pair can at most contribute one
  principal mating parent during the mating selection process. When comparing nine
  state-of-the-art many-objective optimizers, we have witnessed the competitive performance
  of our proposed algorithm on 130 many-objective test problems with various characteristics,
  including regular and inverted PFs.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Adversarial decomposition
- Computer science
- Convergence
- evolutionary algorithm
- Evolutionary computation
- many-objective optimization
- Optimization
- Shape
- Sociology
- stable matching theory
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
