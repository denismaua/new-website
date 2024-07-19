---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Speeding Up k-Neighborhood Local Search in Limited Memory Influence Diagrams
authors:
- Denis Deratani Mauá
- Fabio Gagliardi Cozman
date: '2014-01-01'
doi: 10.1007/978-3-319-11433-0_22

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-20T22:34:06.166341Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 1

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 7th European Workshop on Probabilistic Graphical
  Models*'
publication_short: 'PGM'

abstract: Limited memory influence diagrams are graph-based models that describe decision
  problems with limited information, as in the case of teams and agents with imperfect
  recall. Solving a (limited memory) influence diagram is an NP-hard problem, often
  approached through local search. In this paper we investigate algorithms for k-neighborhood
  local search. We show that finding a k-neighbor that improves on the current solution
  is W[1]-hard and hence unlikely to be polynomial-time tractable. We then develop
  fast schema to perform approximate k-local search; experiments show that our methods
  improve on current local search algorithms both with respect to time and to accuracy.

# Summary. An optional shortened abstract.
summary: ''

tags: [decision making, limid, influence diagrams]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code: https://github.com/denismaua/kpu-pp
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
