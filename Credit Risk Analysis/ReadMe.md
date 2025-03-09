# Credit Risk Analysis for Personal Loans and Mortgages

**Goal:** To create models that can estimate the probability of default (PD) for personal loans and mortgages, helping the bank allocate capital and manage risk.

**Objectives:**
- Predicting Probability of Default for Personal Loans:
    - Build a predictive model to estimate the probability that a borrower will default on a personal loan.
    - Estimate the expected loss for loans that are predicted to default in the next year.
- Mapping FICO Scores for Mortgage Default Prediction:
    - Map FICO scores to categorical buckets for use in a machine learning model predicting the probability of mortgage default.
    - Develop a quantization technique that optimizes the boundaries for these buckets, making the data more suitable for model training.

**Implementation:**

Task1: 
- Data Collection: Customer data on income, loan amounts, and default history was provided.
- Modeling: Various machine learning algorithms, such as logistic regression and decision trees, were applied to predict loan defaults.
- Evaluation: The model was evaluated using metrics like accuracy, precision, recall, and the ROC curve.
- Expected Loss: Using the predicted probability of default and a recovery rate of 10%, the expected loss was calculated for each loan.

Task2:
- FICO Score Mapping: FICO scores were divided into buckets, where lower buckets correspond to better credit scores.
- Quantization: Several quantization techniques were applied to optimize the boundaries of the FICO score buckets, such as minimizing mean squared error or maximizing log-likelihood.
- Evaluation: The model was trained using the mapped FICO scores to predict the likelihood of mortgage defaults.

**Insights & Results:**
- Risk Prediction: The model accurately predicts the likelihood of default, enabling better management of loan portfolios.
- Expected Loss: By predicting defaults, the model helps in estimating the expected loss and allows the bank to reserve sufficient capital.
- FICO Score Buckets: Optimized buckets provide a generalized approach to predicting mortgage defaults based on customer creditworthiness.
- Predictive Power: The mapped FICO scores improve the accuracy of the predictive model for mortgage defaults.

