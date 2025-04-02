# Credit Risk Modelling

This repository shows the use cases for applying credit risk regulatory requirements to credit risk models. I used various datasets that involve credit risk assessment, loan defaults, and financial modeling. 

Here are some datasets that I am exploring and how I plan to apply my knowledge:

### 1. German Credit Data (Credit Risk)

**Dataset:** German Credit Data

**Description:** This dataset contains 1,000 samples of individuals with information about their credit, such as credit history, purpose, and current balance, and whether they defaulted on a loan or not (good/bad credit).

**What I Did in the Project:**

- **[Probability of Default:](https://github.com/MiltonGreat/Probability-of-Default.git)** Built a classification model (e.g., logistic regression, decision trees) to predict whether an individual will default or not based on their features.
- **[Credit Scorecards:](https://github.com/MiltonGreat/Credit-Scorecard-Model.git)** Developed a credit scorecard model using features like "credit history," "purpose," and "savings" to assess the creditworthiness of an individual.
- **[Regulatory Implications:](https://github.com/MiltonGreat/Regulatory-Implications.git)** Implemented an IRB (Internal Ratings-Based) approach for calculating capital requirements for credit risk and simulate capital adequacy using the features in the dataset.
- **[Model Validation and Stress Testing:](https://github.com/MiltonGreat/Model-Validation-and-Stress-Testing.git)** Performed model validation (e.g., K-fold cross-validation, holdout validation) and stress-test the model under different economic scenarios (e.g., higher default rates).

### 2. Home Credit Default Risk

**Dataset:** Home Credit Default Risk

**Description:** This dataset contains data from a financial services company, including information about clients, credit applications, and whether the client defaulted on a loan.

**What I Did in the Project:**

- **Probability of Default:** Built a machine learning model to predict the likelihood of loan default, incorporating features such as income, family size, and credit history.
- **Credit Scorecards:** Created a credit scorecard to categorize borrowers into different risk buckets (e.g., low risk, medium risk, high risk).
- **Loss Given Default:** Built models that estimated LGD based on the applicant’s profile (e.g., loan amount, collateral).
- **Exposure at Default:** Calculated potential exposure at the time of default using historical data to estimate the potential loss to the lender.

### 3. Give Me Some Credit

**Dataset:** Give Me Some Credit

**Description:** This dataset contains information about customers’ credit history and default behavior. It includes information like credit usage, age, and income.

**What I Did in the Project:**

- **Probability of Default:** Used this dataset to build a binary classification model (good/bad credit) based on various features like credit utilization, monthly income, and loan amount.
- **Retail Credit Risk Scorecard:** Designed a credit scorecard model and evaluate the risk level of different customers based on their financial behavior.
- **Feature Engineering:** Created new features, such as lagged values or aggregate metrics, to enhance the model and make it more predictive.
- **Regulatory Reporting:** Applied Basel II/III frameworks to calculate capital adequacy and perform stress testing on the data using various economic conditions.

### 4. Lending Club Loan Data

**Dataset:** Lending Club Loan Data

**Description:** This dataset contains information on loan performance, including loan amount, interest rate, loan term, borrower’s credit history, and whether the loan was repaid or defaulted.

**What I Did in the Project:**
- **Default Prediction:** Used machine learning algorithms like Random Forest, XGBoost, or Neural Networks to predict default based on borrower information (e.g., credit score, loan amount, debt-to-income ratio).
- **Loss Given Default:** Estimated LGD by looking at the loan’s collateral value and borrower’s ability to repay.
- **Exposure at Default:** Calculated potential exposure at the time of default by combining loan amounts and other relevant borrower data.
- **Model Interpretability:** Used SHAP or LIME for model interpretation and explain which features most influence the creditworthiness predictions.

### 5. Credit Card Fraud Detection

**Dataset:** Credit Card Fraud Detection

**Description:** This dataset contains credit card transactions labeled as fraudulent or non-fraudulent. It is suitable for anomaly detection and fraud modeling.

**What I Did in the Project:**
- **Anomaly Detection:** Used anomaly detection techniques to identify outliers or suspicious transactions that may indicate fraud.
- **Fraud Detection Models:** Built models like Isolation Forest or Autoencoders to detect unusual transactions, simulating market anomalies and risk management processes.
- **Modeling in Risk Context:** While this dataset focuses on fraud, I use it to simulate the detection of unusual behavior that could represent credit risk and use it for credit scoring in certain scenarios.

### 6. Fannie Mae Single Family Loan Performance Data

**Dataset:** Fannie Mae Loan Data

**Description:** This dataset contains detailed loan performance information, including features like loan-to-value ratio, borrower’s credit score, and delinquency status.

**What I Did in the Project:**
- **Risk-Based Pricing Models:** Built models that calculate risk-based pricing for loans, where the interest rate is determined based on the credit risk of the borrower.
- **Delinquency Prediction:** Developed models that predict whether a borrower will default or become delinquent, helping improve the loan performance model.
- **Loan Valuation:** Implemented models for assessing the value of loan portfolios based on borrower behavior, credit risk, and macroeconomic factors.
