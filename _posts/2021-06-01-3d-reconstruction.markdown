---
title: "3D reconstruction course project"
layout: post
date: 2021-06-01 22:10
year: 2021
tag: reconstruction
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
* Pytorch for optimization of positions of cameras and positions of triangulated 3D points.
* 3D reconstruction, structure from motion, multi-view geometry, bundle adjustment.
* Duration: 6 weeks.

This project was done in the course TSBB15 Computer Vision at Linköping university.

The goal was to construct a system able to perform 3D reconstruction of a static scene given images of this scene takenfrom different angles. This task is thoroughly studied in the field of computer vision and known as Structure from Motion (SfM).

<img src="/assets/images/dino_mesh.gif" alt="should be a gif"/>
<figcaption class="caption">Mesh of triangulated 3D points.</figcaption>

<img class="image" src="/assets/images/dino2.png" alt="Alt Text">
<figcaption class="caption">Keypoints on dinosaur that will be triangulated.</figcaption>

<img class="image" src="/assets/images/pytorch-3d.PNG" alt="Alt Text">
<figcaption class="caption">Scheme of Pytorch used for optimization of camera-positions and triangulated points.</figcaption>

<img class="image" src="/assets/images/pipe.PNG" alt="Alt Text">
<figcaption class="caption">Pipeline of multiview 3D reconstruction.</figcaption>

### Links
* Here's the link to the [Github repo](https://github.com/matheus-bernat/3d-reconstruction).
* And here's the project [report](/assets/reports/TSBB15_proj2.pdf).