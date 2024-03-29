---
title: "Deep Learning-Based System for Automatic Recognition and Diagnosis of Electrical Insulator Strings"
authors:
- Carlos Sampedro
- admin
- Alejandro Rodríguez-Ramos
- Adrián Carrio
- Pascual Campoy
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-06-25T00:00:00Z"
doi: "https://doi.org/10.1109/ACCESS.2019.2931144"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*(7)"
publication_short: ""

abstract: "This paper presents a complete system for automatic recognition and the diagnosis of electrical insulator strings which efficiently combines different deep learning-based components to build a versatile solution to the automation problem of the power line inspection process. To this aim, the proposed system integrates one component responsible for insulator string segmentation and two components in charge of its diagnosis. The insulator string segmentation component consists of a novel fully convolutional network (FCN) architecture, termed Up-Net, which enhances the capabilities of the state-of-the-art U-Net network by introducing new skip connections at certain levels of the architecture. Furthermore, we propose a second variant of the Up-Net network by training it within a generative adversarial network (GAN) framework. The capabilities of the proposed Up-Net variants are incremented by the application of data augmentation and transfer learning techniques, achieving accurate segmentation of the insulator string elements (i.e., discs and caps). Regarding the insulator string diagnosis, we design a convolutional neural network (CNN) which takes as input the mask generated by the insulator string segmentation component and is capable of identifying the absence of a variable number of discs. The second diagnosis component consists of a novel strategy which integrates a Siamese convolutional neural network (SCNN) designed for modeling the similarity between adjacent discs and allowing the detection of several types of disc defects using the same model. The proposed system has been extensively evaluated in several video sequences from real aerial inspections of high-voltage insulators, showing robust insulator recognition and diagnosis capabilities."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- IEEE Access
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8772209
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://vimeo.com/318826658'

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
