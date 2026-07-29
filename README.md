# AI-Based Satellite Image Classification Using EuroSAT

## Overview

This project uses deep learning to classify satellite images into different land-cover categories.

A Convolutional Neural Network (CNN) was developed and trained using the EuroSAT dataset, which contains Sentinel-2 satellite images from 10 different land-cover classes.

## Research Question

How accurately can a deep learning model classify different land-cover types from satellite imagery?

## Dataset

The EuroSAT dataset contains 27,000 satellite images divided into 10 classes:

- AnnualCrop
- Forest
- HerbaceousVegetation
- Highway
- Industrial
- Pasture
- PermanentCrop
- Residential
- River
- SeaLake

## Methodology

The project followed these steps:

1. Loaded the EuroSAT satellite image dataset
2. Preprocessed and normalized images
3. Built a Convolutional Neural Network
4. Trained the model using labeled satellite images
5. Evaluated performance using:
   - Accuracy
   - Loss curves
   - Classification report
   - Confusion matrix

## Model Architecture

The CNN model contains:

- Three convolutional layers
- Max pooling layers
- Dense classification layers
- Dropout regularization
- Softmax output layer

## Results

The model was evaluated using validation data.

Validation Accuracy:

88.67%

The model was able to successfully classify multiple land-cover categories while showing some difficulty distinguishing visually similar classes.

## Visual Results

### Accuracy Curve

![Accuracy Curve](paper_figures/accuracy_curve.png)

### Loss Curve

![Loss Curve](paper_figures/loss_curve.png)

### Confusion Matrix

![Confusion Matrix](paper_figures/confusion_matrix.png)

## Applications

This project demonstrates potential uses of AI in:

- Environmental monitoring
- Land-use classification
- Remote sensing analysis
- Forest and ecosystem monitoring

## Future Improvements

Future improvements could include:

- Transfer learning with models such as ResNet or EfficientNet
- Using multispectral Sentinel-2 bands
- Adding data augmentation
- Testing on additional satellite datasets
