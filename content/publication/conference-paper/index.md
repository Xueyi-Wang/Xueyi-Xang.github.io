---
title: 'Fall Detection with Event-Based Data: A Case Study'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Nicoletta Risi
  - Estefanía Talavera
  - Elisabetta Chicca
  - Dimka Karastoyanova
  - George Azzopardi 

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-09-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-20T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: Fall detection systems are relevant in our aging society aiming to support efforts towards reducing the impact of accidental falls. However, current solutions lack the ability to combine low-power consumption, privacy protection, low latency response, and low payload. In this work, we address this gap through a comparative analysis of the trade-off between effectiveness and energy consumption by comparing a Recurrent Spiking Neural Network (RSNN) with a Long Short-Term Memory (LSTM) and a Convolutional Neural Network (CNN). By leveraging two pre-existing RGB datasets and an event-camera simulator, we generated event data by converting intensity frames into event streams. Thus, we could harness the salient features of event-based data and analyze their benefits when combined with RSNNs and LSTMs. The compared approaches are evaluated on two data sets collected from a single subject; one from a camera attached to the neck (N-data) and the other one attached to the waist (W-data). Each data set contains 469 video samples, of which 213 are four types of fall examples, and the rest are nine types of non-fall daily activities.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
