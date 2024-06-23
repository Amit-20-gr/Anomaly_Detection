# Anomaly_Detection
Anomaly detection identifies outliers, rare events, and deviations from normal behavior. This project builds Isolation Forest and RandomForestClassifier models to detect fraudulent transactions.
## Overview

This project aims to detect fraudulent transactions by building two machine learning models: `IsolationForest` and `RandomForestClassifier`. The dataset used for this project was imbalanced, and the `SMOTE` (Synthetic Minority Over-sampling Technique) was employed to handle the imbalance. The `RandomForestClassifier` model achieved an impressive accuracy of **99.4%**, while the `IsolationForest` model achieved an accuracy of **61.4%**.
## Modeling

Two models were developed for fraud detection:

1. **Isolation Forest**: An unsupervised learning model designed to detect anomalies.
2. **RandomForestClassifier**: A supervised learning model that classifies transactions based on features, benefiting from the balanced dataset created using `SMOTE`.

## Results

- **RandomForestClassifier**: Achieved an accuracy of **99.4%**.
- **IsolationForest**: Achieved an accuracy of **61.4%**.

The `RandomForestClassifier` significantly outperformed the `IsolationForest` in this context, highlighting the effectiveness of supervised learning with a balanced dataset.
