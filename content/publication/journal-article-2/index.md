---
title: 'Geometry-semantic aware for monocular 3D Semantic Scene Completion'

authors:
  - Zonghao Lu 
  - Bing Cao
  - Shuyin Xia
  - 'Qinghua Hu'

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: "2025-01-09T00:00:00Z"
doi: "10.1016/J.PATCOG.2024.111030"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Pattern Recognition.*"
publication_short: ""

abstract: 'Monocular Semantic Scene Completion (SSC) empowers intelligent devices to comprehend voxel occupancy (geometry) and semantics in 3D scenes, attracting significant attention in indoor and autonomous driving scenarios. However, existing monocular SSC models primarily map 2D images into 3D space, neglecting the potential benefits of leveraging semantic and geometric understanding in 2D. To address this, we propose the Proxy-embedding Parallel Multi-task Network (PPMNet), which aims to perceive the geometry and semantics of 3D space through depth estimation and semantic segmentation proxy tasks on the 2D perspective plane. Moreover, 2D plane features can be inversely projected into 3D space and subsequently processed using the 3D network. In addition, we enhance contextual awareness in both perspective planes and voxel grids through parallel 2D and 3D decoders. Furthermore, we employ Dual-Head Pyramid Pooling (DHPP) to aggregate information from these two representations. Finally, considering the class imbalance and label incompleteness in practical data, we design a local-to-global loss to prioritize challenging categories. Extensive experiments validate our superiority over state-of-the-art methods on the NYUv2 and SemanticKITTI datasets. The code is available at: https://github.com/luzonghao1/PPMNet.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0031320324007817/pdfft?md5=ba0e206aa5cb884e0cba35b5d661a4a3&pid=1-s2.0-S0031320324007817-main.pdf'
url_code: 'https://github.com/luzonghao1/PPMNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
