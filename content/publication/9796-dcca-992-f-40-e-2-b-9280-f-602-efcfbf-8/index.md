---
title: Efficient Greedy Decremental Hypervolume Subset Selection Using Space Partition
  Tree

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jingda Deng
- Jianyong Sun
- Qingfu Zhang
- Hui Li

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.302967Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Evolutionary Computation*'
publication_short: ''

doi: 10.1109/TEVC.2024.3400801

abstract: In the realm of evolutionary multiobjective optimization, the hypervolume
  indicator serves as a crucial metric for assessing the quality of solution sets.
  Due to the high costs in hypervolume computation, hypervolume-based optimization
  algorithms always meet the challenge of finding a certain number of points in a
  given point set to maximize the hypervolume indicator, especially when there are
  many objectives. In response, the greedy decremental algorithm for hypervolume subset
  selection problem (gHSSD) has emerged as a noteworthy alternative. This paper introduces
  a general algorithm for gHSSD, applicable in any dimensionality above two. The proposed
  algorithm leverages a space partition tree and incorporates a once-build-multiple-use
  strategy, effectively reducing time complexity. We prove that the proposed algorithm
  has a time complexity of O((n-k+n)nd-12logn) where n is the number of points, k
  is the number of points to be reserved, and d the dimensionality. Theoretically,
  this complexity is competitive with the current best algorithms for d=3,4 and better
  than them for all 5≤d≤7. To validate our algorithm, we have conducted extensive
  tests on various random point sets and multiobjective optimization benchmarks. Experimental
  results suggest that our implementation is more efficient than or competitive with
  state-of-the-art algorithms on many instances as n increases for d=3,4. © 2024 IEEE.
  Personal use is permitted, but republication/redistribution requires IEEE permission.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Complexity analysis
- Greedy hypervolume subset selection
- Hypervolume indicator
- Multiobjective optimization
- Space partition method

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
