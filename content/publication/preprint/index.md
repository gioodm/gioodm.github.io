---
title: "WASP: A pipeline for functional annotation based on AlphaFold structural models"
authors:
- Del Missier, Shabestary, Ledesma-Amaro
date: "2024-07-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: WASP, <ins>W</ins>hole-proteome <ins>A</ins>nnotation through <ins>S</ins>tructural-homology <ins>P</ins>ipeline, is a python-based software leveraging structural homology to enhance protein annotation at scale, providing a more comprehensive understanding of protein functions across various organisms. WASP relies on network topology for better accuracy and more robust statistical power. WASP highlights the importance of structural homology in systematically identifying novel annotations which were previously missed by sequence-based tools.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
 genome annotation, structural alignment, genome-scale model, alphafold

featured: true

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/gioodm/WASP'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '**Overview of WASP workflow**.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

### Summary

- **WASP Overview**: WASP is a novel pipeline for protein functional annotation starting from AlphaFold structure models. Using the output of state-of-the-art structural annotation tools, the proteome of a query organism is linked to structural homologs present in the AlphaFold database, creating a network whose topology is exploited to perform functional enrichment. In addition, WASP provides a holistic and comprehensive characterisation of proteins, using a diverse set of descriptors that provide a rich understanding of their molecular function.

- **Structural Homology Advantage**: Previous methods primarily relied on sequence information to achieve annotation. However, protein structure is a major determinant in protein function, and it is known that structure is evolutionary more conserved while sequence divergence is more common. WASP is the first bioinformatic tool based on structure to annotate organisms at the whole-proteome level. WASP provides a user-friendly framework that allows advanced protein function prediction accessible to a broad range of researchers, from computational biologists to experimental scientists.

- **Benchmarking Performance**: We benchmark WASP against multiple datasets and several state-of-the-art tools. We focus on classification based on EC numbers, a widespread system for enzyme activity categorisation. On hidden labels, WASP achieved superior F1 scores compared to state-of-the-art tools using sequence homology.

- **Improved Annotation and Industrial Application**: WASP improved annotation in a cohort of industrially relevant organisms by 20-30% for previously uncharacterised proteins and successfully annotated a novel isolate of the yeast _Yarrowia lipolytica_. By improving annotation levels of high-potential organisms, WASP enhances the exploitation of their biological capabilities for various biotechnological applications.

- **Genome-Scale Metabolic Models (GEMs)**: WASP curated GEMs by gap-filling orphan reactions, identifying candidates for 75-100% of these reactions across 20 GEMs, based on plausible biological associations and providing insights into protein evolution. These results enhance out ability to perform quantitative biological analyses, enabling the construction of more accurate and predictive metabolic network models for better understanding and manipulation of biological systems.

- **Phylogenetic Tree Reconstruction**: WASP provides superior clade discrimination in phylogenetic studies, offering precise mapping of evolutionary relationships and functional diversities among proteins, and deeper insights into protein evolution within and across species.

