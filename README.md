# Grain Boundary Detection in Microstructure Images Using Deep Learning

This project explores the application of deep learning models for **grain boundary detection** in microstructure images, focusing on the development and evaluation of various Convolutional Neural Networks (**CNNs**) and **transfer learning** techniques.

## Overview

Advancements in **material characterization** and **machine learning** have enabled new approaches to analyzing microstructures. This study leverages deep learning models, including **U-Net**, **Xception**, and a custom **CNN**, to detect grain boundaries in microstructure images.

## Key Highlights

- **Dataset**: A dataset of **480 microstructure images** of **316L stainless steel** samples, with **hand-annotated masks**, was used for model training and evaluation.
  - High-resolution images were obtained through **grinding**, **polishing**, and **etching** techniques.
  
- **Model Architectures**:
  - **Custom CNN**
  - **Xception** (with transfer learning)
  - **U-Net** (with transfer learning)

- **Best Performance**: The **U-Net model** with transfer learning achieved **87% accuracy** in predicting grain boundaries due to its encoder-decoder design and skip connections, which preserved fine spatial details.

## Methodology

1. **Data Preprocessing**: The microstructure images were preprocessed to enhance quality and consistency.
2. **Manual Annotation**: Grain boundaries were manually annotated to create accurate masks for training.
3. **Model Training**: Various models (Custom CNN, Xception, and U-Net) were trained and optimized iteratively.
4. **Evaluation Metrics**: 
   - **Dice Coefficient**
   - **Accuracy**
   - **Segmentation performance**

## Results

- The **U-Net architecture** demonstrated the best performance, with superior boundary delineation and segmentation outcomes.
- **Quantitative metrics** were used to assess model performance, ensuring high accuracy in grain boundary prediction.

## Future Work

- **Self-made Datasets**: The next step is to train models on custom datasets to improve generalization and robustness.
- **Exploring Contour-based Methods**: Future work will explore **contour-based methods** for enhanced precision in grain boundary detection.
- **Extending to Other Materials**: The models will be adapted to work with microstructure images of other materials, expanding their utility.

## Contributions

- **Dataset Creation**: High-resolution microstructure images of **316L stainless steel**.
- **Model Development**: Implementation of CNN, Xception, and U-Net models using **TensorFlow**.
- **Performance Evaluation**: Utilization of Dice coefficient and accuracy metrics for model evaluation.



