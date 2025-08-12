# churn - Price - Prediction

📌 Project Overview
Customer churn is a critical problem for businesses, especially in competitive industries like telecom, banking, and subscription-based services. This project aims to predict whether a customer is likely to churn using machine learning models based on historical customer data.

The goal is to help businesses take proactive retention measures by identifying at-risk customers before they leave.

🎯 Objectives
Analyze customer data to uncover patterns related to churn.

Build a machine learning model to predict churn with high accuracy.

Develop a simple web interface for real-time churn predictions.

🔍 Key Features
Data Preprocessing:

Handled missing values, categorical encoding, and feature scaling.

Model Development:

Tested multiple algorithms (Logistic Regression, Random Forest, etc.).

Selected the best-performing model based on evaluation metrics.

Evaluation Metrics:

Accuracy, Precision, Recall, F1-score, and ROC-AUC.

Deployment:

Flask-based web app (app.py) for predicting churn from new customer inputs.

User Interface:

Simple HTML front-end (index.html) for user-friendly interaction.

📂 Repository Structure
├── churn_project.ipynb      # Data analysis & model building  
├── app.py                   # Flask app for deployment  
├── index.html               # Web interface for predictions  
├── encoder.pkl              # Encoded categorical features  
├── scaler.pkl               # Scaler for feature normalization  
└── README.md                # Project documentation  
🚀 Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Framework: Flask

Tools: Jupyter Notebook

📈 Results & Insights
Identified key factors influencing churn such as contract type, monthly charges, and tenure.

Achieved XX% accuracy with YY% recall, making it effective at catching potential churn cases.

Business can use this model to implement targeted retention campaigns.

🖥️ How to Run the Project
Clone the repository
git clone https://github.com/vinayakjain01/churn-Prediction.git
Install dependencies

pip install -r requirements.txt
Run the Flask app

python app.py
Open http://127.0.0.1:5000/ in your browser to access the web interface.

📬 Contact
Author: Vinayak Jain
GitHub: vinayakjain01
