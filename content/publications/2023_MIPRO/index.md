---
draft: false
title: 'Reconstruction of short genomic sequences with graph convolutional networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xavier Bresson
  - Thomas Laurent
  - Martin Schmitz
  - Mile Šikić

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-22T00:00:00Z'
doi: '10.23919/MIPRO57284.2023.10159916'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *46th MIPRO ICT and Electronics Convention (MIPRO)*
publication_short: In *46th MIPRO ICT and Electronics Convention (MIPRO)*

abstract: "Genome reconstruction, without prior knowledge about the sequence we are reconstructing, is performed with tools called de novo genome assemblers. These tools rely on numerous heuristics and usually provide a fragmented reconstruction, even for sequences shorter than the entire genomes or chromosomes. One of the most common approaches to de novo assembly, called Overlap-Layout-Consensus, constructs a graph from short overlapping fragments, which heuristics then simplify and find a path through. In this work, we explore how graph neural networks (GNNs) can assist with this task, and show that the GNN-based Layout phase can reconstruct longer sequences than naive search algorithms or heuristics deployed in de novo assemblers, with no significant difference in compute time on sequences up to 10 Mbp in length."



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

url_pdf: https://ieeexplore.ieee.org/abstract/document/10159916
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

