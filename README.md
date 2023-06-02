# Flower-Image-Prediction Project Description

Main objective of this project was to learn and practice image processing in python. This project also includes ANN(Artificial Neural Network) Deep Learning model for predicting the type of flower from the input image. Note: Generally we prefer using CNN(Convolutional neural Network) but we have used ANN for exploration and practice purpose.
We will be importing data from "https://upscfever.com/datasets/flowers-new.zip" for training and validation of the ANN model.
We will be utilising the following pyhton libraries: numpy, pandas, matplotlib, os, cv2, sklearn, tensorflow, keras, for data preprocessing and model training.
Preprocessing for image data includes resizing, conversion to numpy array, label encoding and one hot encoding(for target variable) and standardising for input variables. We have used functions like flatten() from keras, which returns a 1D array for the given image array (3D), which can be further used to train ANN model.

Note: Accuracy for model is low because main focus was on learning image processing.
