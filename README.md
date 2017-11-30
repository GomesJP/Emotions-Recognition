# Emotions-Recognition


Download the fer2013 dataset from kaggle:

https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

unzip it to get the csv file copy it to the data folder.

# Installation

This project was done on python version 3.6

Create a conda environment and install the required packages with the following commands:

1) conda create --name emotions-recognition --file emotions-recognition.txt

OR try your luck manually:

1) conda create --name emotions-recognition

2) activate emotions-recognition

3) conda install opencv pandas pytables matplotlib keras scikit-learn tensorflow ipykernel pillow graphviz pydotplus

4) pip install keras-vis 

Finally:

A) Install graphviz from http://www.graphviz.org/ and add its bin folder to PATH
(this step is needed only to visualize the resulting CNN layers as a graph)

# Project

1) Run the "Import Data" jupyter notebook first to clean the data and create a fer2013.h5 file

2) Run the "NN_model" jupyter notebook to train the neural network model and create a keras_model.h5 file

3) Run the "feature_visualization" jupyter notebook to see some examples of predictions and see important pixels used by the CNN for the prediction.

4) Run the "Camera" jupyter notebook to start the camera and see the prediction of the trained model 
