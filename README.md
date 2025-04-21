# Image Separation Project

This project focuses on separating images using a convolutional neural network (CNN) with an encoder–decoder structure. The main goal is to take a combined image as input and return the two original, separated images. Model performance is evaluated with the mean squared error (MSE) between the predicted images and the reference images.

## Project Content

The project is provided as a Jupyter notebook containing all the code needed for data loading, preprocessing, model definition, training, and performance evaluation.

## Dataset

Datasets used for this project are:
	•	MNIST: A dataset of handwritten digits composed of 28 × 28‑pixel grayscale images, later resized to 32 × 32.
	•	Fashion‑MNIST: A dataset of clothing images, also composed of 28 × 28‑pixel grayscale images, resized to 32 × 32.

The images are normalized (dividing by 255) and randomly combined to create the model’s input dataset.

## Project functionalities

Data preprocessing: Normalization and resizing of images.

Training‑data generation: Dynamic creation of combined images from random pairs of MNIST and Fashion‑MNIST images.

Model training: Training of the CNN encoder–decoder network with a mean‑squared‑error loss function.

Performance evaluation: Analysis of model performance, metric calculation, and visualization of separation examples.

## Reference Datasets

The datasets used in this project are imported directly via TensorFlow:
	•	MNIST Dataset
	•	Fashion‑MNIST Dataset
