---
title: Gaussian-Based Instance-Adaptive Intensity Modeling for Point-Supervised Facial
  Expression Spotting
authors:
- Yicheng Deng
- Hideaki Hayashi
- Hajime Nagahara
date: '2025-01-01'
publishDate: '2025-12-09T01:20:22.588886Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 13th International Conference on Learning Representations
  (ICLR 2025)*'
abstract: Point-supervised facial expression spotting (P-FES) aims to localize facial
  expression instances in untrimmed videos, requiring only a single timestamp label
  for each instance during training. To address label sparsity, hard pseudo-labeling
  is often employed to propagate point labels to unlabeled frames; however, this approach
  can lead to confusion when distinguishing between neutral and expression frames
  with various intensities, which can negatively impact model performance. In this
  paper, we propose a two-branch framework for P-FES that incorporates a Gaussian-based
  instance-adaptive Intensity Modeling (GIM) module for soft pseudo-labeling. GIM
  models the expression intensity distribution for each instance. Specifically, we
  detect the pseudo-apex frame around each point label, estimate the duration, and
  construct a Gaussian distribution for each expression instance. We then assign soft
  pseudo-labels to pseudo-expression frames as intensity values based on the Gaussian
  distribution. Additionally, we introduce an Intensity-Aware Contrastive (IAC) loss
  to enhance discriminative feature learning and suppress neutral noise by contrasting
  neutral frames with expression frames of various intensities. Extensive experiments
  on the SAMM-LV and CAS(ME) datasets demonstrate the effectiveness of our proposed
  framework. Code is available at https://github.com/KinopioIsAllIn/GIM.
links:
- name: URL
  url: https://openreview.net/forum?id=daD6uGMeLs
---
