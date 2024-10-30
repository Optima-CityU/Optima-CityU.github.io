---
title: 'EB-GLS: an improved guided local search based on the big valley structure'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jialong Shi
- Qingfu Zhang
- Edward Tsang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2018-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:58.132098Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Memetic Computing*'
publication_short: ''

doi: 10.1007/s12293-017-0242-5

abstract: Local search is a basic building block in memetic algorithms. Guided local
  search (GLS) can improve the efficiency of local search. By changing the guide function,
  GLS guides a local search to escape from locally optimal solutions and find better
  solutions. The key component of GLS is its penalizing mechanism which determines
  which feature is selected to penalize when the search is trapped in a locally optimal
  solution. The original GLS penalizing mechanism only makes use of the cost and the
  current penalty value of each feature. It is well known that many combinatorial
  optimization problems have a big valley structure, i.e., the better a solution is,
  the more the chance it is closer to a globally optimal solution. This paper proposes
  to use big valley structure assumption to improve the GLS penalizing mechanism.
  An improved GLS algorithm called elite biased GLS (EB-GLS) is proposed. EB-GLS records
  and maintains an elite solution as an estimate of the globally optimal solutions,
  and reduces the chance of penalizing the features in this solution. We have systematically
  tested the proposed algorithm on the symmetric traveling salesman problem. Experimental
  results show that EB-GLS is significantly better than GLS.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Combinatorial optimization
- Elitism
- Guided local search
- Metaheuristics
- Traveling salesman problem

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
