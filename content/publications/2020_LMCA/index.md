---
title: "A step towards neural genome assembly"
authors:
- admin
- Petar Veličković
- Mile Šikić

date: "2020-11-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["workshop"]

# Publication name and optional abbreviated publication name.
publication: "Poster presentation at *[Learning Meets Combinatorial Optimization](https://sites.google.com/view/lmca2020/home) @ NeurIPS 2020*"
publication_short: "Poster at *LMCA workshop @ NeurIPS 2020*"

abstract: De novo genome assembly focuses on finding connections between a vast amount of short sequences in order to reconstruct the original genome. The central problem of genome assembly could be described as finding a Hamiltonian path through a large directed graph with a constraint that an unknown number of nodes and edges should be avoided. However, due to local structures in the graph and biological features, the problem can be reduced to graph simplification, which includes removal of redundant information. Motivated by recent advancements in graph representation learning and neural execution of algorithms, in this work we train the MPNN model with max-aggregator to execute several algorithms for graph simplification. We show that the algorithms were learned successfully and can be scaled to graphs of sizes up to 20 times larger than the ones used in training. We also test on graphs obtained from real-world genomic data---that of a lambda phage and E. coli.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Neural algorithmic reasoning
- De novo genome assembly

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2011.05013
url_code: ''
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
