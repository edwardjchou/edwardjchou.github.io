---
title: '[Delegated Feature Extraction for Encrypted Inference](https://pimlai.github.io/pimlai18/)'
authors: 'Edward Chou, Josh Beal, Albert Haque, Li Fei-Fei'
date: 2018-06-24
teaser: 'ICML_PiMLAI_DFE.png'
permalink: /publication/ICML_PiMLAI_DFE
collection: publications
---

Abstract
-------
Homomorphic encryption enables neural networks to operate on encrypted data, which could be valuable for privacy sensitive computations. However, the computational overhead of this method increases significantly with network depth, preventing the use of modern network architectures that have dozens of layers. To mitigate this issue, we propose the use of models trained with transfer learning, where the computations involved in the pretrained layers of the model can be delegated to the client, and encryption is applied only for the evaluation of the fine-tuned layers on the server. Using this technique, as well as some optimizations to speed up the computation, we achieve practical runtimes for large input sizes.