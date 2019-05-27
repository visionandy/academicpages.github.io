---
title: "MICIK: MIning Cross-Layer Inherent Similarity Knowledge for Deep Model Compression"
collection: publications
permalink: /publication/jie1
excerpt: '1st across layers based Deep model compression work. We completed this work in the Decemeber of 2017.'
date: 2019-2-01
author: Jie Zhang, Xiaolong Wang*, Dawei Li, Yalin Wang
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/1902.00918'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
State-of-the-art deep model compression methods exploit the low-rank approximation and sparsity pruning to remove redundant parameters from a learned hidden layer. However, they process each hidden layer individually while neglecting the common components across layers, and thus are not able to fully exploit the potential redundancy space for compression. To solve the above problem and enable further compression of a model, removing the cross-layer redundancy and mining the layer-wise inheritance knowledge is necessary. In this paper, we introduce a holistic model compression framework, namely MIning Cross-layer Inherent similarity Knowledge (MICIK), to fully excavate the potential redundancy space. The proposed MICIK framework simultaneously,(1) learns the common and unique weight components across deep neural network layers to increase compression rate;(2) preserves the inherent similarity knowledge of nearby layers and distant layers to minimize the accuracy loss and (3) can be complementary to other existing compression techniques such as knowledge distillation. Extensive experiments on large-scale convolutional neural networks demonstrate that MICIK is superior over state-of-the-art model compression approaches with 16X parameter reduction on VGG-16 and 6X on GoogLeNet, all without accuracy loss.
[Download paper here](https://arxiv.org/pdf/1902.00918)

