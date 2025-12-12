# Telco_Churn_Project

Telco Customer Churn Prediction

Binary Classification Using Decision Tree & Neural Network Models

This project implements a complete machine learning pipeline to predict customer churn using the publicly available Telco Customer Churn dataset.
It includes EDA, preprocessing, model development, hyperparameter tuning, evaluation, ethical considerations, and deployment strategy as required in the project brief.

1. Project Overview

This project aims to build models that predict whether a telecom customer will churn (leave the service).
Two machine learning models were developed:

•	Decision Tree Classifier
•	Neural Network (Keras / TensorFlow)

Both models were evaluated and compared using appropriate metrics and visualizations.

2. Dataset

Dataset: Telco Customer Churn
Source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn?resource=download

The dataset includes:

•	Customer demographics

•	Account information

•	Services subscribed

•	Charges & payment details

•	Churn label (Yes/No)

3. Key Components
   
Exploratory Data Analysis (EDA)

•	Visualizations of churn distribution

•	Boxplots of key numerical variables

•	Missing value analysis

•	Data type corrections

Preprocessing

•	Handling missing values

•	One-hot encoding of categorical features

•	Scaling numerical variables

•	Train-test split with stratification

Model Development

•	Decision Tree
	  - Baseline model
    - GridSearchCV hyperparameter tuning
	
•	Neural Network
    - Sequential model
    - Dense + Dropout layers
    - Adam optimizer
    - 50 epochs training
    
Evaluation

•	Accuracy
•	Classification report
•	Confusion matrix
•	Learning curves
•	Performance comparison table

Ethical & Deployment Considerations

Included in the final report:

•	Bias mitigation

•	Fairness evaluation

•	Transparency

•	Privacy concerns

•	Monitoring model drift

•	Post-deployment updates

4. Results Summary

Decision tree accuracy: 0.753
Neural network accuracy: 0.713

5. How to Run

1. Install dependencies

pip install -r requirements.txt

2. Run the notebook file

Telco_Churn_Project.ipynb

6. Report
   
The report includes:

•	Methodology

•	EDA insights

•	Preprocessing

•	Results

•	Model comparison

•	Ethical considerations

•	Post-deployment strategy

•	Appendix containing ALL source code

7. GitHub Repository Link

https://github.com/GangaminiH/Telco_Churn_Project.git

Acknowledgements

Dataset is originally obtained from the IBM Telco Customer Churn dataset published on Kaggle.
