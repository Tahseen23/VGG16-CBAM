# CNN+Attention: VGG16 and VGG16-CBAM Models

This repository contains the implementation and training scripts for two Convolutional Neural Network (CNN) models:
1. VGG16
2. VGG16 with Convolutional Block Attention Module (CBAM)

## Table of Contents
- [Introduction](#introduction)
- [Models](#models)
- [Setup](#setup)
- [Training](#training)
- [Results](#results)
- [License](#license)

## Introduction
The purpose of this project is to compare the performance of a standard VGG16 model against a VGG16 model enhanced with CBAM. CBAM integrates attention mechanisms that are supposed to improve the model's ability to focus on relevant features in the input data.

## Models
1. **VGG16**: A well-known CNN architecture introduced by Simonyan and Zisserman in 2014.
2. **VGG16-CBAM**: An enhanced version of VGG16 with the CBAM integrated into its convolutional layers.

![first](<Screenshot 2024-06-11 194031.png>)


### Prerequisites
Ensure you have the following installed:
- Python 3.7 or higher
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib

### Results

| Model | train acc | val acc|
| --- | --- | --- |
| VGG16 | 1.0 | 0.8900|
| VGG16 + CBAM | 1.0 | 0.85|


