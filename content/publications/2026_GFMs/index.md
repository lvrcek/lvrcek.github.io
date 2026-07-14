---
title: "Entropy, Disagreement, and the Limits of Foundation Models in Genomics"
authors:
- Maxime Rochkoulets
- admin
- Mile Šikić

date: "2026-04-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["workshop"]

# Publication name and optional abbreviated publication name.
publication: "Poster presentation at *[Learning Meaningful Representations of Life workshop](https://www.lmrl.org/) @ ICLR 2026*"
publication_short: "Poster at *LMRL workshop @ ICLR 2026*"

abstract: Foundation models in genomics have shown mixed success compared to their counterparts in natural language processing. Yet, the reasons for their limited effectiveness remain poorly understood. In this work, we investigate the role of entropy as a fundamental factor limiting the capacities of such models to learn from their training data and develop foundational capabilities. We train ensembles of models on text and DNA sequences and analyze their predictions, static embeddings, and empirical Fisher information flow. We show that the high entropy of genomic sequences---from the point of view of unseen token prediction---leads to near-uniform output distributions, disagreement across models, and unstable static embeddings, even for models that are matched in architecture, training and data. We then demonstrate that models trained on DNA concentrate Fisher information in embedding layers, seemingly failing to exploit inter-token relationships. Our results suggest that self-supervised training from sequences alone may not be applicable to genomic data, calling into question the assumptions underlying current methodologies for training genomic foundation models.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Genomic Foundation Models
- Embedding Analysis

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2604.04287
url_code: 'https://github.com/lbcb-sci/GFMs'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""

---


<!--
This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
-->
