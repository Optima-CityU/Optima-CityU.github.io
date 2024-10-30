---
title: 'SA-ES: Subspace Activation Evolution Strategy for Black-Box Adversarial Attacks'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenhua Li
- Huilin Cheng
- Xinye Cai
- Jun Zhao
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.956845Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Emerging Topics in Computational Intelligence*'
publication_short: ''

doi: 10.1109/TETCI.2022.3214627

abstract: Deep neural networks are vulnerable to adversarial examples that alter the
  output significantly with imperceptible change in the input. In our black-box setting,
  the adversarial attacker can only query the model to predict the value after the
  softmax layer without accessing the underlying model. Currently, generating adversarial
  examples with high qualifications in the query-limited setting and investigating
  the distribution of adversarial examples are two main challenges in the black-box
  attack. In this paper, we propose a zeroth-order optimization method for the black-box
  adversarial attack, termed subspace activation evolution strategy (SA-ES). It captures
  the most promising direction for generating more convincing adversarial examples.Moreover,
  instead of only searching for one reliable adversarial example for an original input,
  SA-ES finds a distribution of adversarial examples, such that a sample drawn from
  this distribution is likely an adversarial example. We conduct comprehensive experiments
  on various data sets and validate that the proposed algorithm can efficiently find
  perturbation-sensitive regions of an image and stably explore the distribution of
  adversarial examples with the limited query, and outperforms the existing methods.
  In addition, we apply SA-ES to physical reality black-box attacks, which effectively
  generate simulated physical adversarial examples for the adversarial training model.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Digital images
- Distribution
- high-quality
- Neural networks
- Optimization
- Perturbation methods
- perturbation-sensitive regions
- physical attack
- Predictive models
- Robustness
- subspace activation evolution strategy
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
