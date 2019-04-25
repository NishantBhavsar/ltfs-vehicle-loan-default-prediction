# LTFS Data Science FinHack
### Vehicle loan default prediction

[competition link](https://datahack.analyticsvidhya.com/contest/ltfs-datascience-finhack-an-online-hackathon/)

- ROC-AUC Score - 0.6579

- Leader board rank - 242/1342

[Analysis Notebook](https://nbviewer.jupyter.org/github/NishantBhavsar/ltfs-vehicle-loan-default-prediction/blob/master/code/Analysis.ipynb)

[Final model Notebook](https://nbviewer.jupyter.org/github/NishantBhavsar/ltfs-vehicle-loan-default-prediction/blob/master/code/model.ipynb)

### Libraries used:
```
pandas==0.23.4
numpy==1.16.2
matplotlib==2.2.2
seaborn==0.9.0
scipy==0.19.1
catboost==0.9.1.1
scikit-learn==0.19.2
```

### Problem Statement

Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and
increased vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate
the determinants of vehicle loan default.
A financial institution has hired you to accurately predict the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly
Instalments) on the due date. Following Information regarding the loan and loanee are provided in the datasets:
- `Loanee Information` (Demographic data like age, income, Identity proof etc.)
- `Loan Information` (Disbursal details, amount, EMI, loan to value ratio etc.)
- `Bureau data & history` (Bureau score, number of active accounts, the status of other loans, credit history etc.)

Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified which can be further used for
minimising the default rates.

### Evaluation Metric
- ROC-AUC score
