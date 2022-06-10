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
    + <img width="990" alt="Screen Shot 2022-06-01 at 11 11 22 AM" src="https://user-images.githubusercontent.com/98932859/173038622-b0a61386-deaa-4e1a-852d-5f856765109a.png">
### ⌨️ Models
### 📍 Takeaway
