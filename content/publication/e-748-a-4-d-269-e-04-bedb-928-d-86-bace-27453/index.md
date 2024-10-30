---
title: 'ESSR: Evolving Sparse Sharing Representation for Multi-task Learning'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yayu Zhang
- Yuhua Qian
- Guoshuai Ma
- Xinyan Liang
- Guoqing Liu
- Qingfu Zhang
- Ke Tang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.537054Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2023.3272663

abstract: Multi-task learning uses knowledge transfer among tasks to improve the generalization
  performance of all tasks. For deep multi-task learning, knowledge transfer is often
  implemented via sharing all hidden features of tasks. A major shortcoming is that
  it can lead to negative knowledge transfer across tasks when task correlation is
  weak. To overcome it, this paper proposes an evolutionary method to learn sparse
  sharing representations adaptively. By embedding the neural network optimization
  into evolutionary multitasking, our proposed method finds an optimal combination
  of tasks and sharing features. It can identify negative correlation and redundant
  features and then remove them from the hidden feature set. Thus, an optimal sparse
  sharing subnetwork can be produced for each task. Experiment results show that the
  proposed method achieve better learning performance with a smaller inference model
  than other related methods. © 2023 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Adaptation models
- Correlation
- evolutionary multitasking optimization
- knowledge transfer
- Multi-task learning
- Multitasking
- Optimization
- sharing representation
- Task analysis
- Training
- multitask learning (MTL)

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
