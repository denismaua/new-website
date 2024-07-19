---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Time Robust Trees: Using Temporal Invariance to Improve Generalization'
subtitle: ''
summary: ''
authors:
- Luis Moneda
- Denis Mauá
tags: [random forests]
categories: []
date: '2022-01-01'
lastmod: 2022-11-18T10:35:51-03:00
featured: false
draft: false

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
projects: []
publishDate: '2022-11-18T13:35:51.639624Z'
publication_types:
- '1'
abstract: As time passes by, the performance of real-world predictive models degrades
  due to distributional shifts and learned spurious correlations. Typical countermeasures,
  such as retraining and online learning, can be costly and challenging in production,
  especially when accounting for business constraints and culture.  Causality-based
  approaches aim to identify invariant mechanisms from data, thus leading to more
  robust predictors at the possible expense of decreasing short-term performance.
  However, most such approaches scale poorly to high dimensions or require extra knowledge
  such as data segmentation in representative environments.  In this work, we develop
  the Time Robust Trees, a new algorithm for inducing decision trees with an inductive
  bias towards learning time-invariant rules. The algorithm's main innovation is to
  replace the usual information-gain split criterion (or similar) with a new criterion
  that examines the imbalance among classes induced by the split through time. Experiments
  with real data show that our approach improves long-term generalization, thus offering
  an exciting alternative for classification problems under distributional shift.
publication: '*Intelligent Systems*'
---
