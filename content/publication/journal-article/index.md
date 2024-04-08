---
title: "Fall detection with a non-intrusive and first-person vision approach"
authors:
- admin
- E Talavera
- D Karastoyanova
- G Azzopardi
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-09-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: Falls have been widely recognized as one of the most dangerous incidents for the elderly and other people with mobility limitations. This problem has attracted wide scientific interest, which has led to several investigations based on nonvision wearable sensors and static cameras. We investigate the challenge of fall detection and recognition using egocentric wearable cameras, which, besides portability and affordability, capture visual information that can be further leveraged for a broad set of lifelogging applications. In this work, five volunteers were equipped with two cameras each, one attached to the neck and the other to the waist. They were asked to simulate four kinds of falls and nine types of nonfalls. The newly collected dataset consists of 5858 short video clips, which we make available online. The proposed approach is a late fusion methodology that combines spatial and motion descriptors along with deep features extracted
by a pretrained convolutional neural network. For the spatial and deep features, we consider the similarity of such features between frames in regular intervals of a given time window. In this way, it is the transition between such frames that are encoded in our approach, while the actual scene content does not play a role. We design several experiments to investigate the best camera location and performance for indoor and outdoor activities and employ leave-one-subjectout cross-validation to test the generalization ability of our approach. For the fall detection (i.e., two-class) problem, our approach achieves 91.8% accuracy, 93.6% sensitivity, and 89.2% specificity.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
