---
title: A Parallel Tabu Search for the Unconstrained Binary Quadratic Programming problem

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jialong Shi
- Qingfu Zhang
- Bilel Derbel
- Arnaud Liefooghe

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2017-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.686778Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2017 IEEE Congress on Evolutionary Computation, CEC 2017 - Proceedings*'
publication_short: ''

doi: 10.1109/CEC.2017.7969360

abstract: 'Although several sequential heuristics have been proposed for dealing with
  the Unconstrained Binary Quadratic Programming (UBQP), very little effort has been
  made for designing parallel algorithms for the UBQP. This paper propose a novel
  decentralized parallel search algorithm, called Parallel Elite Biased Tabu Search
  (PEBTS). It is based on D2TS, a state-of-the-art sequential UBQP metaheuristic.
  The key strategies in the PEBTS algorithm include: (i) a lazy distributed cooperation
  procedure to maintain diversity among different search processes and (ii) finely
  tuned bit-flip operators which can help the search escape local optima efficiently.
  Our experiments on the Tianhe-2 supercomputer with up to 24 computing cores show
  the accuracy of the efficiency of PEBTS compared with a straightforward parallel
  algorithm running multiple independent and non-cooperating D2TS processes.'

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
  url: http://www.cec2017.org/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
