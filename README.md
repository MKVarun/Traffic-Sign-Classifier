# Traffic-Sign-Classifier
In this project, we have used deep neural networks and convolutional neural networks based on the LeNet architecture to classify traffic signs. We have trained and validated a model so that it can classify traffic sign images using the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). We have obtained a test accuracy of **97.87%** on the test set.

## Dataset
We have used the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). The training set has 34799 traffic sign images, validation set has 4471 images and test set has 12630 images each having a dimension of 32x32x3 (RGB images).

## Models
We have trained 3 models based on the LeNet architecture:

1) Model with normalised images and no dropout layers
2) Model with normalised images and dropout layers
3) Model with augmented images and dropout layers.

## Future Improvements
While we have obtained good results, we believe that we can achieve even better performance in the future by testing more hyperparameter variations (e.g. dimensions of fully connected layers) as well as exploring novel ANN architectures such as GoogLeNet's Inception Module, Resnet, or Xception.

