# Style Transfer

## Project Overview

* Implemented this project based on paper titled, "[Image Style Transfer Using Convolutional Neural Networks]"(https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)
* Take a content image and a style image 
* Produce a new image which reflects the content of the content image but the artistic "style" of the style image
* Calculate the loss function (combination of content loss and style loss) which matches the content and style of each respective image in the feature space
* Perform gradient descent on the pixels of the image itself
* Pre - trained deep neural network, [SqueezeNet](https://arxiv.org/abs/1602.07360) is used
* CPU is used
* Pytorch is used

## Environment Setup

* Anaconda 
* Jupyter Notebook
* Pytorch
* Python 3.7

## Procedures

* Content - Loss is calculated using the following equation:
