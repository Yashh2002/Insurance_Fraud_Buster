🛡️ Insurance Fraud Detection System

A Machine Learning powered web application that detects fraudulent insurance claims using Logistic Regression.
The system enables users to submit claim details via a Django web interface and instantly receive fraud risk predictions along with visual insights.

This project demonstrates end-to-end implementation of ML + Web Development + Database integration, making it highly relevant for Python Developer / Data Analyst / ML roles.

🚀 Project Highlights
Developed an ML-based fraud detection model using Logistic Regression.
Built a Django web application for real-time insurance claim submission.
Integrated MySQL database to store claim records and prediction results.
Performed Exploratory Data Analysis (EDA) to identify fraud patterns.
Evaluated model performance using Accuracy, Precision, Recall, F1-score, ROC-AUC.
Created data visualizations using Matplotlib & Seaborn for better interpretability.
Achieved approximately 75% model accuracy.
🧠 Problem Statement

Insurance fraud leads to billions of dollars in losses every year.
Manual claim verification is time-consuming and inefficient.

This project aims to:

Automate fraud detection
Improve decision-making using ML predictions
Provide interpretable insights through visualizations
Reduce fraudulent claims and financial losses
🛠️ Tech Stack
Category	Technology
Programming Language	Python
Backend Framework	Django
Machine Learning	Scikit-learn
Data Analysis	Pandas, NumPy
Data Visualization	Matplotlib, Seaborn
Database	MySQL
ML Algorithm	Logistic Regression
Tools	Jupyter Notebook, Git, GitHub
⚙️ System Architecture
User Input (Claim Form)
        ↓
Django Web Application
        ↓
Preprocessing Pipeline (Pandas)
        ↓
Trained ML Model (Logistic Regression)
        ↓
Fraud Prediction Result
        ↓
MySQL Database Storage
        ↓
Visualization Dashboard
📊 Features
1. Claim Submission Interface
User-friendly Django form
Validates claim input data
Stores claim details in MySQL
2. Fraud Prediction Model
Logistic Regression classifier
Predicts probability of fraud
Real-time prediction output
3. Exploratory Data Analysis (EDA)
Fraud vs Legitimate claim distribution
Feature correlation analysis
Data preprocessing and cleaning
4. Data Visualization Dashboard
Count plots
Correlation heatmaps
ROC Curve
Fraud probability charts
5. Model Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
📈 Model Performance
Metric	Score
Accuracy	~75%
Precision	Good
Recall	Balanced
F1-score	Optimized
ROC-AUC	Strong separation capability
📂 Project Structure
insurance-fraud-detection/
│
├── fraud_detection_app/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│
├── ml_model/
│   ├── train_model.ipynb
│   ├── preprocessing.py
│   ├── model.pkl
│
├── templates/
│   ├── claim_form.html
│   ├── result.html
│
├── static/
│   ├── css/
│   ├── images/
│
├── database/
│   ├── schema.sql
│
├── requirements.txt
├── manage.py
└── README.md
🔄 Workflow
User submits insurance claim details
Data is validated and preprocessed
ML model predicts fraud probability
Prediction result displayed on UI
Claim & result stored in MySQL database
Visual insights generated for analysis
