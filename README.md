# Experimental Evaluation of CNN Architectures and Training Techniques for CIFAR-10 Image Classification

George Ioannidis, undergraduate student, ECE AUTH

## Overview

This project focuses on image classification on the CIFAR-10 dataset using both classical baseline classifiers and Convolutional Neural Networks. The goal is to compare the testing performance of simple baseline methods with progressively improved CNN architectures.

## Methods

The baseline classifiers include:

- Nearest Centroid
- 1-Nearest Neighbor
- 3-Nearest Neighbor

For the CNN experiments, different architectures, layer configurations and training techniques were evaluated, including:

- additional convolutional blocks
- wider filter configurations
- dropout
- batch normalization
- data augmentation
- learning rate schedulers
- weight decay
- early stopping
- Xavier initialization

## Results

The best-performing CNN achieved **91.43% test accuracy** on the CIFAR-10 test set, significantly outperforming the baseline classifiers.

## Files

- `cifar10_cnn_classification.ipynb`: implementation and experiments
- `Report.pdf`: project report
