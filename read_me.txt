📊 Loan Approval Prediction System
📌 Project Overview

This project aims to build a machine learning model that predicts whether a loan application will be approved or not based on applicant details such as income, credit score, assets, and employment status.

The system uses data preprocessing, exploratory data analysis (EDA), and a Random Forest classifier to make predictions.

🚀 Features
Data cleaning and preprocessing
Exploratory Data Analysis (EDA) with visualizations
Handling categorical variables using Label Encoding
Feature scaling using StandardScaler
Model training using Random Forest Classifier
Model evaluation using accuracy metrics
Feature importance analysis
🗂️ Dataset
Dataset used: loan_approval_dataset.csv
Contains applicant information such as:
Income
Loan amount
Loan term
CIBIL score
Assets (residential, luxury, bank)
Employment status
Education
Loan status (Target variable)
🧪 Workflow
1. Data Collection
Loaded dataset using pandas
Initial inspection using .head(), .info(), .describe()
2. Data Cleaning
Removed unnecessary columns (e.g., loan_id)
Checked for null values and duplicates
3. Data Preprocessing
Converted categorical variables using Label Encoding
education
self_employed
loan_status
4. Exploratory Data Analysis (EDA)
Distribution plots for key features
Count plots for categorical variables
Correlation heatmap
Outlier detection using IQR method
5. Feature Engineering
Log transformation applied to skewed data (residential_assets_value)
Feature scaling using StandardScaler
6. Model Building
Train-test split using train_test_split
Model used: Random Forest Classifier
7. Model Evaluation
Accuracy measured on:
Training set
Test set
8. Feature Importance
Identified most influential features affecting loan approval
🛠️ Technologies Used
Python 🐍
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
📈 Results
The model achieves good accuracy on both training and test datasets.
Important features influencing loan approval include:
CIBIL score
Income
Asset values
Loan amount
▶️ How to Run
Clone the repository:
git clone https://github.com/your-username/loan-approval-prediction.git
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook Loan_approval-sys.ipynb
📌 Future Improvements
Hyperparameter tuning
Trying other models (XGBoost, Logistic Regression)
Deploying the model using Flask/Streamlit
Adding a user interface
🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull requests