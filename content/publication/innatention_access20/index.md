---
title: "Adaptive Inattentional Framework for Video Object Detection With Reward-Conditional Training"
authors:
- Alejandro Rodríguez-Ramos
- admin
- Carlos Sampedro
- Pascual Campoy
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2020-06-01T00:00:00Z"
doi: "https://doi.org/10.1109/ACCESS.2020.3006191"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*(8)"
publication_short: ""

abstract: "Recent object detection studies have been focused on video sequences, mostly due to the increasing demand of industrial applications. Although single-image architectures achieve remarkable results in terms of accuracy, they do not take advantage of particular properties of the video sequences and usually require high parallel computational resources, such as desktop GPUs. In this work, an inattentional framework is proposed, where the object context in video frames is dynamically reused in order to reduce the computation overhead. The context features corresponding to keyframes are fused into a synthetic feature map, which is further refined using temporal aggregation with ConvLSTMs. Furthermore, an inattentional policy has been learned to adaptively balance the accuracy and the amount of context reused. The inattentional policy has been learned under the reinforcement learning paradigm, and using our novel reward-conditional training scheme, which allows for policy training over a whole distribution of reward functions and enables the selection of a unique reward function at inference time. Our framework shows outstanding results on platforms with reduced parallelization capabilities, such as CPUs, achieving an average latency reduction up to 2.09×, and obtaining FPS rates similar to their equivalent GPU platform, at the cost of a 1.11× mAP reduction."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- IEEE Access
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9130680
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://vimeo.com/426725929'

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
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
