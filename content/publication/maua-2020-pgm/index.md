---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Two Reformulation Approaches to Maximum-A-Posteriori Inference in Sum-Product
  Networks
authors:
- Denis Deratani Mauá
- Heitor Reis Ribeiro
- Gustavo Perez Katague
- Alessandro Antonucci
date: '2020-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-03-09T22:59:16.059450Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 1
publication: '*Proceedings of the Tenth International Conference on Probabilistic Graphical Models*'
publication_short: PGM 2020

abstract: 'Sum-product networks are expressive efficient probabilistic graphical models that allow for tractable marginal inference. Many tasks however require the computation of maximum-a-posteriori configurations, an NP-Hard problem for such models. To date there have been very few proposals for computing maximum-a-posteriori configurations in sum-product networks. This is in sharp difference with other probabilistic frameworks such as Bayesian networks and random Markov fields, where the problem is also NP-hard. In this work we propose two approaches to reformulate maximum-a-posteriori inference as other combinatorial optimization problems with widely available solvers. The first approach casts the problem as a similar inference problem in Bayesian networks, overcoming some limitations of previous similar translations. In addition to making available the toolset of maximum-a-posteriori inference on Bayesian networks to sum-product networks, our reformulation also provides further insight into the connections of these two classes of models. The second approach casts the problem as a mixed-integer linear program, for which there exists very efficient solvers. This allows such inferences to be enriched with integer-linear constraints, increasing the expressivity of the models. We compare our reformulation approaches in a large collection of problems, and against state-of-the-art approaches. The results show that reformulation approaches are competitive.'

# Summary. An optional shortened abstract.
summary: ''

tags: [sum-product networks, probabilistic circuits]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://proceedings.mlr.press/v138/maua20a/maua20a.pdf
url_code: https://gitlab.com/pgm-usp/pyspn
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
