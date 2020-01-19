![](https://user-images.githubusercontent.com/21193878/56485800-185ba300-64f3-11e9-9b61-149f2ac47b2d.PNG)

Vehicle Loan Default Prediction Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate the determinants of vehicle loan default. 

The aim of this exercise is to accurately predict the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Instalments) on the due date. Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified which can be further used for minimising the default rates.

Following Information regarding the loan and loanee are provided in the datasets:

Loanee Information (Demographic data like age, income, Identity proof etc.) 
Loan Information (Disbursal details, amount, EMI, loan to value ratio etc.) 
Bureau data & history (Bureau score, number of active accounts, the status of other loans, credit history etc.) 

This solution uses ensmeble of LightGBM, CatBoost and Lasso Regressions. The solution was in Top 10% pool securing a rank of 90 out of 1329 participants.

Competition Link - https://datahack.analyticsvidhya.com/contest/ltfs-datascience-finhack-an-online-hackathon/pvt_lb
