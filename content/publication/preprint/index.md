---
title: "WASP: A pipeline for functional annotation based on AlphaFold structural models"
authors:
- Del Missier, Shabestary, Ledesma-Amaro
date: "2024-07-01T00:00:00Z"
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

abstract: Protein function annotation is a crucial aspect of understanding biological processes and mechanisms. Traditionally, annotations have been derived from sequence homology, providing valuable insights but often leaving gaps even in well-characterised organisms. With the emergence of AlphaFold, rapid generation of structural models are offering a new paradigm for inferring protein function based on structural homology. Here, we present WASP, a pipeline leveraging structural homology to enhance protein annotation at scale, providing a more comprehensive understanding of protein functions across various organisms. WASP relies on network topology for better accuracy and more robust statistical power. On hidden labels, WASP achieved superior F1 scores compared to state-of-the-art tools using sequence homology. On a cohort of 20 model organisms relevant for industrial applications, WASP could retrieve 20-30% of uncharacterised proteins. WASP utility was further demonstrated in genome-scale model curation where it could identify native candidates for 75% to 100% of orphan reactions. Together, WASP highlights the importance of structural homology in systematically identifying novel annotations which were previously missed by sequence-based tools.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
 Genome annotation, structural alignment, genome-scale model, orphan reaction, bioproduction, alphafold, synthetic biology, systems biology.

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
