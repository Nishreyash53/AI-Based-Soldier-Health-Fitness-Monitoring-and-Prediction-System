# 🤖 Machine Learning Module

# AI-Based Soldier Health Fitness Monitoring and Prediction System

This module contains the complete Machine Learning pipeline used to predict a soldier's physical fitness category (A, B, C, D) using health and fitness parameters.

---

# 🎯 Objective

To develop an AI-powered prediction system that classifies soldiers into different fitness grades based on their physical and health-related attributes using Machine Learning.

---

# 📂 Project Files

| File | Description |
|------|-------------|
| dataset.ipynb | Complete ML notebook (EDA, preprocessing, feature engineering, training & evaluation) |
| soldier_fitness_xgboost_final.pkl | Final trained XGBoost model |
| preprocessor_final.pkl | Data preprocessing pipeline |
| class_encoder_final.pkl | Label encoder for target classes |
| gender_encoder_final.pkl | Gender label encoder |
| confusion_matrix.png | Confusion Matrix |
| feature_importance.png | XGBoost Feature Importance |
| roc_curve.png | Multi-Class ROC Curve |
| model_performance.csv | Accuracy, Precision, Recall & F1 Score |
| final_model_comparison.csv | Comparison of all trained models |

---

# 📊 Dataset

**Dataset Used:** Body Performance Dataset

### Features

- Age
- Gender
- Height (cm)
- Weight (kg)
- Body Fat (%)
- Systolic Blood Pressure
- Diastolic Blood Pressure
- Grip Force
- Sit and Bend Forward
- Sit-ups Count
- Broad Jump

### Engineered Features

- BMI
- Pulse Pressure
- Strength Index
- Jump Power
- Core Strength
- Flexibility Index

---

# 🎯 Target

Fitness Class

- A
- B
- C
- D

---

# 🛠 Machine Learning Workflow

- Data Cleaning
- Missing Value Checking
- Duplicate Removal
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Correlation Analysis
- Feature Importance
- SHAP Explainability
- Label Encoding
- Data Scaling
- Train-Test Split
- Model Training
- Hyperparameter Tuning
- Model Evaluation
- Model Saving

---

# 🤖 Models Evaluated

- Logistic Regression
- Random Forest
- LightGBM
- CatBoost
- Stacking Ensemble
- XGBoost (Baseline)
- Tuned XGBoost
- Feature Engineered XGBoost ✅

---

# 🏆 Final Model

**Feature Engineered XGBoost**

### Performance

| Metric | Score |
|---------|-------|
| Accuracy | **76.56%** |
| Precision | **76.64%** |
| Recall | **76.26%** |
| F1 Score | **76.18%** |

---

# 📈 Model Evaluation

The project includes

- Confusion Matrix
- Multi-Class ROC Curve
- SHAP Feature Importance
- XGBoost Feature Importance
- Classification Report
- Model Comparison

---

# 🔥 Top Important Features

- Grip Force
- Jump Power
- Core Strength
- Flexibility Index
- Sit and Bend Forward
- Pulse Pressure
- Broad Jump
- Strength Index

---

# 💾 Saved Models

- soldier_fitness_xgboost_final.pkl
- preprocessor_final.pkl
- class_encoder_final.pkl
- gender_encoder_final.pkl

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

---

# 🚀 Future Scope

- Real-Time Soldier Health Monitoring
- Flask Web Application
- Streamlit Dashboard
- AI-Based Fitness Recommendation
- Wearable Device Integration
- Soldier Readiness Prediction
- Live Health Analytics

---

# 👨‍💻 Author

**Nishreyash Tripathi**

B.Tech CSE (AI & ML)

GLA University

---

# ⭐ Project Status

**Completed**

Final XGBoost Model Successfully Developed and Uploaded.
