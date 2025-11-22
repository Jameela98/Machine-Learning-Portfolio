## Random Forest Project: Lending Club Loan Prediction Project
## Project Overview
This project focuses on building machine learning models to predict whether borrowers will fully pay back their loans using data from LendingClub. The analysis explores various borrower characteristics and uses decision trees and random forests to classify loan repayment outcomes.

## Dataset Information
The dataset contains lending data from LendingClub for the period 2007-2010, with the following key features:

- credit.policy: 1 if customer meets credit underwriting criteria, 0 otherwise
- purpose: Loan purpose category (credit_card, debt_consolidation, educational, major_purchase, small_business, all_other)
- int.rate: Loan interest rate (proportion)
- installment: Monthly installment amount
- log.annual.inc: Natural log of self-reported annual income
- dti: Debt-to-income ratio
- fico: FICO credit score
- days.with.cr.line: Number of days with credit line
- revol.bal: Revolving balance
- revol.util: Revolving line utilization rate
- inq.last.6mths: Number of creditor inquiries in last 6 months
- delinq.2yrs: Number of 30+ days past due payments in past 2 years
- pub.rec: Number of derogatory public records
- not.fully.paid: Target variable (1 if not fully paid, 0 if fully paid)

## Project Structure
The analysis follows these main steps:
1) Data Loading and Exploration
 - Import and examine the dataset
 - Understand feature distributions and basic statistics

2) Exploratory Data Analysis
 - FICO score distributions by credit policy and repayment status
 - Loan purpose analysis
 - Interest rate vs. FICO score relationships

3) Model Building
 - Decision Trees classification
 - Random Forest implementation
 - Model evaluation and comparison

## Key Findings
- FICO scores show distinct patterns between borrowers who meet credit criteria vs. those who don't
- Different loan purposes have varying rates of non-payment
- Interest rates show correlation with borrower risk profiles
- Random Forest models demonstrate strong predictive performance

 ## Tools Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook
  
## Model Performance
The project compares the performance of Decision Trees and Random Forest classifiers, with a focus on:
- Accuracy metrics
- Feature importance analysis
- Model interpretability
- Overfitting prevention 

## Future Improvements
- Hyperparameter tuning for optimal performance
- Additional feature engineering
- Exploration of other classification algorithms
- Cross-validation implementation
- Handling class imbalance if present

## Files in This Repository
- 02-Decision Trees and Random Forest Project.ipynb - Main Jupyter notebook containing complete analysis
- README.md - Project documentation
- loan_data - Dataset
