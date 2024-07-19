---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Cautious Classification with Data Missing Not at Random using Generative Random Forests
subtitle: ''
summary: 'Missing data present a challenge for most machine learning approaches. When a generative probabilistic model of the data is available, an effective approach is to marginalize missing values out. Probabilistic circuits are expressive generative models that allow for efficient exact inference. However, data is often missing not at random, and marginalization can lead to overconfident and wrong conclusions. In this work, we develop an efficient algorithm for assessing the robustness of classifications made by probabilistic circuits to imputations of the non-ignorable portion of missing data at prediction time. We show that our algorithm is exact when the model satisfies certain constraints, which is the case for the recent proposed Generative Random Forests, that equip Random Forest Classifiers with a full probabilistic model of the data. We also show how to extend our approach to handle non-ignorable missing data at training time.'
authors:
- Julissa Giuliana Villanueva Llerena
- Denis Deratani Mauá
- Alessandro Antonucci
tags: [probabilistic circuits, missing data]
categories: []
date: '2021-01-01'
lastmod: 2021-08-25T12:59:06-03:00
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
projects: [pq2020]
publishDate: '2021-08-25T15:59:05.808216Z'
publication_types:
- '1'
abstract: ''
publication: '*Proceedings of the Sixteenth European Conference on Symbolic and Quantitative
  Approaches to Reasoning with Uncertainty*'
---
