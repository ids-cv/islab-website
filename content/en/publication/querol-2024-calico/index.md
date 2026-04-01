---
title: 'CALICO: Confident Active Learning with Integrated Calibration'
authors:
- Lorenzo Querol
- Hajime Nagahara
- Hideaki Hayashi
date: '2024-01-01'
publishDate: '2025-12-09T01:20:20.853963Z'
publication_types:
- paper-conference
publication: '*Proceedings of the International Conference on Artificial Neural Networks
  (ICANN 2024)*'
abstract: The growing use of deep learning in safety-critical applications, such as
  medical imaging, has raised concerns about limited labeled data, where this demand
  is amplified as model complexity increases, posing hurdles for domain experts to
  annotate data. In response to this, active learning (AL) is used to efficiently
  train models with limited annotation costs. In the context of deep neural networks
  (DNNs), AL often uses confidence or probability outputs as a score for selecting
  the most informative samples. However, modern DNNs exhibit unreliable confidence
  outputs, making calibration essential. We propose an AL framework that self-calibrates
  the confidence used for sample selection during the training process, referred to
  as Confident Active Learning with Integrated CalibratiOn (CALICO). CALICO incorporates
  the joint training of a classifier and an energy-based model, instead of the standard
  softmax-based classifier. This approach allows for simultaneous estimation of the
  input data distribution and the class probabilities during training, improving calibration
  without needing an additional labeled dataset. Experimental results showcase improved
  classification performance compared to a softmax-based classifier with fewer labeled
  samples. Furthermore, the calibration stability of the model is observed to depend
  on the prior class distribution of the data.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1007/978-3-031-72332-2_9
---
