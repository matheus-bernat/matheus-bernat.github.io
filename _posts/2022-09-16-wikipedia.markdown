---
title: "Topical classification of Wikipedia images -- Master Thesis"
layout: post
date: 2022-09-16 10:00
year: 2022
tag: wikipedia
image: /assets/images/dlab.svg
small_image: /assets/images/dlab.svg
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
* ML libraries: Tensorflow, Scikit, Numpy.
* Viz libraries: Matplotlib, Seaborn.
* Problem: Multilabel topic classification, imbalanced dataset.
* Duration: semester project during the Spring semester 2022, and master thesis during the current Fall semester.

Wikipedia is full of articles... and images! Having over 53 million articles in 299 languages containing 11.5 million unique images, there is a great need for automated organization of all this data. Inspired by ORES, an ensemble of machine learning systems in Wikipedia that provides among others automated labeling of articles, the semester project aimed at automated _topic_ labeling of images in Wikipedia. In this project, experiments are made using images labeled with the ORES labels of the articles where they are present, and with the custom labels that were attributed with a heuristic in the taxonomy part of this semester project. Two different models (EfficientNetB0 and EfficientNetB2) are trained on this data using 10 or 20 labels. As the main insights we understood that:

- the custom labels were inferior to ORES labels according to our metrics;
- the network with more parameters, EfficientNetB2, yielded higher prediction values having greater average recall but does not outperform EfficientNetB0 with regards to the ROC curves;
- the labels with better performance are those that are most present in the dataset used in pre-training.

As for the *master thesis* that I am currently undertaking, the focus lies on:
- studying solutions to damp the bad effects of the unbalanced dataset;
- structure the labels hierarchically and develop a hierarchical classification model;
- performing a completely novel data study on the topic distribution of images in Wikipedia.


<img class="image" src="/assets/images/neuralnet_good.png" alt="Alt Text">
<figcaption class="caption">Structure of the designed network.</figcaption>

<img class="image" src="/assets/images/class_dist_naive.PNG" alt="Alt Text">
<figcaption class="caption">Class distribution.</figcaption>

### Links
* Link to the [Github repo](https://github.com/epfl-dlab/wiki_image_classification/tree/main/classification).
* Report of the semester project [report](/assets/reports/Wikipedia_Image_Classification_DLAB.pdf).