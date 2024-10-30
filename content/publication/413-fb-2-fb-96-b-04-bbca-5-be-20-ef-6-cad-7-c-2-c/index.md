---
title: Provably Neural Active Learning Succeeds via Prioritizing Perplexing Samples

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Dake Bu
- Wei Huang
- Taiji Suzuki
- Ji Cheng
- Qingfu Zhang
- Zhiqiang Xu
- Hau-San Wong

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.473719Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of 41st International Conference on Machine Learning*'
publication_short: ''

doi: ''

abstract: 'Neural Network-based active learning (NAL) is a cost-effective data selection
  technique that utilizes neural networks to select and train on a small subset of
  samples. While existing work successfully develops various effective or theory-justified
  NAL algorithms, the understanding of the two commonly used query criteria of NAL:
  uncertainty-based and diversity-based, remains in its infancy. In this work, we
  try to move one step forward by offering a unified explanation for the success of
  both query criteria-based NAL from a feature learning view. Specifically, we consider
  a feature-noise data model comprising easy-to-learn or hard-to-learn features disrupted
  by noise, and conduct analysis over 2-layer NN-based NALs in the pool-based scenario.
  We provably show that both uncertainty-based and diversity-based NAL are inherently
  amenable to one and the same principle, i.e., striving to prioritize samples that
  contain yet-to-be-learned features. We further prove that this shared principle
  is the key to their success-achieve small test error within a small labeled set.
  Contrastingly, the strategy-free passive learning exhibits a large test error due
  to the inadequate learning of yet-to-be-learned features, necessitating resort to
  a significantly larger label complexity for a sufficient test error reduction. Experimental
  results validate our findings. © 2024 by the author(s).'

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
  url: https://proceedings.mlr.press/v235/, https://icml.cc/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
