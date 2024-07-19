---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Algorithms and Complexity Results for Discrete Probabilistic Reasoning Tasks
authors:
- Denis Deratani Mauá
date: '2013-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-20T22:33:38.656884Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 7

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: Many solutions to problems in machine learning and artificial intelligence
  involve solving a combinatorial optimization problem over discrete variables whose
  functional dependence is conveniently represented by a graph. This thesis addresses
  three types of these combinatorial optimization problems, namely, the maximum a
  posteriori inference in discrete probabilistic graphical models, the selection of
  optimal strategies for limited memory influence diagrams, and the computation of
  upper and lower probability bounds in credal networks. These three problems arise
  out of seemingly very different situations, and one might believe that they share
  no more than the graph-based specification of their inputs or the underlying probabilistic
  treatment of uncertainty. However, correspondences among instances of these problems
  have long been noticed in the literature. For instance, the computation of probability
  bounds in credal networks can be reduced either to the problem of maximum a posteriori
  inference in graphical models, or to the selection of optimal strategies in limited
  memory influence diagrams. Conversely, both the maximum a posteriori inference and
  the strategy selection problems can be reduced to the computation of a probability
  bound in a credal network. These reductions suggest that much insight can be gained
  by carrying out a joint study of the practical and theoretical computational complexity
  of these three problems. This thesis describes algorithms and complexity results
  for these three classes of problems. In particular, we develop a new anytime algorithm
  for the maximum a posteriori problem. Not only the algorithm is of practical relevance,
  as we show that it compares favorably against a state-of-the-art method, but it
  is the base of the proof of polynomial-time approximability of the two other problems.
  We characterize the tractability of the strategy selection problem according to
  the input parameters, and we show that the strategy selection problem can be solved
  in polynomial time in singly connected diagrams over binary variables and univariate
  utility functions, and that relaxing any of these assumptions makes the problem
  NP-hard to solve or even approximate within any bound. We also investigate the theoretical
  complexity of computing upper and lower probability bounds in credal networks. We
  show that the complexity of the problem depends on the irrelevance concept adopted,
  but is in general NP-hard even in polytree-shaped networks, and even in trees if
  we assume strong independence. We also show that there is a particular type of inference
  that can be solved in polynomial time in imprecise hidden Markov models, whether
  we assume epistemic irrelevance or strong independence.

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

url_pdf: http://doc.rero.ch/record/203103?ln=en
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
