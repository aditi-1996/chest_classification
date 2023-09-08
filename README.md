# Introduction

This project aims to classify chest x-rays into 14 classes using DenseNet121 on `NIH-14 dataset` and use `SHAP` methods to explain the predictions.

## Directory Structure

```bash
.
├── notebooks
│   ├── nih-chest-xray-classification.ipynb
│   └── shap-xray.ipynb
└── README.md
```

- `notebooks/nih-chest-xray-classification.ipynb`: This notebook trains DenseNet121 for dieseas classification into 14 classes and calculate per-class AUC score.

- `notebooks/shap-xray.ipynb`: This notebook uses the trained weights from prior notebook and uses SHAP to explain the predcition by overlaying pixels contributing towards prediction.

## Setup Instructions

- Create virtual environment: `python3 -m venv chest_classification`
- Activate virtual enviromnet: `source chest_classification/bin/activate`
- Install necessary packages: `python3 -m pip install -r requirements.txt`

