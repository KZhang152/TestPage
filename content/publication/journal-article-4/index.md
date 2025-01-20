---
title: 'Integrated Heterogeneous Graph Attention Network for Incomplete Multi-modal
                  Clustering'

authors:
  - Yu Wang
  - Xinjie Yao
  - Pengfei Zhu
  - Weihao Li
  - Meng Cao
  - Qinghua Hu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: "2024-09-20T00:00:00Z"
doi: "10.1007/S11263-024-02066-Y"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Int. J. Comput. Vis.*"
publication_short: ""

abstract: 'Incomplete multi-modal clustering (IMmC) is challenging due to the unexpected missing of some modalities in data. A key to this problem is to explore complementarity information among different samples with incomplete information of unpaired data. Despite preliminary progress, existing methods suffer from (1) relying heavily on paired data, and (2) difficulty in mining complementarity on data with high missing rates. To address the problems, we propose a novel method, Integrated Heterogeneous Graph ATtention (IHGAT) network, for IMmC. To fully exploit the complementarity among different samples and modalities, we first construct a set of integrated heterogeneous graphs based on the similarity graph learned from unified latent representations and the modality-specific availability graphs formed by the existing relations of different samples. Thereafter, the attention mechanism is applied to the constructed integrated heterogeneous graph to aggregate the embedded content of heterogeneous neighbors for each node. In this way, the representations of missing modalities can be learned based on the complementarity information of other samples and their other modalities. Finally, the consistency of probability distribution is embedded into the network for clustering. Consequently, the proposed method can form a complete latent space where incomplete information can be supplemented by other related samples via the learned intrinsic structure. Extensive experiments on eight public datasets show that the proposed IHGAT outperforms existing methods under various settings and is typically more robust in cases of high missing rates.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://link.springer.com/content/pdf/10.1007/s11263-024-02066-y.pdf'
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
