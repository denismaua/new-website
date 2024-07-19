---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Tractable inference in credal sentential decision diagrams
authors:
- Lilith Mattei
- Alessandro Antonucci
- Denis Deratani Mauá
- Alessandro Facchini
- Julissa Villanueva Llerena
date: '2020-01-01'
doi: 10.1016/j.ijar.2020.06.005

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-20T22:13:58.579228Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 2
publication: '*International Journal of Approximate Reasoning*'
publication_short: 'IJAR'

abstract: 'Probabilistic sentential decision diagrams are logic circuits where the
  inputs of disjunctive gates are annotated by probability values. They allow for
  a compact representation of joint probability mass functions defined over sets of
  Boolean variables, that are also consistent with the logical constraints defined
  by the circuit. The probabilities in such a model are usually “learned” from a set
  of observations. This leads to overconfident and prior-dependent inferences when
  data are scarce, unreliable or conflicting. In this work, we develop the credal
  sentential decision diagrams, a generalisation of their probabilistic counterpart
  that allows for replacing the local probabilities with (so-called credal) sets of
  mass functions. These models induce a joint credal set over the set of Boolean variables,
  that sharply assigns probability zero to states inconsistent with the logical constraints.
  Three inference algorithms are derived for these models. These allow to compute:
  (i) the lower and upper probabilities of an observation for an arbitrary number
  of variables; (ii) the lower and upper conditional probabilities for the state of
  a single variable given an observation; (iii) whether or not all the probabilistic
  sentential decision diagrams compatible with the credal specification have the same
  most probable explanation of a given set of variables given an observation of the
  other variables. These inferences are tractable, as all the three algorithms, based
  on bottom-up traversal with local linear programming tasks on the disjunctive gates,
  can be solved in polynomial time with respect to the circuit size. The first algorithm
  is always exact, while the remaining two might induce a conservative (outer) approximation
  in the case of multiply connected circuits. A semantics for this approximation together
  with an auxiliary algorithm able to decide whether or not the result is exact is
  also provided together with a brute-force characterization of the exact inference
  in these cases. For a first empirical validation, we consider a simple application
  based on noisy seven-segment display images. The credal models are observed to properly
  distinguish between easy and hard-to-detect instances and outperform other generative
  models not able to cope with logical constraints.'

# Summary. An optional shortened abstract.
summary: ''

tags: [probabilistic circuits, imprecise probability, robustness analysis]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://authors.elsevier.com/c/1bRq~,KD6ZRaqL
url_code: https://github.com/idsia/cjuice
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
