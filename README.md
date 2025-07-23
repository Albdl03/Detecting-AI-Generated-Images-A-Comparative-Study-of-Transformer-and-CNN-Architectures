# Detecting AI-Generated Images Using Transformer Architectures: A Comparative Analysis

## Overview

This repository supports the MSc Business Analytics dissertation project conducted at Trinity College Dublin by **Alberto de Leo**, under the supervision of **Dr. Soham Ghosh**. The research investigates the effectiveness of Transformer-based models—such as Vision Transformer (ViT), Swin Transformer, and BEiT—in detecting AI-generated images using the [CIFAKE] {https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images} dataset (due to size constraints the dataset is not available otn the repository, you can download it from the link).

## Motivation

With the increasing realism of AI-generated images from tools like DALL·E 2, Midjourney, and Stable Diffusion, businesses face growing challenges in maintaining content authenticity. Traditional CNN-based models have become inadequate for detection tasks. This dissertation explores whether Transformer architectures can offer superior accuracy, scalability, and explainability in identifying synthetic visual content.

## Methodology

- **Dataset:** [CIFAKE] {https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images} – 120,000 images (60K real, 60K synthetic)
- **Models Evaluated:** ViT, Swin Transformer, BEiT, ResNet-50
- **Metrics:** Accuracy, F1-score, AUC, interpretability
- **Tools & Libraries:** PyTorch, Torchvision, Hugging Face Transformers

## Key Contributions

- **Model Performance:** Transformer models significantly outperform CNNs on synthetic image detection tasks.
- **Explainability:** Visual tools (e.g., Grad-CAM, attention maps) identify how and where decisions are made.
- **Business Relevance:** Results offer actionable insights for marketing teams, brand safety analysts, and compliance units.

## Results Summary

- ViT and Swin models demonstrated improved detection accuracy and robustness.
- Attention-based models excelled in capturing semantic anomalies rather than superficial pixel-level artifacts.
- Visual explanations enhanced transparency and supported auditability for enterprise contexts.

Contact
Alberto de Leo
Email: deleoa@tcd.ie
LinkedIn: linkedin.com/in/alberto-de-leo
