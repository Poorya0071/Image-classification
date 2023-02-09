# Image Classification With Deep Neural Networks:

In this repository, we are going to employ several different Deep Learning models to do image classification projects. 

## Project 1: Sports Dataset:

This dataset contains 100 different types of sports. We aim to train a Deep learning model on the training dataset and validating on the validation dataset to predict the name of sports by using an image as the input.

### Model:

We used the EfficentnetB0 from TensorFlow Hub. EfficientNet-b0 is a convolutional neural network trained using a large dataset of over a million images from the ImageNet database, enabling it to classify images into 1000 different categories, including objects like keyboards, mice, pencils, and various species of animals.

The archtecture of EfficentnetB0 

![myimage](EFNB0.png)

## Results

After training the model on the training dataset and evaluating it on the evaluation dataset for 20 epochs, the results of the prediction on the test dataset are as below. 

training_loss: 0.0052 - training_accuracy: 0.9990 

val_loss: 0.0977 - val_accuracy: 0.9680

test_loss: 0.0703 - test_accuracy: 0.9720

The results are satisfying, with more than 97% accuracy on the unseen test dataset.
