# Image Segmentation using U-Net

## Overview
This project implements an image segmentation model using a **U-Net architecture** to segment bee frames from images while filtering out unnecessary elements. The dataset consists of images with **YOLO-format annotations**, which are converted into segmentation masks for training a deep learning model.

The trained model achieves high segmentation accuracy with the following evaluation metrics:
- **Validation Loss:** 0.1392
- **Validation Accuracy:** 83.24%
- **Mean Average Precision (mAP):** 0.8058
- **F1 Score:** 0.8611

---
## Repository Structure
- **data**: Directory for storing raw and processed data.
- **notebook**: Jupyter notebooks for experimentation, implementation and visualization.
- **results**: Predictions, metrics, and plots
- **model**: Saved trained model
- **README.md**: Project documentation
- **requirements.txt**: Dependencies