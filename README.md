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
- Log-loss

## <img src="https://cdn-icons-png.flaticon.com/128/9623/9623606.png" width=20 /> Insights
<img src="https://github.com/casper6020/Income-level-prediction-Adult-Dataset/blob/main/Comparison_Figure.png" style="width: 450px; height: 300px;"/>
- The Accuracy, ROC AUC Scores and Log-loss clearly indicated that the boosting algorithms are significantly better at predicting.
- In addition, the scores demonstrated that the XGBoost model is better than the GB algorithm.
- 
- 
- Though, the boosting alogorithms has significantly high predicting ability, they are hard to explain to non-technical persons and impractical to use if there is an audit issue.
- Therefore, one should apply logistic regression if the relationship between independent and target variable is linear and the project is likely to face audit. 

#### Why XGB model outperforms GB model? 
- 







