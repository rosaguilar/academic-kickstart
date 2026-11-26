---
title: "Ensemble machine learning for crop classification"
summary: "A cloud-based multi-temporal ensemble of five machine learning classifiers that maps crops on smallholder farms in Mali from very-high-resolution satellite imagery, outperforming every single classifier."
authors: ["admin"]
tags: ["GeoAI", "Remote sensing", "Agriculture", "Google Earth Engine"]
categories: []
icon: "seedling"
weight: 1
date: 2018-05-09

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image: add `featured.png` or `featured.jpg` to this folder (e.g. a map or key figure from the paper).
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

links:
- name: "Paper (Remote Sensing, 2018)"
  url: "https://doi.org/10.3390/rs10050729"
  icon_pack: fas
  icon: file-alt

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
slides: ""
---

Smallholder farmers cultivate more than 80% of Africa's cropland. Their fields are small, irregular and often intercropped, which makes crops very hard to map from space.

I developed a **cloud-based, multi-temporal ensemble classifier** in Google Earth Engine to map the most common crops on smallholder farms in southern Mali.

* Combines spatial and spectral features from **multi-temporal WorldView-2 imagery** with field data.
* Combines **five machine learning classifiers** using majority voting and weighted majority voting, and compares ensembles of different sizes.
* Both ensemble strategies **outperform every single classifier** tested.

Read the paper: [A Cloud-Based Multi-Temporal Ensemble Classifier to Map Smallholder Farming Systems](https://doi.org/10.3390/rs10050729), *Remote Sensing* 10(5), 729 (2018), with Raul Zurita-Milla, Emma Izquierdo-Verdiguier and Rolf A. de By.
