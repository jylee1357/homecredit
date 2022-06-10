# Home Credit Default Risk
### 🙋‍♂️ Goals
- To predict each client's ability in repayment and also to ensure that loans are given with proper principals.
- Predicting client's ability in repayment using LGBM classifier and also perform hyperparameter tuning using Bayesian Optimization.
### 𝌞 Data Preprocessing
* Datasets
  - application_train.csv
  - application_test.csv
  - bureau.csv
  - bureau_balance.csv
  - credit_card_balance.csv
  - installments_payments.csv
  - POS_CASH_balance.csv
  - previous_application.csv
   
* Preprocessing
  - application_train.csv
    + Use Pandas factorize() on object columns
    + In "DAYS_EMPLOYED" column, there are outliers (EMPLOYED DAYS > 1,000); therefore, I decided to remove it.
  - Previous_application_train.csv
    + Merged with application_train.csv
    + Used aggregation to apply all the preprocessing functions on each 'SK_ID_CURR' and saved the result as a new dataframe
    + 
### ⌨️ Models
### 📍 Takeaway
