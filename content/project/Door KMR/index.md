---
title: KMR iiwa Autonomous Door Opening
summary: "Detecting door handles and open doors with a mobile manipulator"
tags:
date: "2018-03-25"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Copyright Fockelmann
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
For my master thesis I developed a functionality to open doors with the KUKA KMR iiwa robot. I wanted to create a method that works without any prior knowledge about the door's shape, geometry or dynamic parameters and with different types of typical door handles.

The handles were detected with a camera (Microsoft Kinect) and object detection by a ResNet+Faster RCNN detector. I formulated the door opening problem with the Task Frame formalism. One Unique feature of my method is that it does not need to run with a fast control loop, but can be exectued on ROS with a commercial robot controller that does not allow for deep system access. The method also includes a sequential control scheme, so that it seamlessly integrates with the ROS navigation stack, automatically opening closed doors that lie on the robot's path.

I published my approach in this [ICRA 2019 paper](/publication/door-opening-impedance-controlled-mobile-robot/).
