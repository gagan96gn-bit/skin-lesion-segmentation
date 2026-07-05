# Skin Lesion Segmentation

U-Net-based semantic segmentation model for detecting skin lesion boundaries, trained on the ISIC 2018 Challenge dataset.

## Overview
Segments dermoscopic images to identify lesion regions pixel-by-pixel, a foundational task in automated skin cancer screening pipelines.

## Approach
- **Dataset:** ISIC 2018 Task 1 (lesion boundary segmentation), with separate training and validation image/ground-truth sets
- **Model:** U-Net built from scratch — encoder-decoder architecture with convolutional blocks, batch normalization, and skip connections
- **Evaluation metrics:** Dice coefficient and IoU (Intersection over Union), tracked across training and validation

## Tools
Python, TensorFlow/Keras, OpenCV, albumentations, Google Colab (GPU)

## How to run
1. Open the notebook in Google Colab
2. Download the ISIC 2018 dataset via KaggleHub
3. Run cells sequentially — data loading, U-Net model build, training, Dice/IoU evaluation on test set
