---
draft: false
title: 'GNNome-Decision: Enhancing GNN Training for de Novo Genome Assembly by Targeting Decision Nodes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Martin Schmitz
  - admin
  - Kenji Kawaguchi
  - Mile Šikić

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-05-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *RECOMB International Workshop on Comparative Genomics*
publication_short: In *RECOMB-CG*

abstract: "De novo genome assembly, the reconstruction of complete DNA sequences from reads without the use of a reference genome, remains one of the most challenging and fundamental problems in computational biology. A common method for de novo genome assembly involves creating an assembly graph of reads and defining a graph traversal that represents the genomic sequence. Recently, the first deep learning-based method, GNNome, was proposed to tackle this problem. Starting from an assembly graph, GNNome performs de novo assembly in two steps: binary edge classification and a greedy walk. However, we observe that the decisions of the greedy agent only matter in 0.86% of nodes. In this paper, we develop an objective function based on margin-ranking loss for GNN training that focuses on these decision nodes, effectively aligning the training objective with the performance of the downstream task of greedy pathfinding. Furthermore, we introduce a modification to the dataset creation pipeline, which increases the fraction of decision nodes by more than tenfold to 9.35%, strongly enhancing the information density in the training dataset. Trained on only human data, our model improves the NGA50 score compared to GNNome on the CHM13 human genome from 111.0 Mb to 115.8 Mb, while achieving similar assembly quality on three non-human real genomes, consistently increasing assembly completeness and decreasing duplicated genes."



# Summary. An optional shortened abstract.
summary: ""

tags:
  - Geometric Deep Learning
  - Genome Assembly

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://link.springer.com/chapter/10.1007/978-3-032-26891-4_16
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: ""
---


<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

