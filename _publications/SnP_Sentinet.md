---
title: '[SentiNet: Detecting Physical Attacks Against Deep Learning Systems](https://arxiv.org/submit/2492681)'
authors: 'Edward Chou, Florian Tramèr, Giancarlo Pellegrino, Dan Boneh'
venue: 'IEEE Security & Privacy'
date: 2018-12-01
teaser: 'SnP_Sentinet.png'
permalink: /publication/SnP_Sentinet
collection: publications
---

Abstract
-------
SentiNet is a novel detection framework for physical attacks on neural networks, a class of attacks that constrains an adversarial region to a visible portion of an image.  Physical attacks have been shown to be robust and flexible techniques suited for deployment in real-world scenarios.  Unlike most other adversarial detection works, SentiNet does not require training a model or preknowledge of an attack prior to detection.  This attack-agnostic approach is appealing due to the large number of possible mechanisms and vectors of attack an attack-specific defense would have to consider.  By leveraging the neural network's susceptibility to attacks and by using techniques from model interpretability and object detection as detection mechanisms, SentiNet turns a weakness of a model into a strength.  We demonstrate the effectiveness of SentiNet on three different attacks - i.e., adversarial examples, data poisoning attacks, and trojaned networks - that have large variations in deployment mechanisms, and show that our defense is able to achieve very competitive performance metrics for all three threats, even against strong adaptive adversaries with full knowledge of SentiNet.