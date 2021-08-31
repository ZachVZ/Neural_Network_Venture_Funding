# Neural_Network_Venture_Funding

This notebook uses machine learning and neural networks to create a binary classifier model that will predict whether the business will become a successful.

Below are the actions that will be performed in this notebook.
1. Prepare the data for use on a neural network model
2. Compile and evaluate a binary classification model using a neural network
3. Optimize the neural network model


## Technologies Require
* This project leverages python version 3.8.5
* pandas
* scikit-learn
* scikit metrics
* imbalanced-learn
* linear model
* train test split
* Standard Scaler OneHotEncoder
* TensorFlow
* Keras
* Project will be accomplished in JupyterLab

## Installation Guide and Running Jupyter Notebook
Installing Jupyter notebook
* On the terminal (Git Bash) under the conda dev environment, type the code below:

pip install jupyterlab

* To open the Jupyter notebook
Open a new Git Bash and type the below command into your conda dev environment:

jupyter lab

* then hit the ENTER key to run


## Required Imports
* pandas - Data manipulation and analysis
* pathlib - Imports csv files
* tensorflow - Run machine learning, deep learning and other statistical and predictive analytics
* tensorflow.keras.layers -  Easy way of creating neural networks with the interchanable layers is what makes Keras the preferred deep learning framework 
* tensorflow.keras.models - Model groups layers into an object with training and inference features. appropriate for a plain stack of layers where each layer has exactly one input tensor and one output tensor 
* sklearn.model_selection - Method for setting a blueprint to analyze data and then using it to measure new data.
* sklearn.preprocessing - Will transform your data such that its distribution will have a mean value 0 and standard deviation of 1


## Install Guide
# Imports
* import pandas as pd
* from pathlib import Path
* import tensorflow as tf
* from tensorflow.keras.layers import Dense
* from tensorflow.keras.models import Sequential
* from sklearn.model_selection import train_test_split
* from sklearn.preprocessing import StandardScaler,OneHotEncoder

## Usage
To use the notebook:
1. Clone the repo
2. Run jupter lab git bash
3. Open file venture_funding_with_deep_learning.pynb

### Contributors
Zach Zwiener

### Contact
Email - zachzwiener3@gmail.com

### License
MIT