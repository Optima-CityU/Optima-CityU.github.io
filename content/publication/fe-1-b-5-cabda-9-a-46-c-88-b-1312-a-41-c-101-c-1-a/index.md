---
title: Noisy Optimization by Evolution Strategies With Online Population Size Learning

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenhua Li
- Shuo Zhang
- Xinye Cai
- Qingfu Zhang
- Xiaomin Zhu
- Zhun Fan
- Xiuyi Jia

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.316954Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Systems, Man, and Cybernetics: Systems*'
publication_short: ''

doi: 10.1109/TSMC.2021.3131482

abstract: Optimization modeling of real-world application problems usually involves
  noise from various sources. Noisy optimization imposes challenges to optimization
  methods since the objective values can be different for multiple evaluations. In
  this article, we propose a novel online population size learning (OPL) technique
  of evolution strategies for handling noisy optimization problems. By re-evaluating
  a fraction of the candidates, we measure the strength of noise level of the re-evaluated
  candidate solutions and adapt the population size according to the noise level.
  The proposed OPL combines the advantages of both explicit averaging by re-evaluations
  and the implicit averaging by large population size and overcomes their limitations.
  We incorporate it with the covariance matrix adaptation evolution strategy (CMA-ES)
  and obtain OPL-CMA-ES. Compared with the existing noise handling technique, the
  proposed OPL is much simpler in both concepts and computation. We conduct comprehensive
  experiments to evaluate the algorithm's performance on standard problems with Gaussian
  noise. We further evaluate the performance of OPL-CMA-ES on the black-box optimization
  benchmarks (BBOBs) noisy testbed, which is a standard platform for comparing black-box
  optimization algorithms, compared with the state-of-the-art noise-handling algorithms.
  The experimental results show that OPL-CMA-ES achieves remarkable performance and
  outperforms the compared variants.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Evolution strategies (ESs)
- Iron
- Linear programming
- Noise level
- Noise measurement
- noise strength
- noisy optimization
- online population size learning (OPL)
- Optimization
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
