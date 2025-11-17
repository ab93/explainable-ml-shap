# Beyond the Black Box: Interpreting ML Models with SHAP
Materials from PyData Berlin 2025 talk on model interpretability using SHAP (SHapley Additive exPlanations).

## Overview
This repository contains code and slides demonstrating how to use SHAP for explaining machine learning models across different domains:

Case Study 1: XGBoost classifier on tabular banking data
Case Study 2: 1D CNN on time series sensor data for human activity recognition


## Quick Start

1. Clone the repo

```bash
git clone https://github.com/ab93/explainable-ml-shap.git
cd explainable-ml-shap
```

2. Install dependencies using Poetry

```bash
poetry install -v
```

3. Open the notebooks

```
jupyter notebook
```

## Case Studies

### Bank Marketing (XGBoost + TreeSHAP)

- Dataset: Portuguese bank direct marketing campaigns
- Task: Predict term deposit subscription (binary classification)
- Model: XGBoost Classifier (AUC: 0.79)
- Explanation: TreeSHAP for fast, exact explanations

### Human Activity Recognition (CNN + DeepSHAP)

- Dataset: Smartphone sensor data (accelerometer + gyroscope)
- Task: Classify 6 human activities (multiclass classification)
- Model: 1D CNN with PyTorch
- Explanation: DeepSHAP for neural network interpretability


## Citing
If you want to cite my work, please cite the paper:

```
@article{Basu2025ExplainingMP,
  title={Explaining ML predictions with SHAP},
  author={Avik Basu},
  journal={Proceedings of the Python in Science Conference},
  year={2025},
  url={https://api.semanticscholar.org/CorpusID:282192526}
}
```

