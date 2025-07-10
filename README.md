# ReflexLearningAlgorithm-MedicalClassification

This repository contains the source code and documentation for the **Reflex Learning Algorithm (RLA)**

The RLA is developed to achieve high recall and computational efficiency in resource-constrained clinical settings, suitable for real-time diagnostics. It was evaluated on three UCI datasets: Breast Cancer Wisconsin (Original), Heart Disease, and Hepatitis, demonstrating superior recall and efficiency compared to baseline models like Decision Trees, Logistic Regression, and Random Forests.

## Overview

The Reflex Learning Algorithm (RLA) is a lightweight, interpretable classifier inspired by biological reflexes, designed for high-recall classification of critical medical cases. It uses automated threshold-based reflex zones to prioritize rapid detection of high-risk patterns (e.g., clump thickness in breast cancer or ST depression in heart disease) with minimal computational overhead. The algorithm is particularly suited for low-resource environments, such as rural clinics or low-power diagnostic devices, achieving 100% recall for Heart Disease and Hepatitis (non-SMOTE) datasets and 91.67% for Breast Cancer.

This repository provides the Python implementation of RLA as a scikit-learn estimator, along with scripts for preprocessing, training, and evaluation on UCI medical datasets.

## Dataset

The RLA was evaluated on three UCI Machine Learning Repository datasets:

- **Breast Cancer Wisconsin (Original)**: 463 instances (after deduplication), 9 numeric features, class distribution (238:225). [DOI: 10.24432/C5HP4Z]
- **Heart Disease**: 303 instances, 13 features (6 numeric, 7 categorical), class distribution (139:164). [DOI: 10.24432/C52P4X]
- **Hepatitis**: 155 instances, 19 features (6 numeric, 13 categorical), class distribution (32:123), with SMOTE-balanced configuration (208 instances, 104:104). [DOI: 10.24432/C5Q59J]

Datasets are publicly available at the UCI Machine Learning Repository. Preprocessing steps include deduplication, imputation, outlier capping, one-hot encoding, and SMOTE.

## Contact
Linkedin: [Michael Angello Qadosy Riyadi](https://www.linkedin.com/in/michaelangelloqr/)
