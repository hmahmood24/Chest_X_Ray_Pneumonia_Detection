# Convolutional Neural Network to Classify Chest X-Ray Images
This repository contains the source code for classifying Chest X-Ray Pneumonia images using a Convolutional Neural Network
This file contains the necessary information about the project environment and the steps required to run the project

## Preliminaries 
The following libraries and toolkits are required to run the source code:

- ```Python version == 3.x ```
- ```TensorFlow version == 2.3.0 ```
- ```Keras version == 2.4.3 ```
- ```NumPy version == 1.18.5 ```
- The source code will run with the aforementioned versions or higher.

## Environment Setup

- Log on to https://www.kaggle.com/ with your account. Click on `My Account`. Scroll down to `API section`. Click on `Expire API Token. Click on `Create New API Token`.
- Download the `.json` file to your local directory.
- Download the `Model_Interp_Task.ipynb` from this repository to your local directory. 
- Open `Google Colab` and upload the `Model_Interp_Task.ipynb` to the Colab Notebook.
- Check for the available versions of the toolkits and libraries in the Colab Notebook by running the following commands:
```
import tensorflow
import keras
import numpy
print(tensorflow.__version__)
print(keras.__version__)
print(numpy.__version__)

```
- Run the entire script and where prompted, upload the `.json` file downloaded earlier to your Colab environment.
 
