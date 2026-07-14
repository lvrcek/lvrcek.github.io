---
draft: false
title: 'GNNome-Decision: Enhancing GNN Training for de Novo Genome Assembly by Targeting Decision Nodes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Marijo Šimunović
  - admin
  - Mile Šikić
  - Anton Bankevich

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-06-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *BMC Bioinformatics*
publication_short: In *BMC Bioinformatics*

abstract: "Modern sequencing technologies have enabled the reconstruction of complete mammalian genomes from telomere to telomere. However, scaling this achievement to thousands of species and population-level studies remains a challenge. Key bottlenecks include the low quality of the draft assemblies and the high coverage requirements. In particular, reconstructing complete and accurate sequences of both haplotypes in diploid genomes is especially difficult since the sequencing depth is not always sufficient to properly reconstruct diverged regions. We aim to explore the use of machine learning, specifically graph neural networks, for scalable error correction in De Bruijn Graphs, addressing the limitations of existing heuristic methods in genome assembly. Inspired by the success of neural networks in extracting patterns from the data on a massive scale, we introduce a method for correcting errors in De Bruijn Graphs using Graph Neural Networks. Our model provides a reliable classification of edges into correct and erroneous, especially for diploid genomes with coverage depth 35 and lower. We demonstrate that these predictions can guide the downstream read error correction algorithm and genome assembly, ultimately allowing for more accurate genome assembly. Machine learning methods have the potential to replace heuristic methods commonly used in genome assembly. Learning-based approaches can enhance the performance of existing assemblers in challenging scenarios and facilitate adaptation to newly sequenced species."



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

url_pdf: https://link.springer.com/article/10.1186/s12859-026-06526-9
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

