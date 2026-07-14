---
title: "Deep learning approach to determining the type of long reads"
authors:
- admin
- Megan Hong Hui Huang
- Robert Vaser
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
publication: "Poster presentation at *International Conference on Intelligent Systems for Molecular Biology - MLCSB COSI, 2020*"
publication_short: "Poster at *ISMB 2020 - MLCSB COSI*"

abstract: "Single and metagenome de novo assembly of long reads is still one of the most difficult problems in bioinformatics. Often used paradigm, called Overlap-Layout-Consensus, aims at finding a Hamiltonian path through an assembly graph obtained from overlapping reads in a sample. However, these graphs can be extremely complex due to repetitive regions in genomes and sequencing artifacts such as chimeric reads, which lead to higher fragmentation of the assembly genomes. A popular approach for tackling this problem is based on dividing reads into three categories and processing them appropriately. These three categories of reads are regular, repetitive, and chimeric. A drawback of read classification with heuristic algorithms in existing assemblers is a manual selection of parameters based on just several genomes. In this work, we propose a deep learning approach for classification of reads based on their pile-o-grams, plots of coverage versus base index. The model was trained on a hand-labeled dataset consisting of pile-o-gram images from multiple bacteria, and tested on a different bacteria species not included in the training set. With such a setup, and with classes being balanced, an accuracy of 93% was achieved which opens the possibility of creating more accurate and less contiguous assemblies."

# Summary. An optional shortened abstract.
summary: ''

tags:
- ONT Long Reads
- Convolutional Neural Networks

featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://www.iscb.org/ismb2020/scientific-programme/posters
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
