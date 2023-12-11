# CSCI4050U_FinalProject
Final Project for CSCI4050U Machine Learning

## Overview

This repository contains three notebooks to solve the classification problem of interpreting sign language gestures associated with (most of) the letters in the Latin alphabet.

## Dataset

The dataset used can be found on [Kaggle](https://www.kaggle.com/datasets/datamunge/sign-language-mnist?select=amer_sign2.png). There are 27455 cases in the training data and 7172 cases in the test data, each of these is a single 28x28 image. The folder containing the dataset is located in the root directory.

## Classification Approaches

There are notebooks to implement the following classification approaches:
- Decision Tree
- K-Nearest Neighbours
- Convolution Net

Each of these notebooks are contained in a separate sub-directory.

## Deployment

These notebooks can be modified, used, and/or deployed in the following manner:

1. Go to [Google Colab](colab.research.google.com)
2. Open a new notebook and choose the `GitHub` tab
3. Copy the following url and put it into the search bar: `https://github.com/MatthewSharpOTU/CSCI4050U_FinalProject/`
4. Google Colab will list each of the `.ipynb` files in the repository. Click the desired notebook and it will open in Google Colab.
5. If desired, make a copy of the notebook (File->Save a Copy)
6. It may be necessary to update the import location for the training and testing dataframes - if so, use the following urls, respectively:
- `https://raw.githubusercontent.com/MatthewSharpOTU/CSCI4050U_FinalProject/main/dataset/sign_mnist_train.csv`
- `https://raw.githubusercontent.com/MatthewSharpOTU/CSCI4050U_FinalProject/main/dataset/sign_mnist_test.csv`
7. You're all set!