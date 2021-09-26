
# Scene Interpretation

This project is a part of a Visual Intelligence workshop conducted by CEVI LAB at KLE Technological University

## Objective
This project aims at providing aid to visually challenged community by interpreting scenes and captioning images. And additionally using the captions to generate audio for visual aid. This project uses [MS COCO dataset](http://cocodataset.org/#home) for training and testing. 

## Project description
The model architecture in this project is similar to [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention.](https://arxiv.org/abs/1502.03044). An attention based model is used which enables us to see the parts of the image that were attended to generate the caption. The features of images are extracted using pretrained Inception V3 model. An encoder-decoder model is trained on the vocabulary from the dataset to generate accurate captions.

## Demo-Preview

The following is a testing image

![Testing Image](https://github.com/khushijain21/scene_interpretation/blob/main/Unknown.png)

The model returns a caption for the image from the vocabulary it was trained on. The bounding boxes help us know the parts of the image that were attended. 

![Image](https://github.com/khushijain21/scene_interpretation/blob/main/final.png)


## Installation

The code can be directly used on google colab.

Before running it locally on Jupyter, please ensure the installation of following Python libraries:

* Tensorflow
* Matplotlib
* Collections
* Random
* Numpy
* OS
* Time
* JSON
* GTTS (Google Text to Speech)


## Contribute

Please feel free to contribute to this project to better achieve the objective. 
