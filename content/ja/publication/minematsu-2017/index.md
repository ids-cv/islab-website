---
title: Adaptive background model registration for moving cameras
authors:
- Tsubasa Minematsu
- Hideaki Uchiyama
- Atsushi Shimada
- Hajime Nagahara
- Rin ichiro Taniguchi
date: '2017-09-01'
publishDate: '2024-01-15T05:01:01.503289Z'
publication_types:
- article-journal
publication: '*Pattern Recognition Letters*'
doi: 10.1016/j.patrec.2017.03.010
abstract: We propose a framework for adaptively registering background models with
  an image for background subtraction with moving cameras. Existing methods search
  for a background model using a fixed window size, to suppress the number of false
  positives when detecting the foreground. However, these approaches result in many
  false negatives because they may use inappropriate window sizes. The appropriate
  size depends on various factors of the target scenes. To suppress false detections,
  we propose adaptively controlling the method parameters, which are typically determined
  heuristically. More specifically, the search window size for background registration
  and the foreground detection threshold are automatically determined using the re-projection
  error computed by the homography based camera motion estimate. Our method is based
  on the fact that the error at a pixel is low if it belongs to background and high
  if it does not. We quantitatively confirmed that the proposed framework improved
  the background subtraction accuracy when applied to images from moving cameras in
  various public datasets.
tags:
- Background subtraction
- Moving camera
- Moving object detection
- Re-projection error
---
