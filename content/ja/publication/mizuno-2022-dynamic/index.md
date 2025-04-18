---
title: Acquiring a Dynamic Light Field Through a Single-Shot Coded Image
authors:
- Ryoya Mizuno
- Keita Takahashi
- Michitaka Yoshida
- Chihiro Tsutake
- Toshiaki Fujii
- Hajime Nagahara
date: '2022-06-01'
publishDate: '2024-01-15T05:01:00.879591Z'
publication_types:
- paper-conference
publication: '*Proc.~IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (CVPR)*'
abstract: We propose a method for compressively acquiring a dynamic light field (a
  5-D volume) through a single-shot coded image (a 2-D measurement). We designed an
  imaging model that synchronously applies aperture coding and pixel-wise exposure
  coding within a single exposure time. This coding scheme enables us to effectively
  embed the original information into a single observed image. The observed image
  is then fed to a convolutional neural network (CNN) for light-field reconstruction,
  which is jointly trained with the camera-side coding patterns. We also developed
  a hardware prototype to capture a real 3-D scene moving over time. We succeeded
  in acquiring a dynamic light field with 5x5 viewpoints over 4 temporal sub-frames
  (100 views in total) from a single observed image. Repeating capture and reconstruction
  processes over time, we can acquire a dynamic light field at 4x the frame rate of
  the camera. To our knowledge, our method is the first to achieve a finer temporal
  resolution than the camera itself in compressive light-field acquisition. Our software
  is available from our project webpage.
url_pdf: 
  https://openaccess.thecvf.com/content/CVPR2022/papers/Mizuno_Acquiring_a_Dynamic_Light_Field_Through_a_Single-Shot_Coded_Image_CVPR_2022_paper.pdf
---
