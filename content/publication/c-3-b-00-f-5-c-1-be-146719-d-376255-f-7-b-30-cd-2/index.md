---
title: Bilevel Optimization via Collaborations among Lower-Level Optimization Tasks

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pei-Qiu Huang
- Qingfu Zhang
- Yong Wang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.311607Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2022.3233409

abstract: Bilevel metaheuristics have been widely used for bilevel optimization. However,
  recent studies have indicated that most bilevel metaheuristics are inefficient since
  they perform the lower-level optimization task for each upper-level solution independently
  and neglect the relationship among lower-level optimization tasks. In this paper,
  we develop a bilevel metaheuristic with the collaborations among lower-level optimization
  tasks. Specifically, a population is evolved to solve the lower-level optimization
  tasks for all upper-level solutions collaboratively at each generation. In the population,
  each solution is associated with a lower-level optimization task. In such a way,
  all lower-level optimization tasks can be solved in a single run. To capture the
  individual features of different lower-level optimization tasks, we construct a
  lower-level search distribution for each lower-level optimization task based on
  all solutions in the population. In addition, an information-sharing mechanism is
  proposed to share good solutions among lower-level optimization tasks. Experiments
  on two sets of test problems and three practical applications demonstrate that our
  proposed algorithm performs better than other bilevel metaheuristics in comparison.
  © 2023 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Bilevel optimization
- Collaboration
- Genetic algorithms
- information sharing
- metaheuristics
- multi-task collaboration
- Particle swarm optimization
- search efficiency
- Sociology
- Task analysis
- Urban areas

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
