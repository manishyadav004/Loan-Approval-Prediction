# Loan-Approval-Prediction
💰 Loan Approval Prediction using Machine Learning
📖 Overview

This project predicts the likelihood of loan approval using various machine learning algorithms.
Financial institutions face challenges in evaluating loan applications, and this project demonstrates how ML can automate and improve decision-making based on applicant details.

The model is trained on the Loan Prediction Dataset (commonly used in Kaggle competitions).

📂 Dataset

Source: Loan Prediction Dataset (Kaggle/UCI or other open repositories)

Features:

ApplicantIncome

CoapplicantIncome

LoanAmount

Loan_Amount_Term

Credit_History

Gender

Married

Dependents

Education

Self_Employed

Property_Area

Target Variable:

Loan_Status → 0 = Rejected, 1 = Approved

⚙️ Methodology

Data Preprocessing

Handling missing values

Encoding categorical variables

Normalization & scaling

Exploratory Data Analysis (EDA)

Distribution of income, loan amounts, credit history

Correlation analysis

Model Training

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

AdaBoost

Model Evaluation

Accuracy Score

Confusion Matrix

Classification Report

📊 Results
Model	Accuracy
Logistic Regression	~81%
Decision Tree	~78%
Random Forest	~84%
K-Nearest Neighbors	~79%
AdaBoost	~80%

✅ Best Model: Random Forest (~84% accuracy)

📌 Insights

Credit History is the most critical factor influencing loan approval.

ApplicantIncome and LoanAmount have an effect but are secondary to credit history.

Random Forest performed best, handling categorical + numerical features efficiently.

Feature scaling significantly improved KNN and Logistic Regression performance.

🛠️ Tech Stack

Python 🐍

Pandas, NumPy → Data preprocessing

Matplotlib, Seaborn → Data visualization

Scikit-learn → ML algorithms

Jupyter Notebook → Development environment

🚀 Installation
# Clone repository
git clone https://github.com/your-username/loan-approval-prediction.git
cd loan-approval-prediction

# Install dependencies
pip install -r requirements.txt

▶️ Usage
# Run Jupyter Notebook
jupyter notebook "Loan Approval Prediction.ipynb"

🔮 Future Work

Implement Deep Learning models (ANNs) for better accuracy

Deploy the model as a web app (Flask/Streamlit)

Integrate with real-time banking datasets

Use Explainable AI (XAI) to improve transparency in predictions

📜 License

This project is licensed under the MIT License – feel free to use and modify.
