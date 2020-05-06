---
title: AM Radio Coverage
summary: Brief summary of the reconstruction of AM radio coverage during the interwar period
tags:
- American Economic History
date: "2020-04-21"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo from the FCC
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

<!-- *cool cite*. -->

The Golden Age of Radio in the United States signed a revolution of media access in the country.
<img align="right" src="wells.png">
To study the effect of radio on American society during the interwar period I coded in R a model of ground wave propagation that, given the characteristics of the transmitting antenna and the distance of the receiver outputs the signal strength of the ground wave.
The model takes into accounts ground conductivity that is the most important factor that affects the attenuation of the ground wave.
<!--
Below the coverage of NBC in 1940 in the US at day time.

![NBC coverage]() -->

The technical details of AM radio propagation and the way I implemented the model are available [here](https://gianlucarusso.github.io/gianlucarusso_radio_appendix.pdf). I am turning the code I wrote into an R package that will be available for download on Github soon.
