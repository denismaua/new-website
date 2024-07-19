---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Exploration Versus Exploitation in Model-Based Reinforcement Learning: An
  Empirical Study'
subtitle: ''
summary: ''
authors:
- Ângelo Gregório Lovatto
- Leliane Nunes de Barros
- Denis D. Mauá
tags: [reinforcemente learning]
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
publishDate: '2022-11-18T13:35:39.456351Z'
publication_types:
- '1'
abstract: 'Model-based Reinforcement Learning (MBRL) agents use data collected by
  exploration of the environment to produce a model of the dynamics, which is then
  used to select a policy that maximizes the objective function. Stochastic Value
  Gradient (SVG) methods perform the latter step by optimizing some estimate of the
  value function gradient. Despite showing promising empirical results, many implementations
  of SVG methods lack rigorous theoretical or empirical justification; this casts
  doubts as to whether good performance are in large part due to the benchmark-overfitting.
  To better understand the advantages and shortcomings of existing SVG methods, in
  this work we carry out a fine-grained empirical analysis of three core components
  of SVG-based agents: (i) the gradient estimator formula, (ii) the model learning
  and (iii) the value function approximation. To this end, we extend previous work
  that proposes using Linear Quadratic Gaussian (LQG) regulator problems to benchmark
  SVG methods. LQG problems are heavily studied in optimal control literature and
  deliver challenging learning settings while still allowing comparison with ground-truth
  values. We use such problems to investigate the contribution of each core component
  of SVG methods to the overall performance. We focus our analysis on the model learning
  component, which was neglected from previous work, and we show that overfitting
  to on-policy data can lead to accurate state predictions but inaccurate gradients,
  highlighting the importance of exploration also in model-based methods.'
publication: '*Intelligent Systems*'
---
