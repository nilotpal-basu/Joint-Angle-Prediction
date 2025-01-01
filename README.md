# README: Joint Angle Prediction using XGBoost and LightGBM Models

## Project Overview
This repository contains the implementation of a **Joint Angle Prediction** model utilizing two gradient boosting algorithms: **XGBoost** and **LightGBM**. The project aims to predict joint angles based on the provided multivariate gait dataset, enabling applications in biomechanical analysis, sports science, and rehabilitation engineering.

---

## Dataset
**Multivariate Gait Data**  
- **Source:** UCI Machine Learning Repository  
- **Dataset Link:** [Multivariate Gait Data](https://archive.ics.uci.edu/dataset/760/multivariate+gait+data)  
- **Description:** The dataset includes multivariate time series data capturing different gait features of individuals, which are crucial for joint angle prediction. It includes input features such as force plate readings, kinematic parameters, and other relevant metrics.

---

## Features of the Project
- **Gradient Boosting Models Used:**
  - **XGBoost:** For efficient, accurate, and scalable tree boosting.
  - **LightGBM:** Optimized for faster training on large datasets.
- **Cross-validation:** Ensured model generalizability and robustness with k-fold cross-validation.

---

## Prerequisites
### Libraries and Tools
- Python 3.8 or above
- Required Python packages (install via `pip install -r requirements.txt`):
  - `xgboost`
  - `lightgbm`
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

---
