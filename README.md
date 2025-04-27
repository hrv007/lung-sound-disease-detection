# Lung Sound Disease Detection Using Attention Over Pre-trained EfficientNet Architecture

## Overview
This repository contains the implementation of a novel deep learning approach for detecting lung diseases through the analysis of lung sound audio signals. The system uses a pre-trained EfficientNet-B0 model enhanced with an attention mechanism to accurately classify various lung conditions.

## Key Features

* Robust preprocessing pipeline including Butterworth filtering (250Hz-2000Hz)
* Audio data augmentation (time stretching, pitch shifting, audio shifting)
* Feature extraction through mel spectrograms
* Pre-trained EfficientNet-B0 model with added attention mechanism
* Superior accuracy with low inference time compared to other models

## Applications

* Early detection of lung diseases
* Remote healthcare solutions
* Preliminary screening in high-volume medical settings
* Continuous monitoring of respiratory health

## Results

* Training accuracy: 99.72%
* Validation accuracy: 99.82%
* Precision, recall, and F1-scores: ~99.82%
* Significantly faster inference time compared to other pre-trained models

## Lung Diseases Detected

* Healthy condition
* COPD (Chronic Obstructive Pulmonary Disease)
* URTI (Upper Respiratory Tract Infection)
* LRTI (Lower Respiratory Tract Infection)
* Bronchiectasis
* Pneumonia

## Paper
For detailed information, please refer to our paper:
Nair, A., Vadher, H., Patel, P., Vyas, T., Bhatt, C., & Bruno, A. (2024).
Lung sound disease detection using attention over pre-trained efficientnet architecture.
Multimedia Tools and Applications. https://doi.org/10.1007/s11042-024-20078-1