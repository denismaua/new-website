---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An Ensemble of Bayesian Networks for Multilabel Classification
authors:
- Alessandro Antonucci
- Giorgio Corani
- Denis Deratani Mauá
- Sandra Gabaglio
date: '2013-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-20T22:36:04.380971Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 1

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 23rd International Joint Conference on Artificial
  Intelligence*'
publication_short: 'IJCAI 2015'

abstract: We present a novel approach for multilabel classification based on an ensemble
  of Bayesian networks. The class variables are connected by a tree; each model of
  the ensemble uses a different class as root of the tree. We assume the features
  to be conditionally independent given the classes, thus generalizing the naive Bayes
  assumption to the multiclass case. This assumption allows us to optimally identify
  the correlations between classes and features; such correlations are moreover shared
  across all models of the ensemble. Inferences are drawn from the ensemble via logarithmic
  opinion pooling. To minimize Hamming loss, we compute the marginal probability of
  the classes by running standard inference on each Bayesian network in the ensemble,
  and then pooling the inferences. To instead minimize the subset 0/1 loss, we pool
  the joint distributions of each model and cast the problem as a MAP inference in
  the corresponding graphical model. Experiments show that the approach is competitive
  with state-of-the-art methods for multilabel classification.

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

url_pdf: http://ijcai.org/papers13/Papers/IJCAI13-184.pdf
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
