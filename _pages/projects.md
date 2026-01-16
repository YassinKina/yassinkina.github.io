---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

## 🚧 Poké-Classifer
**Status:** Completed |  [View Code](https://github.com/YassinKina/poke-classifier-pytorch) | [Live Demo](https://poke-classifier-pytorch.streamlit.app/)

### Technical Stack: Python | PyTorch | Torchvision | Hugging Face Datasets

### 📖 Project Overview
Deep learning models often struggle with fine-grained classification when classes share similar features. This project explores the challenges of multi-class image recognition by building a custom convolutional neural network (CNN) capable of identifying 150+ species of Pokémon with high precision.

The project covers the entire machine learning lifecycle: from raw data engineering and augmentation to deploying a live, interactive web application.

### 🚀 Key Technical Features
Custom Dynamic CNN Architecture: Built using PyTorch, the model features a modular design with configurable convolutional layers, Batch Normalization to stabilize training, and Dropout layers to prevent overfitting on specific features.

Robust Data Engineering: Leveraged the Hugging Face Datasets library to build a high-performance data pipeline. Implemented automated dataset splitting and real-time image transformations (Resizing, Normalization, and Random Flips) to improve model generalization.

Interactive Inference App: Developed and deployed a web interface using Streamlit. Users can upload local images, and the system provides real-time predictions by passing the image through the optimized inference engine.

Performance Visualization: Integrated Matplotlib and Seaborn to track training/validation loss curves and generate confusion matrices, identifying specific "visual confusion" points between similar Pokémon types.

### 📈 Results & Evolution
By transitioning from a basic linear model to a deep CNN with optimized hyperparameters, the classifier achieved significant gains in top-1 and top-5 accuracy. This project served as a foundation for my deeper work in NLP and Transformer architectures, specifically in understanding how neural networks represent high-dimensional input data.


## 📦 Amazon Product Insight Engine: Fine-Tuning RoBERTa for E-commerce
**Status:** Completed | [View Code](https://github.com/yassinkina/YOUR-REPO-NAME) | [Live Demo](https://YOUR-STREAMLIT-LINK)

### Technical Stack: Python | PyTorch | Hugging Face Transformers | Pandas | MPS (Metal Performance Shaders)

### 📖 Project Overview

Standard sentiment analysis often fails to capture the nuance of e-commerce feedback, usually reducing reviews to a binary "Positive" or "Negative" label. This project moves beyond that by fine-tuning a RoBERTa (Robustly Optimized BERT) model to predict granular 1–5 star ratings, allowing businesses to distinguish between "mediocre" (3-star) and "defective" (1-star) products.

A core focus of this project was technical efficiency: building a pipeline that manages large-scale datasets and high-compute training tasks on consumer-grade hardware (Apple M-series Silicon).

## 📈 Results & Impact
The final model achieved a 72% accuracy on a 5-class classification task, but more importantly, it demonstrated an 70%+ recall on 1-star reviews, which the baseline model missed entirely. This project showcases my ability to take a raw, imbalanced dataset and build a high-performance, hardware-optimized NLP solution.




---


