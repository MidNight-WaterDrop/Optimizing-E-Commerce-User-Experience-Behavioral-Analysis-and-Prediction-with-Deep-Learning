# Optimizing E-Commerce User Experience


## Overview
This project analyzes e-commerce user behavior to predict purchase likelihood using **DeepFM and DeepCTR** models. The goal is to enhance user experience and optimize conversion rates.

## Challenges & Solutions
1. **Sparse Data** – Used **DeepFM embeddings** for better feature representation.
2. **Dynamic Behavior** – Applied **RNNs/LSTMs** for sequential learning.
3. **Scalability** – Optimized processing with **TensorFlow & TFRecord**.

## Key Findings
- **DeepFM & DeepCTR outperformed Sequential Models**.
- **Feature selection improved predictions** (*Product Action Event Remove* was key).
- **DeepFM achieved 99.99% accuracy, far exceeding traditional models**.

## Future Work
- **Expand data sources** for richer insights.
- **Implement real-time analytics**.
- **Enhance model interpretability**.

## References
- [Shopper Intent Prediction](https://github.com/coveooss/shopper-intent-prediction-nature-2020?tab=readme-ov-file)
- [DeepCTR Documentation](https://deepctr-doc.readthedocs.io/en/latest/)

