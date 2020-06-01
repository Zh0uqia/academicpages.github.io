---
title: "Synthetic Augmentation and Feature-based Filtering for Improved Cervical Histopathology Image Classification"
collection: publications
permalink: /publication/miccai19
excerpt: ''
date: 2019-06-10
venue: 'MICCAI'
citation: 'Yuan Xue, **Qianying Zhou**, Jiarong Ye, L. Rodney Long, Sameer Antani, Carl Cornwell, Zhiyun Xue, Xiaolei Huang (2019). &quot;Synthetic Augmentation and Feature-Based Filtering for Improved Cervical Histopathology Image Classification.&quot; <i>MICCAI 2019</i>'
---
[[PDF]](https://qycode.me/files/miccai19.pdf)

## Abstract
Cervical intraepithelial neoplasia (CIN) grade of histopathology images is a crucial indicator in cervical biopsy results. Accurate CIN grading of epithelium regions helps pathologists with precancerous lesion diagnosis and treatment planning. Although an automated CIN grading system has been desired, supervised training of such a system would require a large amount of expert annotations, which are expensive and time-consuming to collect. In this paper, we investigate the CIN grade classification problem on segmented epithelium patches. We propose to use conditional Generative Adversarial Networks (cGANs) to expand the limited training dataset, by synthesizing realistic cervical histopathology images. While the synthetic images are visually appealing, they are not guaranteed to contain meaningful features for data augmentation. To tackle this issue, we propose a synthetic-image filtering mechanism based on the divergence in feature space between generated images and class centroids in order to control the feature quality of selected synthetic images for data augmentation. Our models are evaluated on a cervical histopathology image dataset with limited number of patch-level CIN grade annotations. Extensive experimental results show a significant improvement of classification accuracy from 66.3% to 71.7% using the same ResNet18 baseline classifier after leveraging our cGAN generated images with feature based filtering, which demonstrates the effectiveness of our models.
