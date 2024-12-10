# Few-Shot Learning for Disease Prediction: Analysis on Biomedical Datasets

## Overview

This study addresses the critical challenges of data scarcity in healthcare diagnostics, particularly for rare diseases, and introduces a novel few-shot learning (FSL) framework that leverages pre-trained biomedical models to achieve robust disease prediction from minimal labeled data.

## Key Insights

Our research highlights the limitations of traditional and zero-shot learning (ZSL) approaches in this domain, achieving only 4.76% accuracy with ZSL methods. By employing a pre-trained BioBERT model fine-tuned with meta-learning strategies, our proposed FSL framework demonstrates significant improvements, achieving:

- **Accuracy**: 80.95%
- **F1-score**: 77%

These findings underscore the potential of FSL in resource-constrained medical settings and its scalability across multimodal healthcare applications.

## Model Implementation

This repository contains the implementation of the few-shot learning (FSL) framework for disease prediction. The code leverages a pre-trained BioBERT model fine-tuned on biomedical data with meta-learning techniques.

