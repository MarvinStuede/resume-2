---
title: cmr_lidarloop
summary: A ROS package for loop closure detection
tags:
date: "2021-12-27"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:

url_code: "https://github.com/MarvinStuede/cmr_lidarloop"
url_pdf: "https://arxiv.org/abs/2103.06713"
url_slides: ""
url_video: "https://www.youtube.com/watch?v=Co81uQPXvn8&embeds_referring_euri=https%3A%2F%2Fmarvinstuede.github.io%2F&source_ve_path=MjM4NTE"
url_project: "https://marvinstuede.github.io/Sobi/software/lidarloop.html"
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

cmr_lidarloop is a ROS package that can be used to detect loops in 3D-Lidar data. It was developed as an extension to the well-known SLAM library [RTAB-Map](http://introlab.github.io/rtabmap/) and integrates seamlessly into RTAB-Map's topic structure. One disadvantage of RTAB-Map is its insufficient use of 3D-Pointcloud data for loop closure detection.
This problem is solved by cmr_lidarloop, which makes use of global feature classification and pointcloud registration and can therefore significantly enhance RTAB-Maps performance in challenging environments (e.g. when illumination changes).

It contains one module for loop-closure detection and subsequent loop verification and another module for scan registration and is avaiable on [GitHub](https://github.com/MarvinStuede/cmr_lidarloop).
The library originated from the master thesis of one of my supervised students, Tim-Lukas Habich.
More information can be found in the [documentation](https://marvinstuede.github.io/Sobi/software/lidarloop.html).
