# Dataset

This directory contains the battery temperature datasets used for machine learning model development.

## Dataset Organization

```text
dataset/
├── raw/
│   ├── T1_Load.xlsx
│   ├── T2_Load.xlsx
│   ├── T3_Load.xlsx
│   ├── T1_NoLoad.xlsx
│   ├── T2_NoLoad.xlsx
│   └── T3_NoLoad.xlsx
│
└── processed/
    ├── Combined_Dataset.csv
    └── Cleaned_Dataset.csv
```

## Description

The datasets contain battery temperature measurements collected from three sensor locations under both load and no-load operating conditions.

These datasets were used for preprocessing, feature engineering, model training, testing, and evaluation.
