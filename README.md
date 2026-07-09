<p align="center">
  <img src="images/banner.png" alt="Project Banner" width="100%">
</p>

# Machine Learning-Based Battery Temperature Fault Detection System for Electric Vehicles
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Random Forest](https://img.shields.io/badge/Random%20Forest-Model-success)
![XGBoost](https://img.shields.io/badge/XGBoost-Enabled-red)
![LightGBM](https://img.shields.io/badge/LightGBM-Enabled-green)
![CatBoost](https://img.shields.io/badge/CatBoost-Enabled-yellow)
![License](https://img.shields.io/badge/License-MIT-blue)
![Patent](https://img.shields.io/badge/Patent-Published-success)
![Electric Vehicle](https://img.shields.io/badge/Application-Electric%20Vehicle-darkgreen)

> Published Indian Patent Application | Machine Learning | Electric Vehicles | Battery Management System | Predictive Maintenance

---

## Overview

Machine Learning-Based Battery Temperature Fault Detection System for Electric Vehicles is a patent-based project developed to detect abnormal battery temperature conditions using machine learning techniques.

The project analyzes battery temperature data collected under normal and abnormal operating conditions to identify potential battery faults before failure occurs. Four machine learning algorithms are implemented and compared to determine the most accurate prediction model.

This repository presents the implementation and machine learning workflow developed for the published Indian Patent Application titled **"Machine Learning-Based Battery Temperature Fault Detection System for Electric Vehicles."**

---
## My Contributions

This repository showcases my implementation and technical work related to the published patent application.

My contributions include:

- Battery temperature dataset preparation and preprocessing
- Feature engineering and data analysis
- Development of Random Forest, XGBoost, LightGBM, and CatBoost models
- Model training, testing, and performance evaluation
- Experimental analysis and result visualization
- Project implementation and technical documentation

## Patent Information

| Item | Details |
|------|---------|
| Patent Title | Machine Learning-Based Battery Temperature Fault Detection System for Electric Vehicles |
| Application Number | 202541123226 |
| Filing Date | 06 December 2025 |
| Publication Date | 02 January 2026 |
| Patent Status | Published Indian Patent Application |
| Current Status | Awaiting Request for Examination |
| Applicant | Vellore Institute of Technology |
| Official Source | Indian Patent Office (IPO), Government of India |

The official patent publication (`Patent_Application_Publication.pdf`) is available in the `docs/` folder of this repository.

---

## Features

- Battery temperature fault detection
- Predictive maintenance
- Real-time battery health analysis
- Machine learning based fault prediction
- Comparison of multiple ML algorithms
- Data preprocessing and feature engineering
- Performance evaluation using multiple metrics
- EV battery safety enhancement

---

## Machine Learning Models

| Model | Purpose |
|--------|---------|
| Random Forest | Ensemble learning model used for accurate battery temperature fault detection. |
| XGBoost | Gradient boosting model for high-performance prediction and fault classification. |
| LightGBM | Fast gradient boosting framework optimized for efficient model training. |
| CatBoost | Gradient boosting algorithm with robust handling of complex feature relationships. |

### Model Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## Technology Stack

### Programming Language

- Python

### Libraries

- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost

### Tools

- Jupyter Notebook
- Visual Studio Code
- Git
- GitHub

---
## System Workflow

```mermaid
flowchart TD

A[Battery Data Collection]
B[Data Preprocessing]
C[Feature Engineering]
D[Train-Test Split]
E[Random Forest]
F[XGBoost]
G[LightGBM]
H[CatBoost]
I[Model Evaluation]
J[Fault Detection]
K[Performance Comparison]
L[Battery Safety & Predictive Maintenance]

A --> B
B --> C
C --> D
D --> E
D --> F
D --> G
D --> H
E --> I
F --> I
G --> I
H --> I
I --> J
J --> K
K --> L
```
## System Architecture

<p align="center">
  <img src="images/architecture/system_architecture.png" width="90%" alt="System Architecture">
</p>

The proposed system collects battery temperature, voltage, and current data from the battery pack. The acquired data undergoes preprocessing and feature engineering before being used to train multiple machine learning models. The best-performing model is selected for battery fault detection and predictive maintenance.

```
## Repository Structure

ML-Based-EV-Battery-Fault-Detection-System
│
├── docs/
│   ├── Patent_Application_Publication.pdf
│   ├── Complete_Specification.pdf
│   ├── PATENT.md
│   ├── PROJECT_REPORT.md
│   └── Research_Paper.md
│
├── dataset/
│   ├── raw/
│   └── processed/
│
├── src/
│
├── notebooks/
│
├── models/
│   └── trained/
│
├── results/
│   ├── graphs/
│   └── reports/
│
├── images/
│   ├── architecture/
│   ├── hardware/
│   └── results/
│
├── README.md
├── LICENSE
├── .gitignore
└── CITATION.cff
```

---

## Performance Metrics

The machine learning models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## Applications

- Electric Vehicles
- Battery Management Systems (BMS)
- Predictive Maintenance
- Battery Health Monitoring
- Smart Mobility
- Automotive Safety
- Intelligent Fault Diagnosis

---
## Results

The developed system demonstrates high accuracy in detecting abnormal battery temperature conditions using machine learning algorithms.

### Performance Summary

| Model | Application |
|--------|-------------|
| Random Forest | Battery temperature fault detection |
| XGBoost | Fault prediction and classification |
| LightGBM | Fast model training and prediction |
| CatBoost | Robust ensemble learning |

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### Output

- Early battery fault detection
- Abnormal temperature identification
- Predictive maintenance support
- Improved battery safety
- Machine learning model comparison

> Detailed graphs, performance reports, and prediction results are available in the `results/` directory.
---

## Future Enhancements

- Deep Learning-based fault prediction
- Real-time IoT integration
- Cloud-based battery monitoring dashboard
- Edge AI deployment
- Battery Remaining Useful Life (RUL) prediction
- Integration with Battery Management Systems (BMS)

---

## License

This project is licensed under the MIT License.

---

## Citation

If you use this project for research or academic purposes, please cite this repository and the associated published patent application.

---

## Acknowledgements

- Vellore Institute of Technology (VIT)
- Office of the Controller General of Patents, Designs & Trade Marks, Government of India
- Open-source Machine Learning Community

---

## Author

**Shashi Kiran A M**

Embedded Systems Engineer | Automotive Electronics Engineer | Machine Learning Enthusiast

GitHub: https://github.com/shashikiranam

---

⭐ If you found this project useful, consider giving it a Star.
