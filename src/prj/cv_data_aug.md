---
layout: default
---

## [Comparing state-of-the-art data augmentation methods on varying dataset settings]
- Group project for the Machine Learning II course @ University of Twente, the Netherlands.
- A study of how the performance of a CNN classifier changes when applying AugMix, CutMix, MixUp and GridMask on several downsampled versions of CIFAR-10.
- Checking if the methods increase robustness to common image corruptions using CIFAR-10-C as an OOD evaluation.
- Python libraries used: Tensorflow, Keras, scikit-learn.
- _Code will be uploaded soon..._

The following image represents the project workflow: each configuration of downsampled subsets considered is augmented 
with augmentation techniques and augmentation factors, then evaluated in and out of distribution.

[!cv_aug_config_workflow](../imgs/cv_aug_config_workflow.pdf)

[back](./portfolio.md)