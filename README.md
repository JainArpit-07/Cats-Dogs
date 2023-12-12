---

# Cat vs Dog Image Classification

## Overview

This project aims to build a machine learning model for image classification to distinguish between images of cats and dogs. The model is implemented using data science techniques in Python, leveraging popular libraries such as TensorFlow, Keras, Matplotlib, and OpenCV (cv2).

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Dataset](#dataset)
- [Usage](#usage)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Image classification is a common task in machine learning, and this project specifically focuses on classifying images as either cats or dogs. The model is built using the deep learning framework TensorFlow and the high-level neural networks API Keras.

## Prerequisites

Make sure you have the following libraries installed:

- TensorFlow
- Keras
- Matplotlib
- OpenCV (cv2)

## Dataset

The model is trained on a dataset consisting of labeled images of cats and dogs. The dataset used for this project can be found at (https://www.kaggle.com/datasets/salader/dogs-vs-cats).

## Usage

Download the dataset and place it in the specified folder
Input the image as test_image = cv2.imread('path')  
If the output is array([[1.]], the image is of a dog   
If the output is array([[0.]], the image is of a cat

## Training

Run the training script to train the model on the dataset.

## Results

The model achieved an accuracy of 80.22% on the validation set.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
