# loan-approval-ml-pipeline
## Overview 
This project builds a machine learning pipeline to predict loan approval outcomes using financial and demographic information. 
The system analyzes applicant financial information and predicts whether a loan application will be approved or rejected.
The pipeline cleans the data, trains a model, predicts approval probability, and generates lending decision recommendations.

## Business Objective 
Predict whether a loan application will be approved or rejected.
Estimate approval probability for each loan application.
Segment applications into approval likelihood categories.
Generate automated lending decision recommendations.
Prepare data outputs for analytical dashboards.

## Dataset 
The dataset contains historical loan application records.
Each record contains borrower financial details and loan attributes.
Target variable: Loan_Status
Loan_Status= Y →  Approved
Loan_Status= N → Rejected 

## Key Features
Gender
Married
Dependents
Education
Self_Employed
ApplicantIncome
CoapplicantIncome
LoanAmount
Loan_Amount_Term
Credit_History
Property_Area

## Workflow
Loan Application Data
Data Cleaning
Missing Value Handling
Categorical Encoding
MAchine Learning Pipeline
Loan Approval Prediction
Approval Probability Scoring 
Approval Band Segmentation
Decision Recommendation System 
SQL Reporting Layer
Dashboard-ready Dataset 

## Technologies used
Python
NumPy
Pandas
Scikit-learn
Matplotlib
SQLite
MAchine Learning
Data Analytics

## Model Output
Predicted Loan Approval Outcome
Approval probability score
Approval Score (Probability * 100)
Approval likelihood band
Decision recommendation 

## Approval Bands
Highly Likely Approved
Moderately Likely Approved
Low Approval Chance

## Decision Logic 
Approve 
Manual Review
Reject

## SQL Tables
processed_loan_data
loan_approval_results
loan_aproval_summary

## Project Outputs 
loan_approval_predictions.csv
loan_approval_summary.csv
loan_approval_dashboard_data.csv
loan_approval_pipeline.db 



