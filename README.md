# Machine-Learning-Project
In this project, the goal is to build a classifier that distinguishes images of 20 bird species. 

## Tools
It was completed by using Keras, Sklearn and Python.

## How the project was completed
**1. Data Pre-processing**
  - Encode the classes using one-hot en-coding.
  - Randomly select 0.7i images from each folder as training set, 0.15i as validation set, and the rest as test set, where i is the number of images in each folder.
  - Resize all the images to the same size.
  
**2. Transfer Learning**
  - Use pretrained models EfficientNetB0 and VGG16 for the last layer.





