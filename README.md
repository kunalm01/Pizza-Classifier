# Pizza-Classifier

## Overview

This project implements a Convolutional Neural Network (CNN) to classify pizza images. It uses the TensorFlow and Keras libraries to build and train the model. The dataset consists of two classes: 'not_pizza' and 'pizza'.

The steps taken in the project are as follows:

  Load the dataset and display class names.  
  Prepare the data for training, validation, and testing.  
  Build and compile the CNN model.  
  Train the model and visualize training results.  
  Evaluate the model on the test set.  
  Make predictions on new images and verify the results.  
  
## Dataset

Link to the dataset - https://www.kaggle.com/datasets/carlosrunner/pizza-not-pizza
The dataset consists of images of pizzas and non-pizzas. It is divided into a training set (70%), a validation set (20%), and a test set (10%). The images are 256x256 pixels and have three color channels (RGB).

##Prediction

The model is used to make predictions on two new images of a pizza and a non-pizza. The images are preprocessed to match the dimensions of the training data. The model predicts whether each image is 'not_pizza' or 'pizza' with its corresponding probability.

##Conclusion

The model achieves an accuracy of 80.10% on the test set, which is a promising result given the small dataset size. The model can be improved by training it on a larger and more diverse dataset.
