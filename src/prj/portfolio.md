---
layout: default
---

# Portfolio

## EDA and Visualization

### [Exploratory Data Analysis and Visualization of Renewable Energy Consumption in the EU](./eda_eu_energy.md)

## Natural Language Processing

### [Fake news classifier using Natural Language Processing](./nlp_fake_news.md)

### [Computational analysis of Twitter discourse surrounding the protests in Iran](./dsd_twitter_iran.md)


## Computer Vision

### [Content-Based Image Retrieval System]
- A comparison of different feature extractor methods for CBIR
- Used both standard Computer Vision techniques (ORB, SIFT, SURF) and Deep Learning (VGG16).
- Python libraries used: OpenCV, scikit-image, Tensorflow.

### [Comparing state-of-the-art data augmentation methods on varying dataset settings]
- Studying how the performance of a CNN classifier changes when applying AugMix, CutMix, MixUp and GridMask on downsampled versions of CIFAR-10.
- Checking if the methods increase robustness to corruptions using CIFAR-10-C as an OOD evaluation.
- Python libraries used: Tensorflow, Keras, scikit-learn.


## Big Data Systems

### [Big Data System to optimize the delivery of goods in the city of Milan](https://github.com/alescortes/food-delivery_bdt2022)
- Developed a big data system to generate orders to a food delivery service and to match a set of delivery men to deliver such orders. 
- The system includes a MongoDB database to store the deliverymen, the pending orders, and the processed orders and a MQTT queue which acts as a buffer in the data ingestion phase.
- Distances are calculated using Openrouteservice API.
- The result of the program is a flask dashboard which displays a map and a series of analytics about the orders.
- Code is packaged using docker


## Computational Social Science

### [Investigating the impact of the pandemic on music consumption]
- Used topic modelling and LDA on lyrics from songs before and after the pandemic.
- Compared logistic regression, boosted trees and random forest classifiers to distinguish between songs before and after the pandemic based on their audio features.
- Used Spotify API to retrieve audio features and Genius API to scrape lyrics.
- R libraries used: ggplot2, tidymodels, tm, topicmodels, caret, gbm, tree, randomForest.
- Will upload this soon hopefully

[back](../../)
