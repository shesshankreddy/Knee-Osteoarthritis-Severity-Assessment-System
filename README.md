# Prediction of Knee Osteoarthritis Severity from X-Ray Images Using Ensemble Learning

This repository contains the code and models for a deep learning-based approach to predict knee osteoarthritis (OA) severity from X-ray images. The model utilizes an ensemble of MobileNet and InceptionV2  architectures to enhance classification accuracy, providing a reliable tool for medical diagnosis.

## Table of Contents
- [Project Overview](#project-overview)
- [Models Used](#models-used)
- [Dataset](#dataset)


## Project Overview

Knee osteoarthritis is a common degenerative joint disease affecting millions globally. Accurate and early detection of the severity of knee OA is crucial for better treatment outcomes. This project aims to predict knee OA severity using deep learning models, classifying X-ray images into three categories:
- Healthy
- Moderate OA
- Severe OA

The ensemble model combines EfficientNet and DenseNet architectures, achieving a classification accuracy of **94.76%** on the test dataset.

## Models Used

- MobileNet
- InceptionV2 
- DenseNet

## Dataset

The dataset used in this project consists of knee X-ray images graded using the **Kellgren and Lawrence** system, a standard for assessing the severity of osteoarthritis:
- **Grade 0**: No OA
- **Grade 1-2**: Mild OA (classified as "Healthy")
- **Grade 3**: Moderate OA
- **Grade 4**: Severe OA




