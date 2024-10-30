---
title: Difficulty Adjustable and Scalable Constrained Multiobjective Test Problem
  Toolkit

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Zhun Fan
- Wenji Li
- Xinye Cai
- Hui Li
- Caimin Wei
- Qingfu Zhang
- Kalyanmoy Deb
- Erik Goodman

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-30T07:28:57.590308Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Evolutionary Computation*'
publication_short: ''

doi: 10.1162/evco_a_00259

abstract: Multiobjective evolutionary algorithms (MOEAs) have progressed significantly
  in recent decades, butmost of them are designed to solve unconstrained multiobjective
  optimization problems. In fact, many real-world multiobjective problems contain
  a number of constraints. To promote research on constrained multiobjective optimization,
  we first propose a problem classification scheme with three primary types of difficulty,
  which reflect various types of challenges presented by real-world optimization problems,
  in order to characterize the constraint functions in constrained multiobjective
  optimization problems (CMOPs). These are feasibility-hardness, convergence-hardness,
  and diversity-hardness. We then develop a general toolkit to construct difficulty
  adjustable and scalable CMOPs (DAS-CMOPs, or DAS-CMaOPs when the number of objectives
  is greater than three) with three types of parameterized constraint functions developed
  to capture the three proposed types of difficulty. In fact, the combination of the
  three primary constraint functions with different parameters allows the construction
  of a large variety of CMOPs, with difficulty that can be defined by a triplet, with
  each of its parameters specifying the level of one of the types of primary difficulty.
  Furthermore, the number of objectives in this toolkit can be scaled beyond three.
  Based on this toolkit, we suggest nine difficulty adjustable and scalable CMOPs
  and nine CMaOPs, to be called DAS-CMOP1-9 and DAS-CMaOP1-9, respectively. To evaluate
  the proposed test problems, two popular CMOEAs—MOEA/D-CDP (MOEA/D with constraint
  dominance principle) and NSGA-II-CDP (NSGA-II with constraint dominance principle)
  and two popular constrainedmany-objective evolutionary algorithms (CMaOEAs)—C-MOEA/DD
  and C-NSGA-III—are used to compare performance on DAS-CMOP1-9 and DAS-CMaOP1-9 with
  a variety of difficulty triplets, respectively. The experimental results reveal
  that mechanisms in MOEA/D-CDP may be more effective in solving convergence-hard
  DAS-CMOPs,while mechanisms of NSGA-II-CDP may bemore effective in solving DAS-CMOPs
  with simultaneous diversity-, feasibility-, and convergence-hardness. Mechanisms
  in C-NSGA-III may be more effective in solving feasibility-hard CMaOPs, while mechanisms
  of C-MOEA/DD may be more effective in solving CMaOPs with convergence-hardness.
  In addition, none of them can solve these problems efficiently, which stimulates
  us to continue to develop new CMOEAs and CMaOEAs to solve the suggested DAS-CMOPs
  and DAS-CMaOPs.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Constrained problems
- Controlled difficulties
- Evolutionary multiobjective optimization
- Test problems
- Constrained problems
- Controlled difficulties
- Evolutionary multiobjective optimization
- Test problems
- Constrained problems
- Controlled difficulties
- Evolutionary multiobjective optimization
- Test problems

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
