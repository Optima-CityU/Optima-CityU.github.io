---
title: Multi-UAV roundup strategy method based on deep reinforcement learning CEL-MADDPG
  algorithm

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Bo Li
- Jianmei Wang
- Chao Song
- Zhipeng Yang
- Kaifang Wan
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-07-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.213954Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Expert Systems with Applications*'
publication_short: ''

doi: 10.1016/j.eswa.2023.123018

abstract: 'Due to the complexity of the multi-UAV rounding up maneuvering target task
  in continuous and complex environments, it is difficult for the UAVs to quickly
  and accurately capture maneuvering targets. Therefore, this paper proposes CEL-MADDPG
  algorithm based on Curriculum Experience Learning. It improves the efficiency of
  multi-UAVs rounding up maneuvering target, and has certain generalization. which
  is better applied to the multi-UAV roundup task in complex dynamic environments.
  The main contributions are the following two: By introducing the Curriculum Experience
  Learning, the multi-UAV rounding up task is divided into target tracking, encircling
  transition, and shrinking capture to learn, and designed corresponding reward function
  according to the task characteristics of each subtask. Which improves the learning
  efficiency of the model. Additionally, the CEL-MADDPG adopts the Preferential Experience
  Replay strategy to select experiences that are conducive to accelerating network
  convergence, and the experience most similar to the current state is further selected
  as a learning sample by using Relative Experience Learning (REL). This improves
  the sampling efficiency of samples and the training and optimization efficiency
  of the model. Simulation experiments show that the CEL-MADDPG algorithm can effectively
  improve the training efficiency of the model and has higher task completion efficiency.
  © 2023 Elsevier Ltd'

# Summary. An optional shortened abstract.
summary: ''

tags:
- CEL-MADDPG
- Deep-reinforcement
- Multi-UAV
- Roundup

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
