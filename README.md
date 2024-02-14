# Plant-leaf-disease-detection
This repository contains code for a plant disease detection model implemented using the VGG19 architecture. The model is trained on the PlantVillage dataset (https://www.kaggle.com/shourov40/discussion) for identifying various plant diseases.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Setup](#setup)
- [Data Processing](#data-processing)
- [Model Implementation](#model-implementation)
- [Training](#training)
- [Testing on External Images](#testing-on-external-images)
- [Results](#results)
- [Usage](#usage)

## Introduction
This project aims to detect plant diseases using deep learning. It utilizes the VGG19 model for transfer learning and is implemented in Python using TensorFlow and Keras.

## Dataset
The dataset used for training is the PlantVillage dataset (https://www.kaggle.com/shourov40/discussion), which contains images of various plant diseases.

## Setup
- Clone the repository:
  ```bash
  git clone https://github.com/yagnavalkinis/Plant-leaf-disease-detection.git
  cd plant-disease-detection

## Data Processing
- The dataset is loaded and preprocessed using OpenCV.
- Image resizing and normalization are applied before training the model.

## Model Implementation
- VGG19 architecture is employed for transfer learning.
- The last 19 layers of the pre-trained VGG19 model are frozen.
- Additional layers (MaxPooling, Flatten, Dense) are added for classification.

## Training
- The model is trained on the dataset with a validation split.
- Training history is visualized, showing accuracy over epochs.

## Testing on External Images
- An external image can be tested using the trained model.
- The image is preprocessed and fed into the model for prediction.

## Results
Model accuracy and results on external images are presented in the jupyter file.

## Usage
- Follow the steps in the Setup section to clone the repository and install dependencies.
- Use the Jupyter notebook or colab to run the code.
- Adjust parameters as needed for your specific use case.
  
