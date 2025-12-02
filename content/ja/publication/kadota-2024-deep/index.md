---
title: Deep Bayesian Active Learning-to-Rank with Relative Annotation for Estimation
  of Ulcerative Colitis Severity
authors:
- Takeaki Kadota
- Hideaki Hayashi
- Ryoma Bise
- Kiyohito Tanaka
- Seiichi Uchida
date: '2024-01-01'
publishDate: '2025-12-02T05:07:24.654557Z'
publication_types:
- article-journal
publication: '*Medical Image Analysis*'
abstract: Automatic image-based severity estimation is an important task in computer-aided
  diagnosis. Severity estimation by deep learning requires a large amount of training
  data to achieve a high performance. In general, severity estimation uses training
  data annotated with discrete (i.e., quantized) severity labels. Annotating discrete
  labels is often difficult in images with ambiguous severity, and the annotation
  cost is high. In contrast, relative annotation, in which the severity between a
  pair of images is compared, can avoid quantizing severity and thus makes it easier.
  We can estimate relative disease severity using a learning-to-rank framework with
  relative annotations, but relative annotation has the problem of the enormous number
  of pairs that can be annotated. Therefore, the selection of appropriate pairs is
  essential for relative annotation. In this paper, we propose a deep Bayesian active
  learning-to-rank that automatically selects appropriate pairs for relative annotation.
  Our method preferentially annotates unlabeled pairs with high learning efficiency
  from the model uncertainty of the samples. We prove the theoretical basis for adapting
  Bayesian neural networks to pairwise learning-to-rank and demonstrate the efficiency
  of our method through experiments on endoscopic images of ulcerative colitis on
  both private and public datasets. We also show that our method achieves a high performance
  under conditions of significant class imbalance because it automatically selects
  samples from the minority classes.
links:
- name: URL
  url: https://doi.org/10.1016/j.media.2024.103262
---
