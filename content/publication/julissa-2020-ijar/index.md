---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Efficient Algorithms for Robustness Analysis of Maximum A Posteriori Inference
  in Selective Sum-Product Networks
authors:
- Julissa Villanueva Llerena
- Denis Deratani Mauá
date: '2020-01-01'
doi: 10.1016/j.ijar.2020.07.008

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-20T22:13:56.002273Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
- 2
publication: '*International Journal of Approximate Reasoning*'
#publication_short: IJAR

abstract: Sum-Product Networks (SPN) are deep probabilistic models with demonstrated
  excellent performance in several machine learning tasks. As with many other probabilistic
  models, performing Maximum-A-Posteriori inference in SPNs is NP-hard. Selective
  SPNs are a subclass of SPNs that allow for efficient Maximum-A-Posteriori inference
  and closed-form parameter learning. Due to the high number of parameters, SPNs learned
  from data can produce unreliable and overconfident inferences, especially for instances
  with low statistical support. This issue can be partially mitigated by performing
  a robustness analysis of inferences with respect to small changes in the parameters.
  In this work, we address the problem of assessing the robustness of Maximum-A-Posteriori
  inferences produced with Selective SPNs to global perturbations of the parameters.
  We consider such an inference robust if it remains the single maximizer under small
  perturbations of the model parameters. We present efficient algorithms and an empirical
  analysis with realistic problems involving missing data completion and multilabel
  classification. The experiments show that our criteria are informative with respect
  to the inference accuracy, suggesting that it indeed discriminate robust and non-robust
  instances.

# Summary. An optional shortened abstract.
summary: ''

tags: [sum-product networks, probabilistic circuits, robustness analysis]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
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
projects: [pq2020]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
