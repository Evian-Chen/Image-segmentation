# U-Net-segmentation
## Overview
This is a samll practice of image segmentation using U-Net architecture.

## Dataset
This dataset is from Carvana Image Masking Challenge(link in reference). Every vehicle has 16 engles and 16 mask image for each of them. Since the original dataset is too large, only 1600 images is uploaded to the google drive in this practice.
> This dataset contains a large number of car images (as .jpg files). Each car has exactly 16 images, each one taken at different angles. Each car has a unique id and images are named according to id_01.jpg, id_02.jpg … id_16.jpg. In addition to the images, you are also provided some basic metadata about the car make, model, year, and trim.

(excerpted from kaggle)

<img src="https://github.com/Evian-Chen/Image-segmentation/blob/main/feaf59172a01_16.jpg" width="300" height="200">
<img src="https://github.com/Evian-Chen/Image-segmentation/blob/main/feaf59172a01_16.jpg" width="300" height="200">

## Methodology
* Build a double convolution network for U-Net.
* Build a U-Net structure model for training later.
* Build a custom dataloader for loading data. 
* Train the model.

![UNet Architecture](https://github.com/Evian-Chen/U-Net-segmentation/blob/main/unet%20architecture.png)

## References
<a href="https://www.kaggle.com/c/carvana-image-masking-challenge">Carvana Image Masking Challenge</a>

<a href="https://arxiv.org/abs/1505.04597">U-Net: Convolutional Networks for Biomedical Image Segmentation</a>
