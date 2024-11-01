# Fraudulent Credit Card Transaction Detection

## About This Project

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to help credit card companies identify fraudulent activities to protect customers from unauthorized charges. The project utilizes anomaly detection methods and includes the implementation of AutoML using PyCaret.

### Context

Credit card companies must recognize fraudulent transactions to prevent customers from being charged for items they did not purchase. This project implements anomaly detection to identify potential fraud within the provided transaction dataset.

### Dataset Overview

The dataset consists of credit card transactions made by European cardholders in September 2013, containing a total of 284,807 transactions, with 492 classified as fraud. The dataset is highly unbalanced, with the positive class (frauds) accounting for only 0.172% of all transactions. 

- **Features:** 
  - **V1, V2, ... V28:** Principal components obtained through PCA (no original features provided due to confidentiality).
  - **Time:** Seconds elapsed between each transaction and the first transaction.
  - **Amount:** The transaction amount, which can be used for cost-sensitive learning.
  - **Class:** Response variable, where 1 indicates fraud and 0 indicates a legitimate transaction.

Given the significant class imbalance, accuracy will be evaluated using the Area Under the Precision-Recall Curve (AUPRC), as confusion matrix accuracy is not meaningful in this context.

### Project Tasks

1. Data Analysis
2. Feature Engineering
3. Model Building and Prediction using Machine Learning Techniques
4. Model Building and Prediction using PyCaret (AutoML)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib/Seaborn (for data visualization)
- Scikit-learn
- PyCaret

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fraud-detection-project.git
