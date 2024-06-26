# CNN-Atmospheric-Rivers

[![DOI](https://zenodo.org/badge/531778489.svg)](https://zenodo.org/doi/10.5281/zenodo.11139593)

In this tutorial (CNN_AR_tutorial.ipynb), we will use an Atmospheric Rivers dataset to train a Convolutional Neural Network (CNN) that can identify whether a map contains an atmospheric river or not.

- **Load training data:** the training data consists of chips of Integrated Vapor Transport (IVT) maps and their corresponding labels ('Atmospheric River', 'Ambiguous', or empty if these two shapes are not present. We be begin by loading the data, and preparing it for input into our neural network.
- **Train a CNN:** using the TensorFlow and Keras libraries, we'll train a CNN to classify the IVT chips (images) into one of two predifined classes. Here, Class 1 is assigned to images containing an atmospheric river, and Class 0 is assigned to images not containing an atmospheric river or containing an ambiguous shape.
- **Evaluate model performance:** after training, we'll evaluate the model on data that was not used during training.

The data being used is avaiable here: https://doi.org/10.5281/zenodo.12177339 and can be cited using:
