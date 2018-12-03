---
title: '[A Fully Private Pipeline for Deep Learning on Electronic Health Records](https://arxiv.org/abs/1811.09951)'
authors: 'Edward Chou*, Thao Nguyen*, Josh Beal, Albert Haque, Li Fei-Fei'
date: 2018-09-15
teaser: 'manuscript_pipeline.png'
permalink: /publication/manuscript_pipeline
collection: publications
---

Abstract
-------
We introduce an end-to-end private deep learning framework, applied to the task of predicting 30-day readmission from electronic health records. By using differential privacy during training and homomorphic encryption during inference, we demonstrate that our proposed pipeline could maintain high performance while providing robust privacy guarantees against information leak from data transmission or attacks against the model. We also explore several techniques to address the privacy-utility trade-off in deploying neural networks with privacy mechanisms, improving the accuracy of differentially-private training and the computation cost of encrypted operations using ideas from both machine learning and cryptography.