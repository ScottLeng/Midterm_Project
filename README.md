# Midterm_Project
# MLflow Model Logging Project

## Overview
This project trains a machine learning model using a dataset and logs the training runs with MLflow for experiment tracking. The dataset is used to predict whether a credit application is approved.

## Dataset
The dataset contains financial and demographic information such as:
- `Gender`
- `Age`
- `Debt`
- `Married`
- `BankCustomer`
- `Industry`
- `Ethnicity`
- `YearsEmployed`
- `PriorDefault`
- `Employed`
- `CreditScore`
- `DriversLicense`
- `Citizen`
- `ZipCode`
- `Income`
- **Target Variable:** `Approved`

## Setup Instructions

### 1. Install Dependencies
Ensure you have Python installed, then install the required libraries:
```bash
pip install pandas scikit-learn mlflow
```

### 2. Run Model Training
Execute the training script to train the model and log the results in MLflow:
```bash
python train_model.py
```

### 3. Start MLflow UI
To visualize the experiment results, start the MLflow UI:
```bash
mlflow ui
```
This will launch a local server. Open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

## Running Multiple Experiments
Modify the model parameters (e.g., `n_estimators` in RandomForest) and re-run the training script to compare results in MLflow.

## GitHub Submission
1. Initialize a Git repository:
```bash
git init
git add .
git commit -m "Initial commit"
```
2. Create a GitHub repository and push the project:
```bash
git remote add origin https://github.com/your-username/mlflow-project.git
git branch -M main
git push -u origin main
```

## Conclusion
This project demonstrates how to log and track machine learning experiments using MLflow. Modify parameters and analyze different runs for optimal performance.
