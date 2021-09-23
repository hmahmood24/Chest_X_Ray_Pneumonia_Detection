# Convolutional Neural Network to Classify Chest Pneumonia X-Ray Images

This repository contains the source code for Classifying Chest Pneumonia X-Ray Images using a Convolutional Neural Network. This file contains the necessary information about the project environment and the steps required to run the project.

## Preliminaries 

The required packages needed to run the project can be found in the `requirements.txt` file. A better workaround, however, would be firing up a Google Colab Notebook and setting up the environment.

## Environment Setup

- Sign up or log on to https://www.kaggle.com/ with your account. Click on `My Account`. Scroll down to `API section`. Click on `Expire API Token`. Click on `Create New API Token`. This step is necessary in order to generate an access token to connect to your Kaggle account via the Kaggle API.
- Download the `.json` file to your local directory.
- Download the `chest_x_ray_pneumonia_classification.ipynb` from this repository to your local directory. 
- Open `Google Colab` and upload the `chest_x_ray_pneumonia_classification.ipynb` to the Colab Notebook.
- Run the entire script and where prompted, upload the `.json` file downloaded earlier to your Colab environment. This is necessary to link the Kaggle API with the Colab environment so that datasets can be downloaded directly to Colab.
- Please feel free to download the dataset from https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia to get a feel for the data and view the images in the `train`, `test` and `val` sub-directories.

Note: This repository is part of this [blog post](https://writersbyte.com/chest-x-ray-pneumonia-classification-using-deep-neural-networks-with-keras/)
