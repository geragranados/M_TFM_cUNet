# Conditional U-Net for Multimodal TFM images generation
This repository contains the code for the paper doi: https://doi.org/10.1016/j.ndteint.2023.102906

An adapted version of the code will be available soon.

For confidential issues, the code is needed to be adapted to an open-access database with the same characteristic of the database used on the publication.

# Paper Abstract

This paper presents a deep-learning surrogate model tailored for a fast generation of realistic ultrasonic images in the Multi-modal Total Focusing Method (M-TFM) framework. The method employs both physics- and data- driven data-sets. To this end, we propose a Conditional U-Net (cU-Net) to perform a controlled generative process of high-resolution M-TFM images by spanning the set of inspection parameters, employing both the experimental data (high-fidelity acquisitions) and the simulated ones (a low-fidelity counterpart). Once trained on experimental and simulated images, the cU-Net embodies an enhanced realism, learnt from the experimental data, coupled with a quasi-real-time prediction that prevents the need for extra simulations. Moreover, our surrogate model provides a controlled M-TFM generation conditioned by the steering parameters of the simulation as well as by the physics underlying the ultrasonic testing schema. The performances of our approach are demonstrated in a case study of M-TFM images of a component with planar defects in a complex weld-like profile. Furthermore, we consider uncertainties in M-TFM image parameters reconstruction in both numerical and experimental data to reproduce the on-site inspection. Additionally, we show how the trained neural network can learn its inner layers (i.e., the cU-Net layers) according to the physical parameters at stake so that it can be considered an white-box model enabling a qualitative interpretation of the generative process.

# Real-Time Generation video

![](tfm_unet_anim.gif)

