# ❤️ Heart Disease Classification System

A machine learning-based system developed using Python to predict whether a patient has heart disease based on clinical data. This project explores multiple classification models, performs rigorous data preprocessing, and evaluates the effectiveness of each approach using industry-standard metrics.

---

## 📚 Project Overview

- **Module**: Further Artificial Intelligence (FAI)
- **Institution**: Asia Pacific University of Technology & Innovation (APU)
- **Project Title**: Heart Disease Classification

---

## 🧠 Objective

To build a predictive model using supervised machine learning techniques that classifies whether a patient has heart disease based on 12 key clinical attributes. The model aims to support early detection and aid medical professionals in decision-making.

---

## 📊 Dataset Information

- Source: [Kaggle - Heart Disease Dataset by fedesoriano](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- Rows: 918
- Columns: 12 features + 1 target
- Target: `HeartDisease` (1 = disease, 0 = healthy)

### Key Features Used:
| Feature | Description |
|--------|-------------|
| Age | Patient's age |
| Sex | Male (M), Female (F) |
| ChestPainType | ASY, ATA, NAP, TA |
| RestingBP | Resting blood pressure |
| Cholesterol | Serum cholesterol level |
| FastingBS | Fasting blood sugar (0/1) |
| RestingECG | ECG results |
| MaxHR | Max heart rate achieved |
| ExerciseAngina | Angina induced by exercise (Y/N) |
| Oldpeak | ST depression |
| ST_Slope | Up, Flat, Down |
| HeartDisease | Output class (1 = disease, 0 = healthy) |

---

## 🛠️ Tools & Libraries

- Python (Jupyter Lab)
- Pandas, NumPy – Data processing
- Seaborn, Matplotlib – Data visualization
- Scikit-learn – ML models, evaluation, preprocessing

---

## 📈 Exploratory Data Analysis (EDA)

- Data inspection, cleaning & null check
- Outlier detection using boxplots
- Distribution analysis (e.g. age, cholesterol, chest pain type)
- Correlation heatmaps to identify key predictors
- Label encoding and one-hot encoding for categorical features

---

## 🧪 Models Implemented

### 1. Random Forest Classifier (RF)
- Uses bootstrapping & feature sampling
- Handles multicollinearity and high-dimensional data
- Best performance across most metrics

### 2. Support Vector Machine (SVM)
- Suitable for high-dimensional data
- Uses kernel trick to handle non-linear separation

### 3. Logistic Regression (LR)
- Interpretable baseline model
- Best for binary classification

---

## 🧪 Evaluation Metrics

| Model | Accuracy | F1 Score | Precision |
|-------|----------|----------|-----------|
| Random Forest | ✅ High | ✅ Best | ✅ Best |
| Logistic Regression | ✅ High | ✅ Good | Good |
| SVM | Lower | Lower | Moderate |

### Confusion Matrix:
- Visual comparison of True Positives, False Positives, etc.
- Logistic Regression & Random Forest performed better than SVM.

---

## 🌟 Feature Importance (Random Forest)

1. ST_Slope (Up)
2. Oldpeak
3. ChestPainType (Flat)
4. MaxHR
5. ExerciseAngina
6. Cholesterol
7. Age

---

## 📉 Visualization Examples

- 📊 Histograms: Age, Cholesterol, MaxHR
- 📈 Boxplots: Oldpeak & MaxHR by class
- 🔥 Heatmaps: Correlation between features
- 📉 Clustered bar charts: Predicted vs True values
- 📌 Feature Importance Bar Chart

(⚠️ Add your screenshots in `screenshots/` and use `![Alt Text](screenshots/image-name.png)` in markdown)

---

## 🧪 Final Results Summary

- **Random Forest** outperformed all models in accuracy and F1-score.
- **SVM** struggled with predictions compared to RF and LR.
- Balanced dataset with strong correlation between features and labels (cp, maxHR, oldpeak).

---

## 🧠 Learnings & Contributions

- Understood clinical indicators of heart disease.
- Applied advanced data preprocessing techniques (outlier removal, encoding).
- Compared multiple ML algorithms using cross-validation.
- Gained experience in data visualization, feature selection, and hyperparameter tuning.

---

## 🔮 Future Work

- Incorporate more patient features like lifestyle and demographics
- Experiment with deep learning models (e.g. neural networks)
- Deploy the model as a web application for clinical usage

---


