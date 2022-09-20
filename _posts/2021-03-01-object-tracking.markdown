---
title: "Object tracking course project"
layout: post
date: 2021-03-01 22:10
year: 2021
tag: object-tracking
image: /assets/images/liu.png
small_image: /assets/images/liu2.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: matheus
externalLink: false
---

### About this project
* Python.
* Statistics (Gaussian mixture models & kalman filtering).
* Duration: 6 weeks.

This project was done in the course TSBB15 Computer Vision at Linköping university.

The goal of the constructed system was to track objects – mainly humans – through image sequences, while addressing problems such as shadows, occlusion and spurious motion.The assumptions made are that both the cameras and the background are static, and that the humans are moving on a flat ground plane.

The pipeline consisted of:
- background modeling (through media filtering and then gaussian mixture models);
- foreground segmentation (morphological operations);
- tracking (kalman filtering, keypoint matching).

<img class="image" src="/assets/images/median_gray.png" alt="Alt Text">
<figcaption class="caption">Figure 1. Example of median filtering using gray-scale images.</figcaption>

<img src="/assets/images/02.gif" alt="should be a gif"/>
<figcaption class="caption">Object tracking.</figcaption>

<img src="/assets/images/09.gif" alt="should be a gif"/>
<figcaption class="caption">Object tracking.</figcaption>

### Links
* Here's the link to the [project report](/assets/reports/TSBB15_proj1.pdf).
* Here's the link to the [Github repository](https://github.com/matheus-bernat/object-tracking).