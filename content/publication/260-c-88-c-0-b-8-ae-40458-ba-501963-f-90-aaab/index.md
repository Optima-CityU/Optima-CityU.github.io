---
title: Multiobjective Optimization-Aided Decision-Making System for Large-Scale Manufacturing
  Planning

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhenkun Wang
- Hui-Ling Zhen
- Jingda Deng
- Qingfu Zhang
- Xijun Li
- Mingxuan Yuan
- Jia Zeng

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.255101Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2021.3049712

abstract: This work is geared toward a real-world manufacturing planning (MP) task,
  whose two objectives are to maximize the order fulfillment rate and minimize the
  total cost. More important, the requirements and constraints in real manufacturing
  make the MP task very challenging in several aspects. For example, the MP needs
  to cover many production components of multiple plants over a 30-day horizon, which
  means that it involves a large number of decision variables. Furthermore, the MP
  task's two objectives have extremely different magnitudes, and some constraints
  are difficult to handle. Facing these uncompromising practical requirements, we
  introduce an interactive multiobjective optimization-based MP system in this article.
  It can help the decision maker reach a satisfactory tradeoff between the two objectives
  without consuming massive calculations. In the MP system, the submitted MP task
  is modeled as a multiobjective integer programming (MOIP) problem. Then, the MOIP
  problem is addressed via a two-stage multiobjective optimization algorithm (TSMOA).
  To alleviate the heavy calculation burden, TSMOA transforms the optimization of
  the MOIP problem into the optimization of a series of single-objective problems
  (SOPs). Meanwhile, a new SOP solving strategy is used in the MP system to further
  reduce the computational cost. It utilizes two sequential easier SOPs as the approximator
  of the original complex SOP for optimization. As part of the MP system, TSMOA and
  the SOP solving strategy are demonstrated to be efficient in real-world MP applications.
  In addition, the effectiveness of TSMOA is also validated on benchmark problems.
  The results indicate that TSMOA as well as the MP system are promising.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Integer programming
- manufacturing planning (MP)
- multiobjective optimization
- real-world application
- two-stage

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
