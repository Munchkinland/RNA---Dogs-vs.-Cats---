## Image Classification Project

## Overview
This project is focused on training a Convolutional Neural Network (CNN) model using TensorFlow and Keras to classify images of dogs and cats. The model uses the VGG16 architecture with additional layers for improved performance.

## Table of Contents
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Training](#training)
- [Model Evaluation](#model-evaluation)
- [Predictions](#predictions)
- [Dependencies](#dependencies)
- [License](#license)

## Project Structure
- `data/`: Contains the raw training and test image data.
- `models/`: Location to save the trained model.
- `src/`: Source code files for data preprocessing, model training, and predictions.

## Usage
1. Clone this repository to your local machine.

2. Install the required dependencies (see [Dependencies](#dependencies)).

3. Run the provided Jupyter Notebook or Python scripts in the `src/` directory to train the model.

4. After training, you can use the model to make predictions on new images (see [Predictions](#predictions)).

## Training
- The training data is stored in the `data/raw/train/` directory, with separate subfolders for dogs and cats.

- The `ImageDataGenerator` is used for data augmentation and preprocessing.

- The trained model is saved to the `models/` directory.

## Model Evaluation
- Model performance metrics such as accuracy and loss are displayed during training.

- A plot of training and validation accuracy/loss is provided for visual assessment.

## Predictions
- You can make predictions using the trained model on new images by providing the image path in the prediction script.

- Example code for making predictions is available in the README.

## Dependencies
- TensorFlow
- Keras
- NumPy
- Matplotlib

Install these dependencies using `pip` or `conda` by running:

pip install tensorflow keras numpy matplotlib
