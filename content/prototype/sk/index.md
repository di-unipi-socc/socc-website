---
title: SKnife
summary: "declarative prototype to partition multi-component applications employing information-flow security methodologies in order to exploit the Separation Kernel (SK) technology."
tags:
date: "2022-07-19T00:00:00Z"
doi: ''

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/di-unipi-socc/sk"

image:
  caption: 'SK'
  focal_point: Smart

# links:
#   - icon: ''
#     icon_pack: fab
#     name: ''
#     url: ''
  
url_code: 'https://github.com/di-unipi-socc/sk'
url_pdf: ''
url_slides: ''
url_video: ''

links:
  - name: 'Prototype'
    url: 'prototype/sk'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---
<!-- Here you can insert a description -->
SKnife is a declarative prototype to partition multi-component applications employing information-flow security methodologies in order to exploit the Separation Kernel (SK) technology. SKnife first check the application is partitionable, i.e. do not leak data to untrusted hardware components, then finds the minimal eligible partitioning, the partitioning with the fewer number of SK domain that avoids data leak. To support the developers of non-partitionable applications, SKnife-Recommend allows finding labelling suggestions to relax the information-flow constraints in order to allow the partitioning.