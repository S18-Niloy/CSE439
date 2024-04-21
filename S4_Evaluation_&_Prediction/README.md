# Evaluation and Prediction Overview

## Validation and Test Results

- **Validation Loss**: 0.466
- **Validation Accuracy**: 0.789
- **Test Loss**: 0.335
- **Test Accuracy**: 0.878

## Description

This repository contains evaluation and prediction results for a semantic segmentation model trained using the UNet architecture. The model was trained on a dataset of aerial imagery annotated with pixel-wise semantic segmentation labels.

## Evaluation

The model's performance was evaluated using both a validation set and a separate test set. The validation loss and accuracy metrics indicate the model's performance on a portion of the dataset not used during training. Similarly, the test loss and accuracy metrics provide an assessment of the model's generalization to unseen data.

## Prediction

Prediction was performed on a randomly selected sample from the test set. The original image, ground truth mask, and predicted mask overlaid on the original image are visualized to demonstrate the model's segmentation performance.

![image](unet_pred.png)
