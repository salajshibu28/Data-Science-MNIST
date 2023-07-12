# Data-Science-MNIST
This project implements a digit recognition system using the MNIST dataset. The MNIST dataset is a collection of 60,000 labeled handwritten digits, commonly used as a benchmark in the field of computer vision and machine learning.

In this project, I used machine learning and data science algorithms using python and it's libraries such as numpy, tensorflow, tensorflow_datasets, pandas to create a neural network model which would classify the input as a digit ranging from 0 to 9.
The model is fed hand-written digit which is classified as a readable digit out of the ten, pretty simple right!

So the model consists of a neural network with multiple hidden layers which i can increase or decrease according to my preference but here i took three hidden layers and then there's the output layer with 10 classes, which has proven to be effective for MNIST digit recognition tasks. The model was trained on the MNIST training set and evaluated on the test set to measure its accuracy and performance.

The code is implemented in Python, utilizing libraries such as numpy, tensorflow, tensorflow_datasets for the MNIST dataset, pandas, sklearn, seaborn, matplotlib etc. The project includes data preprocessing done by sklearn library to standardize the data, then I shuffle the data present, the I divided the dataset into three parts (training-data, validation-data and testing-data), then I added labels to the images by creating a user defined function called "scale" using which I scaled my training data + validation data and the testing data.

I created the model using tensorflow library with keras and added initial layer then 4 hidden layers of size 200 each and then the output layer, with respective activation function and compiled using the adam optimizer and for performance metrics I then calculated the accuracy of the model based on the testing data.
