# A Hybrid Multimodal Deep Learning Framework for Alzheimer’s Disease Classification and Survival Analysis Using Image and Clinical Data

## Research Publication

This repository documents my research work on a **Hybrid Multimodal Deep Learning Framework** for Alzheimer’s disease classification and survival analysis using structural MRI images and patient clinical data.

**Publication:** Procedia Computer Science
**Conference:** Eighth International Conference on Futuristic Trends in Networks and Computing Technologies (FTNCT08)
**Year:** 2026
**Publisher:** Elsevier
**Author:** Sadiya Naz Kaladgi et al.

## Abstract

This research presents a hybrid multimodal deep learning framework that combines structural MRI images with patient-specific clinical variables for Alzheimer’s disease classification and survival analysis.

The framework uses separate image and clinical encoders to extract complementary representations, followed by a late-fusion architecture for joint learning. The study evaluates EfficientNet-B0, BrainFusionNet, DenseNet-201, and an ensemble model for Alzheimer’s stage classification. Survival analysis is performed using Cox-based approaches to estimate patient-specific disease progression risk.

## Objective

To develop a multimodal deep learning framework that integrates medical imaging and clinical information to improve Alzheimer’s disease classification and provide patient-specific survival risk estimation.

## Dataset

The study uses the **OASIS dataset**, combining:

* Structural T1-weighted MRI scans
* Clinical and demographic information
* Cognitive assessment variables

The dataset was organized to associate patient clinical records with corresponding MRI images.

## Methodology

The proposed framework consists of:

1. MRI image preprocessing and normalization
2. Clinical data preprocessing and encoding
3. CNN-based image feature extraction
4. MLP-based clinical feature extraction
5. Late fusion of image and clinical embeddings
6. Classification of Alzheimer’s disease stages
7. Survival analysis for disease progression
8. Model evaluation using classification and survival metrics

## Deep Learning Models

The study evaluated:

* EfficientNet-B0
* BrainFusionNet
* DenseNet-201
* Ensemble model

The implementation used **PyTorch**, with supporting libraries including `timm`, `scikit-learn`, and `lifelines`.

## Results

The evaluated models achieved the following classification accuracies:

| Model           | Accuracy |
| --------------- | -------: |
| EfficientNet-B0 |    97.5% |
| BrainFusionNet  |    97.0% |
| DenseNet-201    |    91.0% |
| Ensemble        |    96.1% |

EfficientNet-B0 achieved the highest classification accuracy among the evaluated models.

For survival analysis, EfficientNet-B0 and BrainFusionNet achieved C-index values of **0.63** and **0.61**, respectively, with statistically significant log-rank test results.

## Key Contributions

* Developed a hybrid multimodal architecture combining MRI and clinical data.
* Investigated CNN-based image feature extraction with clinical feature embeddings.
* Implemented late-fusion learning for multimodal representation.
* Evaluated multiple deep learning architectures.
* Incorporated classification and survival-analysis components.
* Applied techniques such as data augmentation, Focal Loss, dropout, and early stopping.
* Evaluated model performance using accuracy, precision, recall, F1-score, AUC, confusion matrices, and C-index.
* Explored interpretability using Grad-CAM and SHAP.

## My Contribution

My contribution to the research included:

* Contributing to the development of the multimodal deep learning framework.
* Working with MRI imaging and clinical data for multimodal analysis.
* Contributing to data preprocessing and feature preparation.
* Working with deep learning model development and evaluation.
* Contributing to model comparison and performance analysis.
* Contributing to the research documentation and presentation of the work.

## Publication & Presentation

The research was accepted and presented at **FTNCT08** and published in **Elsevier Procedia Computer Science**.

The repository contains:

* `Research-Paper.pdf` — Published research paper
* `Presenter-Certificate.pdf` — Conference presenter certificate

## Research Paper

The complete published paper is available in this repository as `Research-Paper.pdf`.

## Disclaimer

This research is an academic machine learning study and is not intended to provide medical diagnosis or replace professional clinical assessment.
