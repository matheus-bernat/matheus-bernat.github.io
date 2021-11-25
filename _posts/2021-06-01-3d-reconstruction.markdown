---
title: "3D reconstruction course project"
layout: post
date: 2021-06-01 22:10
tag: reconstruction
image: /assets/images/liu.png
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
* Pytorch for optimization of positions of cameras and positions of triangulated 3D points.
* 3D reconstruction, structure from motion, epipolar geometry.
* Duration: 6 weeks.

This project was done in the course TSBB15 Computer Vision at Linköping university.

The goal was to construct a system able to perform 3D reconstruction of a static scene given images of this scene takenfrom different angles. This task is thoroughly studied in the field of computer vision and known as Structure from Motion (SfM).

<img class="image" src="/assets/images/pipeline.png" alt="pipeline">
<figcaption class="caption">Incremental Structure from Motion pipeline.</figcaption>

<img class="image" src="/assets/images/3d_point_cloud3.png" alt="Alt Text">
<figcaption class="caption">Triangulated 3D points.</figcaption>

<img class="image" src="/assets/images/dino2.png" alt="Alt Text">
<figcaption class="caption">Keypoints on dinosaur that will be triangulated.</figcaption>

### Links
* Here's the link to the [Github repo](https://github.com/matheus-bernat/3d-reconstruction).
* And here's the project [report](/assets/reports/TSBB15_proj2.pdf).