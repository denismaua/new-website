---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Decision-Aware Model Learning for Actor-Critic Methods: When Theory Does Not Meet Practice'
authors:
- Ângelo G. Lovatto
- Thiago P. Bueno
- Denis D. Mauá
- Leliane N. de Barros
date: '2020-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-12-02T13:33:53.447551Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 1

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the First I Can't Believe It's Not Better Workshop*"
publication_short: 'ICBINB@NeurIPS 2020'

abstract: 'Actor-Critic methods are a prominent class of modern reinforcement learning algorithms based on the classic Policy Iteration procedure. Despite many successful cases, Actor-Critic methods tend to require a gigantic number of experiences and can be very unstable. Recent approaches have advocated learning and using a world model to improve sample efficiency and reduce reliance on the value function estimate. However, learning an accurate dynamics model of the world remains challenging, often requiring computationally costly and data-hungry models. More recent work has shown that learning an everywhere accurate model is unnecessary and often detrimental to the overall task; instead, the agent should improve the world model on task-critical regions. For example, in Iterative Value-Aware Model Learning, the authors extend model-based value iteration by incorporating the value function (estimate) into the model loss function, showing the novel model objective reflects improved performance in the end task. Therefore, it seems natural to expect that model-based Actor-Critic methods can benefit equally from learning value-aware models, improving overall task performance, or reducing the need for large, expensive models. However, we show empirically that combining  Actor-Critic and value-aware model learning can be quite difficult and that naive approaches such as maximum likelihood estimation often achieve superior performance with less computational cost. Our results suggest that, despite theoretical guarantees, learning a value-aware model in continuous domains does not ensure better performance on the overall task.'

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

url_pdf: http://proceedings.mlr.press/v137/lovatto20a/lovatto20a.pdf
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
