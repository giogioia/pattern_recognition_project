# pattern_recognition_project
Deep convolutional neural network implementation for brain tumor segmentation.

In this project I pre-processed MRI scans by applying skull-stripping techniques and eventually built an extremely lightweight convolutional neural network with Keras for brain tumor segmentation.

The dataset used was created by Buda et al. (https://arxiv.org/abs/1906.03720). The authors used a U-Net model for brain tumor segmentation. U-Net has 7m paramenters. Our goal was to develop a lightweight model that would yield similar performance of the author's U-Net implementation (82% Dice score).

Our model, a modified MobileNetv3, achieved 85% Dice score, outperforming the original U-Net implementation of the authors whilst having 0.05% of U-Net's paramenters (350k v 7m params).

Project report: [ISPR_PROJECT_REPORT](/ISPR_PROJECT_REPORT.pdf)

Project presentation: [ISPR_PROJECT_SLIDES](/ISPR_PROJECT_SLIDES.pdf)
