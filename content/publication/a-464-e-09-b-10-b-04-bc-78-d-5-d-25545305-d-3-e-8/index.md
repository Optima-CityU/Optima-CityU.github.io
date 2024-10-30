---
title: A new cooperative framework for parallel trajectory-based metaheuristics

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jialong Shi
- Qingfu Zhang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2018-04-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.004810Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Applied Soft Computing Journal*'
publication_short: ''

doi: 10.1016/j.asoc.2018.01.022

abstract: In this paper, we propose the Parallel Elite Biased framework (PEB framework)
  for parallel trajectory-based metaheuristics. In the PEB framework, multiple search
  processes are executed concurrently. During the search, each process sends its best
  found solutions to its neighboring processes and uses the received solutions to
  guide its search. Using the PEB framework, we design a parallel variant of Guided
  Local Search (GLS) called PEBGLS. Extensive experiments have been conducted on the
  Tianhe-2 supercomputer to study the performance of PEBGLS on the Traveling Salesman
  Problem (TSP). The experimental results show that PEBGLS is a competitive parallel
  metaheuristic for the TSP, which confirms that the PEB framework is useful for designing
  parallel trajectory-based metaheuristics.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Algorithm design
- Combinatorial optimization
- Guided Local Search
- Parallel metaheuristics

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
