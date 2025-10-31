This repository contains **two machine learning projects integrated with MLflow Tracking**.  
MLflow is used to track model experiments, parameters, metrics, artifacts, and runs.

---

## 📂 Projects Included

| Project Name | Model Type | Description | MLflow Tracking |
|-------------|------------|-------------|----------------|
| **1. Iris Classification Model** | Classification | Predicts the species of Iris flowers based on sepal & petal measurements. | ✅ MLflow enabled |
| **2. House Price Prediction** | Regression | Predicts house prices based on various numerical attributes. | ✅ MLflow enabled |

---

## 🧠 Project 1: Iris Classification Model

### 📌 Overview
This project builds a **classification model** to predict the species of Iris flowers using machine learning (e.g., Logistic Regression, Decision Tree, Random Forest).

### 🎯 Steps Performed
- Data loading from sklearn dataset
- Exploratory Data Analysis (EDA)
- Model Training & Evaluation
- MLflow Experiment Tracking (parameters, metrics, model artifacts)

### 🔗 MLflow Tracking Links
| Type | Link |
|------|------|
| 🏃 **Run Details** | http://127.0.0.1:5000/#/experiments/287353155992825511/runs/023cee2d8bb146a0b9feab0d817898e7 |
| 🧪 **Experiment Dashboard** | http://127.0.0.1:5000/#/experiments/287353155992825511 |

---

## 🏡 Project 2: House Price Prediction Model

### 📌 Overview
This project implements a **regression model** to predict the selling price of houses using features such as number of rooms, area, age, location, etc.

### 🎯 Steps Performed
- Dataset preprocessing & normalization
- Model training and hyperparameter tuning
- Evaluation using RMSE / MAE / R²
- MLflow tracking & storing model artifacts

### 🔗 MLflow Tracking Links
| Type | Link |
|------|------|
| 🏃 **Run Details** | http://127.0.0.1:5000/#/experiments/0/runs/28f3d9dcd4ae40fe85f03d646e31db87 |
| 🧪 **Experiment Dashboard** | http://127.0.0.1:5000/#/experiments/0 |

---

## 🚀 How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/ShivamMitra/ML-Project-Integration-With-MLFLOW-Tracking.git
   cd ML-Project-Integration-With-MLFLOW-Tracking
2. Create and activate virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate       # Windows: venv\Scripts\activate

4. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Start MLflow UI:
   ```bash
   mlflow ui
6. Run the project scripts (example):
   ```bash
   python iris_model.ipynb
   python house_price_model.ipynb
## 📦 Dependencies
```
Package	Purpose
mlflow	Experiment tracking
scikit-learn	Machine learning models
pandas	Data handling
numpy	Numerical computations
matplotlib / seaborn	Visualizations
```
(Install automatically via requirements.txt)

## 🤝 Contributing
Contributions are welcomed! You may:
- Add new models / improve tuning
- Experiment with additional datasets
- Extend MLflow integration to Azure / AWS / DagsHub storage

## 📜 License
This project is licensed under the MIT License.
