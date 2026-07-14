---
draft: false
title: 'Graph Neural Network Meets de Bruijn Genome Assembly'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Marijo Šimunović
  - admin
  - Mile Šikić

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-18T00:00:00Z'
doi: '10.1109/ISPA58351.2023.10279343'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 International Symposium on Image and Signal Processing and Analysis (ISPA)*
publication_short: In *ISPA 2023*

abstract: "The genome assembly problem, which involves reconstructing the sequence of nucleotides in a DNA molecule from its short, error-prone substrings called reads, is one of the most extensively studied computational problems in biology. The majority of existing solutions for this problem rely on representing input reads in the form of an assembly graph, where each vertex and edge represents a sequence of nucleotides, and the genome corresponds to a path in this graph. However, assembly graphs often contain millions of erroneous edges due to read errors, which significantly complicates the graph analysis. Traditionally, these erroneous edges are detected and removed using a variety of heuristics. However, these heuristics often require manual parameter tuning. In this paper, we propose a novel approach to detect erroneous edges in a specific type of assembly graph called the de Bruijn graph. We employ a graph neural network-based architecture to detect these erroneous edges, replacing the corresponding heuristic step in traditional genome assembly algorithms. To overcome the lack of datasets with known ground truth, we simulate realistic read sets using error profiles learned from real reads. We propose a new method for erroneous edge classification in de Bruijn graph that relies on Graph Neural Networks. In our experiments, we demonstrate that the new method can reliably replace a more complicated heuristic approach and reduce the overall execution time."



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

url_pdf: https://ieeexplore.ieee.org/abstract/document/10279343
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

