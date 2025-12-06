<p align="center"> <img src="https://img.shields.io/badge/FinChurn-Bank%20Customer%20Churn%20Prediction-blueviolet?style=for-the-badge&logo=python&logoColor=white" /> </p> <h1 align="center">⭐🏦 FinChurn – Intelligent Bank Customer Churn Prediction System</h1> <p align="center"> <b>An end-to-end ML system to predict which customers are likely to leave the bank using clean preprocessing, feature engineering, and multiple machine-learning algorithms.</b> </p> <p align="center"> <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python" /> <img src="https://img.shields.io/badge/ML-Scikit--Learn-yellow?style=for-the-badge" /> <img src="https://img.shields.io/badge/Analytics-EDA-green?style=for-the-badge" /> <img src="https://img.shields.io/badge/Models-Logistic%20%7C%20RF%20%7C%20GBoost-red?style=for-the-badge" /> <img src="https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=for-the-badge" /> </p>

# 📘 Project Overview
FinChurn is an advanced machine-learning project designed to predict bank customer churn using structured customer demographics, account activity, and behavioral patterns.
This end-to-end system includes data preprocessing, EDA, feature engineering, ML modeling, and model evaluation to identify customers most likely to leave the bank.

# 🧠 Algorithms Used
This project compares multiple machine-learning models:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

<h2>📁 Project Structure
<pre>
FinChurn/
│── FinChurn – Intelligent Bank Customer Churn Prediction.ipynb   # Main Jupyter Notebook
│── Churn_Modelling.xlsx                                          # Dataset
│── churn_model.pkl                                               # Trained ML Model
│── scaler.pkl                                                    # Standard Scaler
│── requirements.txt                                              # Dependencies
│── README.md           
</pre>

# 📁 Dataset
Dataset: Bank Customer Churn Modelling Dataset
- 10,000+ customer records
- Includes geography, gender, credit score, age, tenure, account balance, products used, and customer activity

Target Variable:
- Exited → 1 = customer left the bank, 0 = customer retained

# 🧹 Data Preprocessing Steps
- Handle missing values (if any)
- Convert categorical values using One-Hot Encoding
- Standardize numerical features
- Split dataset into training/testing sets
- Address class imbalance (if needed)

# 📊 Exploratory Data Analysis
- Churn vs Non-Churn distribution
- Impact of Age, Balance, Estimated Salary
- Geography-wise churn analysis
- Correlation heatmap
- Customer behavior insights

# 🤖 Model Evaluation Metrics
- Accuracy Score
- Precision, Recall, F1-score
- Confusion Matrix
- ROC–AUC Curve (optional)

# 📦 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

# 📈 Future Improvements
- Add XGBoost & LightGBM
- Hyperparameter tuning (RandomizedSearchCV / Optuna)
- Deployment using Flask / FastAPI
- Build an interactive dashboard

# 🛡️ License
- This project is licensed under the MIT License.
