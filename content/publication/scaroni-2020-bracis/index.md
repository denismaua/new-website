---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: On the Performance of Planning Through Backpropagation
authors:
- Renato Scaroni
- Thiago P. Bueno
- Leliane N. de Barros
- Denis Mauá
date: '2020-01-01'
doi: '10.1007/978-3-030-61380-8_8'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10-21T13:55:23.498707Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 1

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 9th Brazilian Conference on Intelligent Systems*'
publication_short: 'BRACIS 2020'

abstract: Planning problems with continuous state and action spaces are difficult to solve with existing planning techniques, specially when the state transition is defined by a high-dimension non-linear dynamics. Recently, a technique called Planning through Backpropagation (PtB) was introduced as an efficient and scalable alternative to traditional optimization-based methods for continuous planning problems. PtB leverages modern gradient descent algorithms and highly optimized automatic differentiation libraries to obtain approximate solutions. However, to date there have been no empirical evaluations comparing PtB with Linear-Quadratic (LQ) control problems. In this work, we compare PtB with an optimal algorithm from control theory called LQR, and its iterative version iLQR, when solving linear and non-linear continuous deterministic planning problems. The empirical results suggest that PtB can be an efficient alternative to optimizing non-linear continuous deterministic planning, being much easier to be implemented and stabilized than classical model-predictive control methods.

# Summary. An optional shortened abstract.
summary: ''

tags: []
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
url_code:
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
