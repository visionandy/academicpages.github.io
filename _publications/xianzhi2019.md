---
title: "Boundary-sensitive Network for Portrait Segmentation"
collection: publications
permalink: /publication/xianzhi2019
excerpt: 'Focusing on the most challenging part of portrait segmentation, we build an end-to-end solution and obtain more realistic results, especially on the object boundary.'
date: 2019-5-01
author: Xianzhi Du, Xiaolong Wang*, Dawei Li, Jingwen Zhu, Serafettin Tasci, Cameron Upright, Stephen Walsh, Larry Davis
venue: 'FG(oral)'
paperurl: 'https://arxiv.org/pdf/1712.08675.pdf'
#videourl: 'https://www.youtube.com/watch?v=KjdkchqlQOU&feature=youtu.be'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Compared to the general semantic segmentation problem, portrait segmentation has higher precision requirement on boundary area. However, this problem has not been well studied in previous works. In this paper, we propose a boundary-sensitive deep neural network (BSN) for portrait segmentation. BSN introduces three novel techniques. First, an individual boundary-sensitive kernel is proposed by dilating the contour line and assigning the boundary pixels with multi-class labels. Second, a global boundary-sensitive kernel is employed as a position sensitive prior to further constrain the overall shape of the segmentation map. Third, we train a boundary-sensitive attribute classifier jointly with the segmentation network to reinforce the network with semantic boundary shape information. We have evaluated BSN on the current largest public portrait segmentation dataset, ie, the PFCN dataset, as well as the portrait images collected from other three popular image segmentation datasets: COCO, COCO-Stuff, and PASCAL VOC. Our method achieves the superior quantitative and qualitative performance over state-of-the-arts on all the datasets, especially on the boundary area.
[Download paper here](https://arxiv.org/pdf/1712.08675.pdf)

