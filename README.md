# Image Decomposition

This project was developed as part of the "Introduction to Machine Learning" course at the University of Bologna. The objective is to decompose a combined image into its original components using a neural network.

## Overview

The network takes a combined image as input and predicts two outputs corresponding to two different image sources:
- A digit image (dataset MNIST).
- A fashion image (dataset Fashion-MNIST).

## Evaluation

Model performance is evaluated using the mean squared error (MSE) between the predicted images and the original ones (final mse = 0.00039955846).

## Notes

- All images are resized to the same resolution with no additional pre-processing.
- The accompanying notebook has been executed on Google Colab.
