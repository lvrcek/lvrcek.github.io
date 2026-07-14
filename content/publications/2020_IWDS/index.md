---
title: "Supervised learning approach to long read classification"
authors:
- admin
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
publication: "Poster presentation at *4rd International Workshop on Data Science (IWDS 2019)*"
publication_short: "Poster at *IWDS 2019*"

abstract: "Determining the complete genetic material of an organism is a central task of genomics as it would enable various applications in medicine and biotechnology. In order to make that possible, several techniques for DNA sequencing have been developed. The most recent approach, called third generation sequencing technology, provides us with DNA sequences of length that can surpass a 100, 000 bases, but that comes at a cost of high sequencing error which is often greater than 15%. The most popular approach for assembling the genome using the mentioned sequences, also called reads, is based on the OLC paradigm which consists of three steps: overlap, layout and consensus. In the overlap phase all the reads are mutually aligned which provides an overlap graph. In the assembly step such graph has to be simplified in order to obtain the Hamiltonian path which defines the assembly genome. In the final phase, consensus, the polishing of the assembly genome is performed by comparing the assembly with the reads obtained from the sequencer. However, not only is finding a Hamiltonian path in a graph an NP-hard problem, but due to high error rate of the third generation sequencers the overlap graph can also be overly complex. In order to avoid that, reads are first analyzed and divided into three groups: regular, chimeric and repeat. When mapped to the reference genome, regular reads have uniform coverage since they have a unique position in the genome. Chimeric reads are usually created as a flaw of sequencer which connects two distant regions into a single read which is characterized as a sudden drop in coverage. Repeat reads have a significantly higher coverage at either end of a read, originating from overlap of bases from that end with multiple positions on a reference genome. The first assembly tool to perform such analysis was HINGE [1]. It observes pile-o-grams of each read, which are plots of coverage versus base index. Another tool that utilizes similar method is Ra [2]. It stores signals from pile-o- grams into vectors of unsigned short integers and calculates the coverage slope at each position by keeping the sliding window on both sides of the observed position. The importance of identifying reads as chimeric and repeats is that they can produce complex overlap graph or add errors into the assembly. Therefore, each type is dealt in its own manner: chimeric reads are cut and only the longest non-chimeric region is retained and ridges are removed from repeat. In this work, we introduce a supervised learning approach for solving this problem. Since the main goal is to improve de-novo genome assembly reads are not mapped onto the reference, but onto each other. This introduces noise into the pile-o- grams and makes the classification more difficult. To deal with that, reads are also mapped onto the reference using the ratlesnake tool [3] which helps classify dubious reads during the training. The training is performed on grayscale images of pile-o-grams on a dataset of 5.000 reads of each class, using the convolutional neural networks. Accuracy obtained for regular reads is 88.93 %, for chimeric 88.17 %, while for repeat reads it is 86.99 %. Code can be found at https://github.com/lvrcek/LongReadClassification under the MIT license."

# Summary. An optional shortened abstract.
summary: ''

tags:
- ONT Long Reads
- Convolutional Neural Networks

featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://www.croris.hr/dogadanja/dogadanje/47959
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
