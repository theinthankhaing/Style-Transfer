# Style Transfer

## Project Overview

* Implemented this project based on paper titled, ["Image Style Transfer Using Convolutional Neural Networks"](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)
* Take a content image and a style image 
* Produce a new image which reflects the content of the content image but the artistic "style" of the style image
* Calculate the loss function (combination of content loss and style loss) which matches the content and style of each respective image in the feature space
* Perform gradient descent on the pixels of the image itself
* Pre - trained deep neural network, [SqueezeNet](https://arxiv.org/abs/1602.07360) is used
* CPU is used
* Pytorch is used
_____________________________________________________

## Environment Setup

* Anaconda 
* Jupyter Notebook
* Pytorch
* Python 3.7
____________________________________________________________

## Procedures

* Content loss, Gram matrix and style loss are calculated first by using equations from [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)
* Pre-process images and resize it to 224 x 224 
* Extract features using model.features 
* Target image is calculated and features are extracted
* Adam optimizer is used
* Total loss computation is calculated
* Output image is obtained by using deprocessing function on target image
_________________________________________________________________________

## Result
![image](https://user-images.githubusercontent.com/50255936/110827029-a18b4700-82d0-11eb-9f74-eeacffe7f2b4.png)
