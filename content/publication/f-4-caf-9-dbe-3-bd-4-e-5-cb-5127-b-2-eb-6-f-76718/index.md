---
title: Combining Lyapunov Optimization With Evolutionary Transfer Optimization for
  Long-Term Energy Minimization in IRS-Aided Communications

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pei-Qiu Huang
- Yong Wang
- Kezhi Wang
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.814313Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Cybernetics*'
publication_short: ''

doi: 10.1109/TCYB.2022.3168839

abstract: This article studies an intelligent reflecting surface (IRS)-aided communication
  system under the time-varying channels and stochastic data arrivals. In this system,
  we jointly optimize the phase-shift coefficient and the transmit power in sequential
  time slots to maximize the long-term energy consumption for all mobile devices while
  ensuring queue stability. Due to the dynamic environment, it is challenging to ensure
  queue stability. In addition, making real-time decisions in each short time slot
  also needs to be considered. To this end, we propose a method (called LETO) that
  combines Lyapunov optimization with evolutionary transfer optimization (ETO) to
  solve the above optimization problem. LETO first adopts Lyapunov optimization to
  decouple the long-term stochastic optimization problem into deterministic optimization
  problems in sequential time slots. As a result, it can ensure queue stability since
  the deterministic optimization problem in each time slot does not involve future
  information. After that, LETO develops an evolutionary transfer method to solve
  the optimization problem in each time slot. Specifically, we first define a metric
  to identify the optimization problems in past time slots similar to that in the
  current time slot, and then transfer their optimal solutions to construct a high-quality
  initial population in the current time slot. Since ETO effectively accelerates the
  search, we can make real-time decisions in each short time slot. Experimental studies
  verify the effectiveness of LETO by comparison with other algorithms. © 2022 IEEE.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Optimization
- Communication systems
- Wireless communication
- Uplink
- Real-time systems
- Minimization
- Millimeter wave communication
- Dynamic environment
- evolutionary algorithm (EA)
- evolutionary transfer optimization (ETO)
- intelligent reflecting surface (IRS)
- Lyapunov optimization
- CHANNEL ESTIMATION
- BEAMFORMING OPTIMIZATION
- DISTRIBUTED OPTIMIZATION
- WIRELESS NETWORK
- SYSTEMS

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
