# Image Classification: Cats & Dogs
A convolutional neural network (CNN) pipeline for binary image classification, built and tuned end-to-end in Python.

## Overview
This project walks through a complete image classification workflow — from raw data loading and exploratory analysis through baseline modeling, iterative hyperparameter tuning, and regularization — using a cats vs. dogs dataset.

See [`mvp.ipynb`](./mvp.ipynb) for the full walkthrough and all project work.

## Project Structure
## Workflow
**1. Data Preparation**
- Load and organize image file paths
- Split data into train/validation sets
- Visualize sample images across classes

**2. Exploratory Data Analysis**
- Pixel intensity distributions by color channel
- Image dimension analysis
- Aspect ratio distribution

**3. Modeling**
- Baseline CNN training
- Batch size and learning rate optimization
- Regularization tuning (dropout, weight decay)
- Input image size optimization

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Matplotlib

## Results
Iterative tuning of batch size, learning rate, regularization strategy, and input image dimensions progressively improved model performance over the baseline.

## Author
Taylor Clements, PhD
