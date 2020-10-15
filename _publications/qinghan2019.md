---
title: "AWDF: An Adaptive Weighted Deep Fusion Architecture for Multi-modality Learning"
collection: publications
permalink: /publication/qinghan2019
excerpt: ''
date: 2019-12-1
author: Qinghan Xue, Abhishek Kolagunda, Steven Eliuk, Xiaolong Wang*
venue: 'IEEE Big Data'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9006395/'
#videourl: 'https://www.youtube.com/watch?v=KjdkchqlQOU&feature=youtu.be'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Fusion has been widely used in machine learning community, especially  for  problems dealing with multiple  inputsources and classifiers. The general strategy for informationfusion  in deep neural network is to  directly  concatenate  the embedding features on the latent space of input sources. However, it is very hard to capture the relative importance of fused sources. It is also impossible to learn the correlation among fused multi-modalities  inputs, e.g., intra-class  and inter-class similarities.Besides, most existing deep   learning  fusion  approaches  useuniversal fusion weights strategy, which cannot fully exploit therelative importance of different inputs. In order to address these problems, in this work we propose an Adaptive  Weighted  Deep Fusion scheme (AWDF) to capture potential relationships among various input sources. It integrates the feature level and decisionlevel fusion in one framework. Furthermore, in order to address the limitations  of  existing fusing  models with fixed  weights, we propose a new scheme named Cross  Decision Weights  Method(CDWM). It  can  dynamically learn the weight for each inputbranch during the fusion process instead of utilizing pre-defined weights. To evaluate the performance of AWDF, we  conduct experiments on three different real-world datasets: Wild BusinessTerms (WBT) Dataset, Iceberg Detection Dataset and CareerConDataset. Our experimental results demonstrate the superiority of AWDF over other fusion approaches.
[Download paper here](https://ieeexplore.ieee.org/abstract/document/9006395/)

