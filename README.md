🏦 FinChurn – Intelligent Bank Customer Churn Prediction System
<p align="center"> <img src="https://img.shields.io/badge/FinChurn-Bank%20Customer%20Churn%20Prediction-blueviolet?style=for-the-badge&logo=python&logoColor=white" /> </p>

A complete end-to-end Machine Learning project that predicts which bank customers are likely to churn, enabling banks to make data-driven retention decisions.
This project includes clean preprocessing, feature engineering, model training, evaluation, and comparison across multiple ML algorithms.

# 🚀 Project Highlights
✔ Predict bank customer churn with high accuracy
✔ Clean & structured EDA + preprocessing
✔ Feature engineering & encoding
✔ Trained 3 ML algorithms
✔ Confusion matrix + classification report
✔ Model comparison table
✔ Fully reproducible code

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
