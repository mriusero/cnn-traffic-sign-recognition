# DEEP-LEARNING-PROJECT
**Road Sign Classification**  

This repository contains a comprehensive project focused on the classification of road signs, a key field in computer vision. The project explores the development of a high-performing deep learning model optimized for identifying and categorizing road signs to support traffic regulation. The model leverages the GTSRB dataset and employs advanced techniques to ensure robustness and accuracy across various conditions.  

## Project Background

### Motivation  
Automatic recognition of road signs is essential for autonomous driving systems and driver assistance technologies (ADAS), helping vehicles interpret traffic signs reliably.

### Objectives  
The primary goal is to design a deep learning model for classifying road signs with high accuracy and generalization across diverse environments.

## Key Features

- **Data Augmentation**: Enhanced dataset variability through rotation, flipping, zooming, and cropping techniques to boost generalization.
- **Regularization Techniques**: Application of Dropout to mitigate overfitting, alongside Batch Normalization to improve training stability and efficiency.
- **Optimized Model Development**: Implementation of both a CNN and a ResNet-inspired model with hyperparameter tuning to enhance accuracy and robustness.
- **Adversarial Testing**: Model evaluation under adverse conditions, including noise, movement, and occlusion, to assess robustness.

## Dataset and Data Preprocessing

- **GTSRB Dataset**: A comprehensive set of images for road sign classification, containing 43 distinct classes with metadata on shape, color, and pictogram ID.
[GTSRB - German Traffic Sign Recognition Benchmark](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
- **Preprocessing Steps**: Image resizing, normalization, data splitting, augmentation, and one-hot encoding of labels to prepare data for robust model performance.

## Architecture and Methodology

- **Training and Experimentation**: Layer-wise visualization of activations in CNNs to identify key features, address overfitting, and refine the model.
- **Grad-CAM Analysis**: Utilizes Grad-CAM for visual interpretation, highlighting the most influential areas for each model prediction.

## Conclusions

- **Model Selection**: The "ResNet Inspired" model shows resilience in challenging conditions, while the "Regularized CNN" model suits resource-constrained environments.
- **Workflow Importance**: A consistent workflow is essential for deep learning model training.
- **Complexity vs. Performance**: Training quality is more impactful on performance than model complexity.
- **Analysis Techniques**: Advanced analysis techniques, such as Grad-CAM, optimize model effectiveness for real-world application needs.

