---
title: '[AI Blue Book: Vehicle Price Prediction using Visual Features](https://arxiv.org/abs/1803.11227)'
authors: 'Richard R. Yang, Steven Chen, Edward Chou'
date: 2017-12-01
teaser: 'manuscript_bluebook.png'
permalink: /publication/manuscript_bluebook
collection: publications
---

Abstract
-------
In this work, we build a series of machine learning models to predict the price of a product given its image, and visualize the features that result in higher or lower price predictions. We collect two novel datasets of product images and their MSRP prices for this purpose: a bicycle dataset and a car dataset. We set baselines for price regression using linear regression on histogram of oriented gradients (HOG) and convolutional neural network (CNN) features, and a baseline for price segment classification using a multiclass SVM. For our main models, we train several deep CNNs using both transfer learning and our own architectures, for both regression and classification. We achieve strong results on both datasets, with deep CNNs significantly outperforming other models in a variety of metrics. Finally, we use several recently-developed methods to visualize the image features that result in higher or lower prices.