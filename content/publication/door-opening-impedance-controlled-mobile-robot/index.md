---
title: Door opening and traversal with an industrial cartesian impedance
  controlled mobile robot
authors:
  - admin
  - Kathrin Nülle
  - Svenja Tappe
  - Tobias Ortmaier
author_notes: []
publication_short: ""
abstract: This paper presents a holistic approach for door opening with a
  cartesian impedance controlled mobile robot, a KUKA KMR iiwa. Based on a given
  map of the environment, the robot autonomously detects the door handle, opens
  doors and traverses doorways without knowledge of a door model or the door's
  geometry. The door handle detection uses a convolutional neural network
  (CNN)-based architecture to obtain the handle's bounding box in a RGB image
  that works robustly for various handle shapes and colors. We achieve a
  detection rate of 100% for an evaluation set of 38 different door handles, by
  always selecting for highest confidence score. Registered depth data
  segmentation defines the door plane to construct a handle coordinate frame. We
  introduce a control structure based on the task frame formalism that uses the
  handle frame for reference in an outer loop for the manipulator's impedance
  controller. It runs in soft real-time on an external computer with
  approximately 20 Hz since access to inner controller loops is not available
  for the KMR iiwa. With the approach proposed in this paper, the robot
  successfully opened and traversed for 22 out of 25 trials at five different
  doors.
tags: []
projects: []
slides: ""
url_pdf: https://www.repo.uni-hannover.de/handle/123456789/10435

image:
  caption: ""
  focal_point: RIGHT
  preview_only: false
  filename: featured.png
summary: Approach for autonomous door handle detection, door opening and traversal
url_dataset: ""
url_project: ""
url_source: ""
url_video: https://www.youtube.com/watch?v=pbAcr6Ur1f4
publication: In *2019 International Conference on Robotics and Automation*
publication_types: ['paper-conference']
publication_short: In *ICRA 2019*
featured: true
date: 2019-05-01T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
doi: 10.1109/ICRA.2019.8793866
---
