---
title: A bi-objective learn-and-deploy scheduling method for bursty and stochastic
  requests on heterogeneous cloud servers

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xinye Cai
- Haiyang Xu
- Xiaoping Li
- Kang Wang
- Long Chen
- Rubén Ruiz García
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.622606Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
publication_short: ''

doi: 10.1109/TPDS.2022.3196475

abstract: 'In this article, we consider the dynamic allocation of bursty requests
  stochastically arriving at heterogeneous servers with uncertain setup times. Lower
  expected response time and less power consumption are desirable objectives of users
  and service providers respectively. However, sudden increase and decrease of cloud
  servers caused by bursty requests are rather challenging to get an appropriate trade-off
  between the two conflicting objectives which are closely related to the launched
  servers. The heterogeneity of the cloud servers further makes it more difficult
  to decide how to switch on and off servers and effectively and efficiently allocate
  bursty requests with balanced objectives. Based on a Markov decision process, a
  real-time bilevel decision-making model is constructed for unallocated requests
  which includes: whether to launch a server and which type of server to launch. A
  learn-and-deploy algorithm framework is proposed which contains two complementary
  stages. In the first stage, an effective offline bi-objective optimization algorithm
  is proposed to learn a set of policies, which provides helpful trade-off information
  for a decision-maker to choose a preferred policy a posteriori. In terms of the
  system status, a policy decides whether to launch a server according to a state-action
  table and which server to launch using a server priority sequence. In the second
  stage, a computationally efficient policy deployment method is proposed to search
  the corresponding action in the selected policy based on the current system status
  and apply it to the real-time system. Experimental studies over a large number of
  random and real instances have been conducted to validate the effectiveness of the
  proposed bilevel model and algorithm. Compared to the most recent existing method,
  the performance of the proposed approach can at most achieve an 80% improvement
  on power consumption and 20% improvement on response time.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Analytical models
- bursty and stochastic requests
- Cloud computing
- dynamic programming
- heterogeneous servers
- learn-and-deploy
- Markov decision process
- multiobjective optimization
- Optimization
- Power demand
- Real-time systems
- Servers
- Time factors

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
