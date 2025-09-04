---
title: Investigating Universal Adversarial Attacks Against Transformers-Based Automatic
  Essay Scoring Systems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Igor Cataneo Silveira
- André Barbosa
- Daniel Silva Lopes da Costa
- admin

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-02-03T18:56:59.082249Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Intelligent Systems*'
publication_short: ''

doi: 10.1007/978-3-031-79032-4_12

abstract: Automatic Essay Scoring promises to scale up student feedback on written
  input, addressing the excessive cost and time demand associated with human grading.
  State-of-the-art automatic scorers are based on Transformers-based neural networks.
  While such models have shown impressive results in reasoning tasks, learned models
  often produce answers that arise from statistical clues in datasets and are misaligned
  with human objectives. Such systems are thus potentially fragile for scenarios where
  users are incentivized to deceive the system, as in a classroom setting. In this
  work, we evaluate the susceptibility of state-of-the-art automatic scorers to attacks
  made by non-expert users, such as students interacting with an automatic grader.
  We develop a methodology to simulate such student attacks and test them against
  scorers based on BERT, Phi-3 and Gemini models. Our findings suggest that (i) a
  BERT-based grader can be deceived using simple feature-based attacks; (ii) although
  Google's Gemini has a solid agreement with graders, it can assign undeservedly high
  grades for small sentences; (iii) a Phi-3-based grader was less susceptible than
  BERT, but it still assigned relatively high grades to some of our attacks.

# Summary. An optional shortened abstract.
summary: ''

tags: [automatic essay evaluation]

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: '/~ddm/publication/silveira-2024-bracis/silveira2024bracis.pdf'
url_code: ''
url_dataset: 'https://huggingface.co/datasets/kamel-usp/aes_enem_dataset'
url_poster: ''
url_project: ''
url_slides: 'slides.pdf'
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['neuroproblog']
---

