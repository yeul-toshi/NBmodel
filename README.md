# NBmodel

Nuclei segmentation by NB(Nuclei Boundary) model.
This tutorial is a personal implementation based on the paper.

## Papers referenced.

Cui, Y., Zhang, G., Liu, Z. et al. A deep learning algorithm for one-step contour aware nuclei segmentation of histopathology images. Med Biol Eng Comput 57, 2027–2043 (2019). https://doi.org/10.1007/s11517-019-02008-8

## Frameworks

Tested with Tensorflow==2.1.0 and Keras 2.3.1.

## Dataset used in this tutorial

https://monuseg.grand-challenge.org/Data/
In this tutorial, the original 1000x1000 image was resized to 1024x1024 and then divided into 16 sections to create 256x256 images.
