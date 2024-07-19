---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Learning Probabilistic Sentential Decision Diagrams under Logic Constraints by Sampling and Averaging
subtitle: ''
summary: 'Probabilistic Sentential Decision Diagrams (PSDDs) are effective tools for combining uncertain knowledge in the form of (learned) probabilities and certain knowledge in the form of logical constraints. Despite some promising recent advances in the topic, very little attention has been given to the problem of effectively learning PSDDs from data and logical constraints in large domains. In this paper, we show that a simple strategy of sampling and averaging PSDDs leads to state-of-the-art performance in many tasks. We overcome some of the issues with previous methods by employing a top-down generation of circuits from a logic formula represented as a BDD. We discuss how to locally grow the circuit while achieving a good trade-off between complexity and goodness-of-fit of the resulting model. Generalization error is further decreased by aggregating sampled circuits through an ensemble of models. Experiments with various domains show that the approach efficiently learns good models even in very low data regimes, while remaining competitive for large sample sizes.'
authors:
- Renato Lui Geh
- Denis Deratani Mauá
tags: [probabilistic circuits]
categories: [probabilistic circuits]
date: '2021-01-01'
lastmod: 2021-08-25T12:45:56-03:00
featured: true
draft: false

url_pdf: https://proceedings.mlr.press/v161/geh21a.html

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [pq2020]
publishDate: '2021-08-25T15:45:55.728304Z'
publication_types:
- '1'
abstract: ''
publication: '*Proceedings of the 37th Conference on Uncertainty in Artificial Intelligence*'
---
