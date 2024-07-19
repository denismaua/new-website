---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Efficient algorithms for Risk-Sensitive Markov Decision Processes with limited
  budget
subtitle: ''
summary: ''
authors:
- Daniel A. Melo Moreira
- Karina Valdivia Delgado
- Leliane Nunes de Barros
- Denis Deratani Mauá
tags:
- '"Probabilistic planning"'
- '"Markov decision processes"'
- '"Risk-Sensitive Markov decision processes"'
categories: [probabilistic planning]
date: '2021-01-01'
lastmod: 2021-10-08T11:41:46-03:00
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
publishDate: '2021-10-08T14:41:46.112098Z'
publication_types:
- '2'
abstract: We tackle the problem of finding optimal policies for Markov Decision Processes,
  that minimize the probability of the cumulative cost exceeding a given budget. Such
  task falls under the umbrella of Risk-Sensitive Markov Decision Processes, which
  optimize a non-additive, non-linear function of cumulative cost that incorporates
  the user's attitude towards risk. Current algorithms for solving that task, for
  any budget equal or smaller than an user-defined budget, scale poorly when the support
  of the cost function is large, since they operate in an augmented state space which
  enumerates all possible remaining budgets. To circumvent this issue, we develop
  (i) an improved version of the Topological Value Iteration with Dynamic Programming
  algorithm (tvi-dp), and (ii) the first symbolic dynamic programming algorithm for
  this class of problems, called rs-spudd, that exploits conditional independence
  in the transition function in the augmented state space. The proposed algorithms
  improve efficiency by pruning irrelevant states and terminating early, without sacrificing
  optimality. Empirical results show that rs-spudd is able to solve problems up to
  103 times larger than tvi-dp.
publication: '*International Journal of Approximate Reasoning*'
url_pdf: https://www.sciencedirect.com/science/article/pii/S0888613X21001389
doi: https://doi.org/10.1016/j.ijar.2021.09.003
---
