---
title: "Angular Super-Resolution in Diffusion MRI with a 3D Recurrent Convolutional Autoencoder"

authors:
- admin
- Paul Armitage
- Mauricio A. Álvarez

date: "2022-03-29T00:00:00Z"
doi: "10.48550/arXiv.2203.15598"

publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Medical Imaging with Deep Learning 2022*"
publication_short: In *MIDL 2022*

abstract: "High resolution diffusion MRI (dMRI) data is often constrained by limited scanning time in clinical settings, thus restricting the use of downstream analysis techniques that would otherwise be available. In this work we develop a 3D recurrent convolutional neural network (RCNN) capable of super-resolving dMRI volumes in the angular (q-space) domain. Our approach formulates the task of angular super-resolution as a patch-wise regression using a 3D autoencoder conditioned on target b-vectors. Within the network we use a convolutional long short term memory (ConvLSTM) cell to model the relationship between q-space samples. We compare model performance against a baseline spherical harmonic interpolation and a 1D variant of the model architecture. We show that the 3D model has the lowest error rates across different subsampling schemes and b-values. The relative performance of the 3D RCNN is greatest in the very low angular resolution domain. Code for this project is available at [github.com/m-lyon/dMRI-RCNN](https://github.com/m-lyon/dMRI-RCNN)."

tags: [Diffusion MRI, Deep Learning, Angular super-resolution, Recurrent CNN, Image Synthesis]

# Display this page in the Featured widget?
featured: true
---