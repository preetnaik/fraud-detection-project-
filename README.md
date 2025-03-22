Fraud Detection Using Machine Learning
This project analyzes fraudulent transactions using ML models like Logistic Regression, Random Forest, Gradient Boosting, and XGBoost to detect fraud efficiently.



step - maps a unit of time in the real world. In this case 1 step is 1 hour of time.
type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.
amount - amount of the transaction in local currency.
oldbalanceOrg - initial balance before the transaction
newbalanceOrig - new balance after the transaction.
nameDest - customer who is the recipient of the transaction
oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).
newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).
isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.
