# Handrwritten-Digit-Recogntion

Here, I implemented a Handwritten Digit Recognition using two different models.

First, I used a multilayer perceptron (MLP) which is a class of artificial neural network (ANN). 
Here 2 dense layers were used, one with relu activation and another with a softmax activation. 
Then the model was trained for 10 epochs to get a training accuracy of 99.91% and validation accuracy of 98.18%


To improve this, I used a Convolutional Neural Network (CNN) where I added 1 convolution layer, 1 max pooling and flattened the neurons and then used a softmax activation to output one from 10 classes. 
Then the model gave a accuracy of 99.42% and validation accuracy of 99.04% for 10 epochs.


To get futhur better accuracy, one can increase the number of layers in CNN and also increase the number of epochs.
