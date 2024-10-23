---
title: Delta Robot Feedforward Dynamics Control
summary: Identification and Feedforward Control of a Codian Delta Robot
tags:
date: "2017-01-06"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---
For this job I worked with a Codian Delta Robot to identify the Minimal Parameters of an Inverse Dynamics Model. This was done by generating Fourier-series based Trajectories to obtain an optimal excitation. The dynamic model was then calculated by Minimum-Least-Squares in MATLAB. I then converted the resulting model to run on an SPS Controller and created a Torque Feedforward Controller. Implementing this controller lead to a decrease in trajectory error.
