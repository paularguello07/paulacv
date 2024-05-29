---
title: Privacy Preserving Image Captioning
date: 2024-01-01
summary: "Privacy-preserving scene captioning using a learned refractive lens 📸🔒"
image: 
    preview_only: true

show_breadcrumb: true
authors:
    - admin
    - Jhon Lopez
    - Carlos Hinojosa
    - Karen Sanchez
    - Hoover Rueda-Chacón
    - Henry Arguello 
---
![screen reader text](/privacy/full_method.png "Proposed end-to-end model. The optical encoder incorporates a camera with a refractive lens, which is parametrized by a linear combination of Zernike polynomials. The decoder is formed by a convolutional feature extraction and an LSTM Network with attention, which produces a caption from the private image")

**Scene captioning**, the task of describing visual information using text, typically relies on high-resolution images, raising privacy concerns due to potential exposure of sensitive data like facial attributes. This project introduces a novel solution to protect privacy by integrating optics design with algorithms, using a learned refractive lens to obscure sensitive visual attributes in the acquired image while still enabling accurate scene captions. 📸🔒

### Key Features

- **Privacy-Preserving Lens:** A specially designed lens that distorts sensitive attributes, such as faces, ethnicity, and gender, ensuring privacy before image acquisition.
- **Optimized Deep Learning:** Combines an optimized refractive lens with a deep network architecture for end-to-end scene captioning from distorted images. 🤖🔍
- **Comprehensive Evaluation:** Validated through extensive simulations and hardware experiments, showing a superior balance between privacy and utility.
## Published Papers

[📌 **Optics lens design for privacy-preserving scene captioning**: ]({{< relref "/publication/ICIP2022-privacy" >}})_Paula Arguello, Jhon Lopez, Carlos Hinojosa, Henry Arguello_**🏆BEST PAPER AWARD ICIP 2022🏆**

[📌 **Learning to Describe Scenes via Privacy-aware Optical Lens**: ]({{< relref "/publication/LATINX2024cvpr-privacy" >}})_Paula Arguello, Jhon Lopez, Karen Sanchez, Carlos Hinojosa, Hoover Rueda-Chacón, Henry Arguello_ **LatinX at CVPR 2024**


## Results
### Ablation against other privacy-preserving approaches
![screen reader text](/privacy/ablation.png "Qualitative results on two test set samples. Insets display the SSIM and Meteor between the distorted and original images")

### Robustness to deconvolution
![screen reader text](/privacy/attacks.png "Evaluation of the robustness of our lens-protected images against deconvolution attacks. Qualitative results show that the identities of individuals cannot be recovered after applying non-blind (Wiener) and blind (DeblurGANv2) deconvolution")

## Hardware Implementation

![screen reader text](/privacy/lab.jpg "(Top) Experimental hardware setup for our proposed privacy-preserving image captioning approach. (Bottom) PSFs and qualitative results on an image example acquired with a conventional camera (left), our proof-of-concept camera (middle), and simulated camera (right)")


## Related Papers

Related works that you may be interested 👇

[🔗 **Privhar: Recognizing Human Actions From Privacy-Preserving Lens**:](https://carloshinojosa.me/project/privhar/) _Carlos Hinojosa, Miguel Marquez, Henry Arguello, Ehsan Adeli,Li Fei-Fei, Juan Carlos Niebles._

[🔗 **Learning Privacy-preserving Optics for Human Pose Estimation**: ](https://carloshinojosa.me/publication/conf-iccv2021/) _Carlos Hinojosa, Juan Carlos Niebles, Henry Arguello._