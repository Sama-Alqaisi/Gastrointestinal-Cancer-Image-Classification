# Cancer Image Classification using Deep Learning
# Introduction
This project focuses on classifying histopathological images of gastrointestinal cancer into Microsatellite Stability (MSS) and Microsatellite Instability (MSI) categories. By utilizing various deep learning models, the aim is to accurately distinguish between MSS and MSI classes to assist in cancer diagnosis. The repository contains code notebooks and a report documenting the data preprocessing, model training, and evaluation processes.

# Dataset Overview
The dataset is organized into:
- MSS_train/: Training images for MSS class.
- MSI_train/: Training images for MSI class.
- MSS_test/: Test images for MSS class.
- MSI_test/: Test images for MSI class.
- MSS_val/: Validation images for MSS class.
- MSI_val/: Validation images for MSI class.

# Project Objectives
- Data Preprocessing: Resize and normalize images to prepare them for training and testing.
- Model Training: Train and fine-tune models including AlexNet, VGG16, GoogLeNet, ResNet18, and a custom MLP.
- Evaluation: Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

# Core Components
- Data Augmentation and Normalization: Applied transformations to enhance and standardize image data.
- Model Training: Training of multiple deep learning architectures for classification.
- Evaluation: Analysis of model performance using various evaluation metrics.

# Tools & Libraries Used
- Python: Primary programming language.
- PyTorch: Framework for developing and training deep learning models.
- TorchVision: For model architectures and image transformations.
- Matplotlib/Seaborn: For visualizing results and metrics.

# Documentation
The project includes:
- Code Notebooks: Notebooks for data preprocessing, model training, and evaluation.
- Report: A detailed report outlining data preprocessing steps, model implementations, and evaluation results.
