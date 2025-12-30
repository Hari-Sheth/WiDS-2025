# WiDS-2025

Repository where I store all the work I did and learnt during WIDS '25

## Files

### Linear_Regression.ipynb
Linear_Regression.ipynb is a file where I learnt how to write code that points out the best-fit line to a given set of points.

### Assignment_1.ipynb (as Week 1 Assignment)
Using a fullly connected neural network(without convolutions) to identify handwritten digits using the MNIST dataset. The network had a loss of around 0.03 and accuracy of 98.42\% after optimising the hyperparameters, however the model perfomed badly on custom input. I tried to debug the problem, and in the process I edited the image to have a black background as in actual MNIST images, and set the mean and variance for the pixel values so that the model would not give wrong output due to skewed pixel values. The model's predictions were now better but still not up to the mark.

### Assignment_1-using-CNN.ipynb
Implemented a CNN to identify handwritten digits since the fully-connected model was not satisfactory. This model showed much better results than before.

### Assignment_2.ipynb (as Week 2 Assignment)
Used the Intel Image Classification Dataset to classify images in 6 classes namely buildings, forest, glacier, mountain, sea and street. Worked nicely on custom images although it showed an accuracy of 81.4\% on testing dataset.
