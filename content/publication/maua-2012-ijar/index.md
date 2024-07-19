---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Updating Credal Networks is Approximable in Polynomial Time
authors:
- Denis Deratani Mauá
- Cassio Polpo de Campos
- Marco Zaffalon
date: '2012-01-01'
doi: 10.1016/j.ijar.2012.06.014

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-20T22:33:04.025232Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 2

# Publication name and optional abbreviated publication name.
publication: '*International Journal of Approximate Reasoning*'
publication_short: ''

abstract: Credal networks relax the precise probability requirement of Bayesian networks,
  enabling a richer representation of uncertainty in the form of closed convex sets
  of probability measures. The increase in expressiveness comes at the expense of
  higher computational costs. In this paper, we present a new variable elimination
  algorithm for exactly computing posterior inferences in extensively specified credal
  networks, which is empirically shown to outperform a state-of-the-art algorithm.
  The algorithm is then turned into a provably good approximation scheme, that is,
  a procedure that for any input is guaranteed to return a solution not worse than
  the optimum by a given factor. Remarkably, we show that when the networks have bounded
  treewidth and bounded number of states per variable the approximation algorithm
  runs in time polynomial in the input size and in the inverse of the error factor,
  thus being the first known fully polynomial-time approximation scheme for inference
  in credal networks.

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

url_pdf: http://www.sciencedirect.com/science/article/pii/S0888613X12000904?v=s5
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
