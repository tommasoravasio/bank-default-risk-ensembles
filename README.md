# Bank-default-risk-ensembles

## Project Overview
The Project is part of the Machine Learning course at Bocconi University. Its main objective is to build a robust credit scroing model to predict default risks. The task is a binary classification problem, where the target variable is whether a customer will experience a serious delinquency in two years `SeriousDlqin2yrs`

## Methodology
Our approaches includes:
* **EDA**: We explored the dataset to detect missing values, outliers and correlations between variables
* **Feature Engineering**: We created new features such as `CreditUtilizationRatio`, `Young` and `LatePaymentsFrequency` to enhance model's performance
*  **Baseline Model**: Logistic regression was used as the baseline model
*  **Ensemble Methods**: We explored ensemble tehniques like Random Forest, Bagging, Boosting
*  **Handling Class Imbalance**: We enhanced techniques like randum undersampling, random oversampling and SMOTE, along with cost sensitive learning such as class weighting to address class imbalance
*  **Algorithm-Level Solutions**: Advanced solutions such as Balanced Random Forest, Easy Ensemble, and Balanced Bagging were implemented

## Files
* `main.ipynb`: Main script file, contains the complete project code from EDA to final model training and evaluation
* `final_submission.csv`: Final predictions for the test dataset
* `ML_report.pdf`: Full project report detailing the methodology, models and results
* `Data`:
  - `train.csv`: data used to train and test the algorithms
  - `test.csv`: data used to predict the final submission
  
