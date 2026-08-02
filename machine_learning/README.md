
# 🤖 Machine Learning Module

## AI-Based Soldier Health Fitness Monitoring and Prediction System

This module contains the complete Machine Learning pipeline used to predict a soldier's physical fitness class based on health and fitness parameters.

---

# 🎯 Objective

To develop an AI-powered fitness prediction model that classifies soldiers into fitness categories (A, B, C, D) using machine learning techniques.

---

# 📂 Files

| File | Description |
|------|-------------|
| dataset.ipynb | Complete Jupyter Notebook containing preprocessing, EDA, model training and evaluation |
| soldier_fitness_xgboost.pkl | Final trained XGBoost model |
| preprocessor.pkl | Saved preprocessing pipeline |
| class_encoder.pkl | Label Encoder for target classes |

---

# 📊 Dataset

The model is trained using the **Body Performance Dataset**.

Features used:

- Age
- Gender
- Height
- Weight
- Body Fat Percentage
- Systolic Blood Pressure
- Diastolic Blood Pressure
- Grip Force
- Sit and Bend Forward
- Sit Ups Count
- Broad Jump
- Blood Pressure Category

Target Variable

- Fitness Class (A, B, C, D)

---

# 🛠 Machine Learning Workflow

- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Label Encoding
- Feature Scaling
- Train-Test Split
- Model Training
- Hyperparameter Tuning
- Model Evaluation
- Model Serialization

---

# 🤖 Models Evaluated

- Decision Tree
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- XGBoost (Best Model)

---

# 🏆 Best Model

Model

XGBoost Classifier

Accuracy

75.52%

The XGBoost model achieved the highest accuracy and was selected as the final prediction model.

---

# 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Feature Importance

---

# 📦 Saved Models

The following files are used during deployment.

- soldier_fitness_xgboost.pkl
- preprocessor.pkl
- class_encoder.pkl

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

---

# 🚀 Future Improvements

- Real-Time Soldier Health Monitoring
- Streamlit Web Application
- Fitness Recommendation System
- Live Wearable Device Integration
- AI-Based Readiness Prediction

---

# 👨‍💻 Author

**Nishreyash Tripathi**

B.Tech CSE (AI & ML)

Machine Learning Module

AI-Based Soldier Health Fitness Monitoring and Prediction System
