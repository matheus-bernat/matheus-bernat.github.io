---
title: "Object tracking project, CV course project @ LiU"
layout: post
date: 2021-03-01 22:10
tag: object-tracking
image: /assets/images/liu.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: matheus
externalLink: false
---

This report contains a description of the techniques andimplementation details of a tracking system for the course TSBB15 Computer Vision at Linköping university. The goal of the constructed system was to track objects – mainly humans – through image sequences, while addressing problems suchas shadows, occlusion and spurious motion.The assumptions made are that both the cameras and thebackground are static, and that the humans are moving on a flat ground plane.

The pipeline consisted of_
- background modeling (through media filtering and then gaussian mixture models);
- foreground segmentation (morphological operations);
- tracking (kalman filtering, keypoint matching).

<img class="image" src="/assets/images/median_gray.png" alt="Alt Text">
<img class="image" src="/assets/images/gt_vs_our_frame70.png" alt="Sequence MOT17-09, ground truth (left) our de-tections (right)">


### About this project
* Python.
* Statistics (Gaussian mixture models & kalman filtering).
* Duration: 6 weeks.

### Links
* Here's the link to the [project report](/assets/reports/TSBB15_proj1.pdf)
* Here's the link to the [Github repository](https://github.com/matheus-bernat/object-tracking).