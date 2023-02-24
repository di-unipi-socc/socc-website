---
title: DA-Placer
summary: "Tool for data-aware service placement and data routing in the Cloud-IoT continuum"
tags:
date: "2021-12-02T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: DA-Placer
  focal_point: Smart
  
url_code: "https://github.com/di-unipi-socc/daplacer"
url_pdf: ''
url_slides: ''
url_video: "https://www.youtube.com/watch?v=TkSmO_cETlw"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Meeting all stringent functional (e.g. _software, hardware, IoT_) and non-functional (e.g. _security, latency, bandwidth_) requirements Cloud-IoT applications, requires to suitably place their services onto target Cloud-IoT nodes. Very few existing approaches solving this problem focussed on the **data-aware** placement of Cloud-IoT application services, i.e. on modelling the characteristics of the data to be processed and on placing services suitably close to their data. We propose a declarative solution that accounts for those aspects so as to determine service placements and SDN data routings that meet all application requirements. Such a solution employs continuous reasoning to speed-up placement and routing decisions at runtime. An open-source Prolog prototype of the solution is assessed over a scenario based on lifelike data. 
