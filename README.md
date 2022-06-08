# Credit-Card-Defaulters-using-Regression
This is a small ML project, where after looking at some data, we can try and predict whether a customer, applying for a loan, would turn out to be a defaulter or not.<br>
Now in this case, we are more interested in making sure a bad loan is not handed out. A good loan (given to a non-defaulter) being denied only costs the company profit, but a bad loan (loan given to a defaulter) being approved risks the company losing the principal amount. So, specificity becomes more important than sensitivity in this case. <br>
A simple LogisticRegression model has been used here, and metrics like ROC curve and auc are used to verify the models and to try and pick the best one among them. <br><br>
(The dataset can be found in the "data" folder, or can be downloaded here: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
