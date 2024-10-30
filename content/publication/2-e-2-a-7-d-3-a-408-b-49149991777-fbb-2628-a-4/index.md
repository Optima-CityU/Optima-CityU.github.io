---
title: 'Learning to Decompose: A Paradigm for Decomposition-Based Multiobjective Optimization'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Mengyuan Wu
- Ke Li
- Sam Kwong
- Qingfu Zhang
- Jun Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.590308Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2018.2865931

abstract: 'The decomposition-based evolutionary multiobjective optimization algorithm
  has become an increasingly popular choice for a posteriori multiobjective optimization.
  However, recent studies have shown that their performance strongly depends on the
  Pareto front shapes. This can be attributed to the decomposition method, of which
  the reference points and subproblem formulation settings are not well adaptable
  to various problem characteristics. In this paper, we develop a learning-to-decompose
  paradigm that adaptively sets the decomposition method by learning the characteristics
  of the estimated Pareto front. Specifically, it consists of two inter-dependent
  parts, i.e., a learning module and an optimization module. Given the current non-dominated
  solutions from the optimization module, the learning module periodically learns
  an analytical model of the estimated Pareto front. Thereafter, useful information
  is extracted from the learned model to set the decomposition method for the optimization
  module, including: 1) reference points compliant with the Pareto front shape; and
  2) subproblem formulations whose contours and search directions are appropriate
  for the current status. Accordingly, the optimization module, which can be any decomposition-based
  evolutionary multiobjective optimization algorithm in principle, decomposes the
  multiobjective optimization problem into a number of subproblems and optimizes them
  simultaneously. To validate our proposed learning-to-decompose paradigm, we integrate
  it with two decomposition-based evolutionary multiobjective optimization algorithms,
  and compare them with four state-of-the-art algorithms on a series of benchmark
  problems with various Pareto front shapes.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- decomposition.
- evolutionary computation
- Gaussian process regression
- multiobjective optimization
- reference points generation

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
