# Emotions-Recognition
 with a webcam

Download the fer2013 dataset from kaggle:

https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

unzip it to get the csv file copy it to the data folder.

# Installation

Create a conda environment and install the required packages with the following commands:

conda create --name emotions-recognition

activate emotions-recognition

conda install opencv pandas pytables matplotlib keras scikit-learn tensorflow ipykernel

# Project

1) Run the "Import Data" jupyter notebook first to clean the data and create a fer2013.h5 file

2) Run the "NN_mode" jupyter notebook to train the neural network model and create a keras_model.h5 file

3) Run the "Camera" jupyter notebook to start the camera and see the prediction of the trained model 