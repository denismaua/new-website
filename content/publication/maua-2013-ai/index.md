---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: On the complexity of solving polytree-shaped limited memory influence diagrams
  with binary variables
authors:
- Denis Deratani Mauá
- Cassio Polpo de Campos
- Marco Zaffalon
date: '2013-01-01'
doi: 10.1016/j.artint.2013.10.002

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-20T22:33:44.672296Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 2

# Publication name and optional abbreviated publication name.
publication: '*Artificial Intelligence*'
publication_short: ''

abstract: Influence diagrams are intuitive and concise representations of structured
  decision problems. When the problem is non-Markovian, an optimal strategy can be
  exponentially large in the size of the diagram. We can avoid the inherent intractability
  by constraining the size of admissible strategies, giving rise to limited memory
  influence diagrams. A valuable question is then how small do strategies need to
  be to enable efficient optimal planning. Arguably, the smallest strategies one can
  conceive simply prescribe an action for each time step, without considering past
  decisions or observations. Previous work has shown that finding such optimal strategies
  even for polytree-shaped diagrams with ternary variables and a single value node
  is NP-hard, but the case of binary variables was left open. In this paper we address
  such a case, by first noting that optimal strategies can be obtained in polynomial
  time for polytree-shaped diagrams with binary variables and a single value node.
  We then show that the same problem is NP-hard if the diagram has multiple value
  nodes. These two results close the fixed-parameter complexity analysis of optimal
  strategy selection in influence diagrams parametrized by the shape of the diagram,
  the number of value nodes and the maximum variable cardinality.

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

url_pdf: http://ipg.idsia.ch/preprints/maua2013b.pdf
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
