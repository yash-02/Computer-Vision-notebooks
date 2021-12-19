# Resnet50
 
ResNets are called Residual Networks. ResNet is a special type of Convolutional Neural Network (CNN) 
that is used for tasks like Image Recognition.

![Architecture](https://miro.medium.com/max/2000/1*6hF97Upuqg_LdsqWY6n_wg.png)

## Requirements
* Python 3.x
* Tensorflow 1.x

## dependencies 
* Tensorflow hub (it provides resnet api)

## Functions
* ResNet50(...): Instantiates the ResNet50 architecture.

* decode_predictions(...): Decodes the prediction of an ImageNet model.

* preprocess_input(...): Preprocesses a tensor or Numpy array encoding a batch of images.
