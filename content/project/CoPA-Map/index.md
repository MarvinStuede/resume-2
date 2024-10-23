---
title: CoPA-Map - Continuous Pedestrian Activity Map
summary: A Model for spatio-temporal pedestrian activity prediction
tags:
date: "2022-07-12"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:

url_code: "https://github.com/MarvinStuede/copa-map"
url_pdf: "https://arxiv.org/abs/2203.06911"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

CoPA-Map is a model to predict the activity of pedestrians based on detections made by mobile robots.
Most modern mobile robots are capable of 3D people detection to receive positions of people with respect to the robot's base frame. With known self-localization of the robot, this data can be mapped to the environment. CoPA-Map uses this spatio-temporal data to predict the activity (ie. rate of occurrences during a time interval) at different locations. These predictions can be used for task and path planning, e.g. to avoid crowds, plan human-centered tasks, or for security-related applications.

The novelty of the model lies in its continuous representation that creates a smooth model output even when the collected data is sparse for different locations, for example, because the robot moves while collecting the data.