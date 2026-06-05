---
title: "Geometric deep learning framework for de novo genome assembly"
authors:
- admin
- Xavier Bresson
- Thomas Laurent
- Martin Schmitz
- Kenji Kawaguchi
- Mile Šikić
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-04-15"
doi: "10.1101/gr.279307.124"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Genome Research, 35*(4)"
publication_short: ""

abstract: The critical stage of every de novo genome assembler is identifying paths in assembly graphs that correspond to the reconstructed genomic sequences. The existing algorithmic methods struggle with this, primarily due to repetitive regions causing complex graph tangles, leading to fragmented assemblies. Here, we introduce GNNome, a framework for path identification based on geometric deep learning that enables training models on assembly graphs without relying on existing assembly strategies. By leveraging only the symmetries inherent to the problem, GNNome reconstructs assemblies from PacBio HiFi reads with contiguity and quality comparable to those of the state-of-the-art tools across several species. With every new genome assembled telomere-to-telomere, the amount of reliable training data at our disposal increases. Combining the straightforward generation of abundant simulated data for diverse genomic structures with the AI approach makes the proposed framework a plausible cornerstone for future work on reconstructing complex genomes with different degrees of ploidy and aneuploidy. To facilitate such developments, we make the framework and the best-performing model publicly available, provided as a tool that can directly be used to assemble new haploid genomes.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Geometric Deep Learning
# - Graph Neural Networks
- Genome Assembly

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://genome.cshlp.org/content/early/2025/03/14/gr279307124
url_code: https://github.com/lbcb-sci/GNNome
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---
