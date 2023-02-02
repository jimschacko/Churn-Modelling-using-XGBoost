# Churn-Modelling-using-XGBoost
<b>Objective</b>

Can you develop a model of machine learning that can predict customers who will leave the company?
The aim is to estimate whether a bank's customers leave the bank or not. The event that defines the customer abandonment is the closing of the customer's bank account.
Details about the dataset:
It consists of 10000 observations and 12 variables. Independent variables contain information about customers. Dependent variable refers to customer abandonment status.


<b>Variables</b>:

RowNumber — corresponds to the record (row) number and has no effect on the output. This column will be removed.
CustomerId — contains random values and has no effect on customer leaving the bank. This column will be removed.
Surname — the surname of a customer has no impact on their decision to leave the bank. This column will be removed.
CreditScore — can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
Geography — a customer’s location can affect their decision to leave the bank. We’ll keep this column.
Gender — it’s interesting to explore whether gender plays a role in a customer leaving the bank. We’ll include this column, too.
Age — this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
Tenure — refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
Balance — also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
NumOfProducts — refers to the number of products that a customer has purchased through the bank.
HasCrCard — denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank. (0=No,1=Yes)
IsActiveMember — active customers are less likely to leave the bank, so we’ll keep this. (0=No,1=Yes)
EstimatedSalary — as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
Exited — whether or not the customer left the bank. This is what we have to predict. (0=No,1=Yes)

<b>Result</b>
The model created as a result of XGBoost hyperparameter optimization became the model with the maximum Accuracy Score. (0.8552)
