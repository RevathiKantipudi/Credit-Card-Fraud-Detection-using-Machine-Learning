
# Credit Card Fraud Detection 

Labeling anonymous credit card transactions as genuine or fraudulent.

In order to prevent customers from being charged for products they did not buy, credit card companies must be able to identify fraudulent credit card transactions.

## Dataset

The dataset includes credit card transactions performed by European cardholders in September 2013.
We have 492 frauds out of 284,807 transactions in our dataset of transactions that took place over the course of two days. The dataset is quite skewed, with frauds making up 0.172% of all transactions in the positive class(frauds).

It only has numeric input variables that have undergone PCA transformation. Unfortunately, we are unable to offer the original characteristics and further context for the data due to confidentiality concerns. The major components derived with PCA are features V1, V2,..., V28. The only features that have not been changed with PCA are "Time" and "Amount." The seconds that passed between each transaction and the dataset's initial transaction are listed in the feature "Time."

The transaction amount is represented by the feature "Amount," which may be utilised for example-dependent, cost-sensitive learning. The response variable, feature "Class," has a value of 1 in cases of fraud and 0 in all other cases.

## Installation

```bash
    pip install pandas
    pip install standard-scaler
    pip install -U scikit-learn
    pip install random-forest-mc
    pip install imbalanced-learn
    pip install joblib
    pip install tk
```
    
## Authors

- BL.EN.U4CSE20065 :K V C Madhav
- BL.EN.U4CSE20068 :K Revathi Annapurna
- BL.EN.U4CSE20094 :M Ajay Sai Kumar
- BL.EN.U4CSE20144 :S S Karthikeya Sharma 
