---
title: 'DipGNNome: Diploid de Novo Genome Assembly with Geometric Deep Learning and Beam-Search'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Martin Schmitz
  - admin
  - Kenji Kawaguchi
  - Mile Šikić

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

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

abstract: De novo genome assembly remains a central challenge in computational biology, particularly for diploid genomes where maternal and paternal haplotypes must be accurately resolved. Existing assemblers achieve impressive results through carefully designed heuristics, yet modern deep learning methods remain largely unexplored in the diploid setting. We present DipGNNome, the first deep learning–based framework for diploid de novo genome assembly. Our approach formulates genome assembly as an edge classification and graph traversal problem, given haplotype-aware assembly graphs. We train a graph neural network (GNN) to guide contig construction as the layout phase in an Overlap-Layout-Consensus genome assembly pipeline. To enable this, we establish a novel pipeline for generating diploid graphs with ground-truth edge labels, providing the first systematic way to produce training data for machine learning models in this domain. This framework creates a foundation for applying and extending graph-based deep learning to diploid assembly. DipGNNome creates assemblies comparable to SotA and demonstrates the feasibility of deep learning for diploid assembly and introduces a paradigm that bridges algorithmic genomics with graph representation learning.

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

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-032-26891-4_15'
url_code: 'https://github.com/lbcb-sci/DipGNNome'
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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

