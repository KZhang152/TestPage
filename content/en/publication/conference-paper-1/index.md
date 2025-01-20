---
title: 'Bi-directional Adapter for Multimodal Tracking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bing Cao
  - Junliang Guo
  - Pengfei Zhu
  - Qinghua Hu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-04-02T00:00:00Z'
doi: '10.1609/aaai.v38i2.27852'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *AAAI*
# publication_short: In *ICW*

abstract: 'Due to the rapid development of computer vision, single-modal (RGB) object tracking has made significant progress in recent years. Considering the limitation of single imaging sensor, multi-modal images (RGB, infrared, etc.) are introduced to compensate for this deficiency for all-weather object tracking in complex environments. However, as acquiring sufficient multi-modal tracking data is hard while the dominant modality changes with the open environment, most existing techniques fail to extract multi-modal complementary information dynamically, yielding unsatisfactory tracking performance. To handle this problem, we propose a novel multi-modal visual prompt tracking model based on a universal bi-directional adapter, cross-prompting multiple modalities mutually. Our model consists of a universal bi-directional adapter and multiple modality-specific transformer encoder branches with sharing parameters. The encoders extract features of each modality separately by using a frozen, pre-trained foundation model. We develop a simple but effective light feature adapter to transfer modality-specific information from one modality to another, performing visual feature prompt fusion in an adaptive manner. With adding fewer (0.32M) trainable parameters, our model achieves superior tracking performance in comparison with both the full fine-tuning methods and the prompt learning-based methods. Our code is available: https://github.com/SparkTempest/BAT.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  # - Multi-modal Vision

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/27852/27730'
url_code: 'https://github.com/SparkTempest/BAT'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

