# Individual's income level prediction
Here, we applied logistic regression and boosting algorithms to predict whether income of individual's exceeds 50K.

## <img src="https://cdn-icons-png.flaticon.com/128/3176/3176324.png" width="20" /> Objectives
-  Compare Accuracy of the Models
-  Compare ROC AUC Score
-  Discuss trade-off between interpretability and predictive power

## <img src="https://cdn-icons-png.flaticon.com/128/18289/18289400.png" width=20 /> Dataset
-  Title:Incomes of people with different demographic features
-  Source: https://archive.ics.uci.edu/static/public/2/data.csv
-  Size: 48,842
-  Independent Variables: Age, Workclass, Education, Marital Status Etc. 
-  Target Variable: Income <=50K or >50k
## <img src="https://cdn-icons-png.flaticon.com/128/6259/6259277.png" width=20 /> Libraries
- Pandas
- Numpy
- Scikit-Learn
- XGBoost

## <img src="https://cdn-icons-png.flaticon.com/128/2172/2172891.png" width=20 /> Model Training
-  Logistic Regression
-  Gradient Boosting
-  Extreme Gradient Boosting (XGB)
#### What is the difference between gradient boosting and extreme gradient boosting?
- Gradient Boosting is an ensemble technique that builds models sequentially, where it starts with a weak model and corrects the errors of the previos one until it converges.
- Extreme gradient boosting is an enhanced and optimized version of gradient boosting. Unlike gradient boosting, extreme gradient boosting includes L1 & L2 regularization, handles missing values automatically, and controls overfitting with both learning rate & regularization.

## <img src="https://cdn-icons-png.flaticon.com/128/1844/1844921.png" width=20 /> Model Evaluation
- Accuracy
- ROC AUC Score

## <img src="https://cdn-icons-png.flaticon.com/128/9623/9623606.png" width=20 /> Insights
- As expected, the boosting algorithms outperformed logistic regression by a lot.
- The accuracy of XGB was not significantly higher than the accuracy of GB, but the ROC AUC score indicated the XGB model is better at classification. 







