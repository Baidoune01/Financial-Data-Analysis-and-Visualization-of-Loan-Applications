# Financial Data Analysis and Visualization for Bank X's Loan Applications

## Project Overview
This project involves a comprehensive analysis and visualization of Bank X's loan application data. The goal is to extract meaningful insights and visualize relationships within the data to assist Bank X in making informed decisions about their loan approval process.

## Dataset Description
The dataset consists of multiple files:
- `loan_applications_train.csv`: Training data with target variable included.
- `previous_credits.csv`: Data on clients' previous credits from other financial institutions.
- `credit_bureau_balance.csv`: Monthly balances of previous credits in the Credit Bureau.
- `previous_pos_cash_loans.csv`: Monthly balance snapshots of previous POS and cash loans.
- `previous_credit_cards.csv`: Monthly balance snapshots of previous credit cards.
- `previous_loan_applications.csv`: Previous applications for Home Credit loans.
- `repayment_history.csv`: Repayment history for previously disbursed credits.

## Analysis Sections
The analysis is divided into several sections, each corresponding to a part of the dataset:

### 1. Applicant Profile Section
Exploratory data analysis (EDA) on the main loan application data, visualizing applicant demographics, income distribution, and identifying any missing values and outliers.

### 2. Credit History Section
Analysis of the credit history of applicants with other financial institutions, including EDA on credit amounts, statuses, and durations.

### 3. Bank X Loan History Section
Visualization and analysis of the bank's historical loan data, focusing on repayment history, previous loan applications, and loan outcomes.

### 4. Consumer Credit and Loan Products Section
Insights into the consumer credit behavior and loan product usage, including POS cash loans and credit cards, with attention to payment amounts, balance distributions, and identification of any outliers.

## Notebooks
Each section of the analysis is contained in a separate Jupyter notebook:

- `Applicant_Profile_Section.ipynb`
- `Credit_History_Section.ipynb`
- `Bank_X_Loan_History_Section.ipynb`
- `Consumer_Credit_Loan_Products_Section.ipynb`

## Outlier Detection
Outlier detection is performed using z-scores in the relevant sections to identify anomalies in the financial behaviors of applicants.

## Visualizations
Key visualizations include:
- Histograms for distribution of numerical features.
- Pairwise plots for key features to identify relationships.
- Bar plots for average loan amounts and total payments by loan type.
- Distribution plots for future installments and credit card balances.


## Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scipy

## Authors
- Baidoune Abderrahmane
- Fri Yassir
- Choukri Zakaria
- Youss Ayman

