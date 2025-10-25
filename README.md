# Individual's income level prediction
Often times, data scientists and researchers are biased to advanced machine learning models because of their predictive power. Here, we compared logstic regression with two boosting algorithms and explained why boosting algorithms outperform logistic regression.

## <img src="https://cdn-icons-png.flaticon.com/128/3176/3176324.png" width="20" /> Objectives
-  Train and Test Logistic Regression and Boosting Algorithms.
-  Create a group bar-chart that demonstrates the key metrices. 
-  Discuss Key Insights.

## <img src="https://cdn-icons-png.flaticon.com/128/18289/18289400.png" width=20 /> Dataset
-  __Title__:Incomes of people with different demographic features
-  __Source__: https://archive.ics.uci.edu/static/public/2/data.csv
-  __Dataset Size__: 48,842
-  __Independent Variables__: Age, Workclass, Education, Marital Status Etc. 
-  __Target Variable__: Income <=50K or >50k
## <img src="https://cdn-icons-png.flaticon.com/128/6259/6259277.png" width=20 /> Libraries
- Pandas
- Numpy
- Scikit-Learn
- XGBoost
- Matplotlib

## <img src="https://cdn-icons-png.flaticon.com/128/2172/2172891.png" width=20 /> Applied Models
-  <img src = "https://cdn-icons-png.flaticon.com/128/8003/8003263.png" width=20/> Logistic Regression
-  <img src = "https://cdn-icons-png.flaticon.com/128/17814/17814841.png" width=20/> Gradient and Extreme Gradient Boosting

## <img src="https://cdn-icons-png.flaticon.com/128/1844/1844921.png" width=20 /> Evaluation Metrices
- Accuracy
- ROC AUC Score
- Log-loss

## <img src="https://cdn-icons-png.flaticon.com/128/9623/9623606.png" width=20 /> Insights
<div style="text-align: center;">
    <img src="https://github.com/casper6020/Income-level-prediction-Adult-Dataset/blob/main/Comparison_Figure.png" width: 450px; height: 300px/>
</div>

- The Accuracy, ROC AUC Scores and Log-loss clearly indicated that the boosting algorithms are significantly better at predicting.
#### Why Boosting algorithms outperform logistic regression?
- Unlike logistic regression, the boosting algorithms can capture non-linear relationships and can correct the errors of the previous learner while training.
- Though, the boosting alogorithms are significantly better at predictions, they are difficult to explain to non-technical personnel and impractical to use if there is an audit issue.
- Therefore, one should apply logistic regression if the relationship between independent and target variable is linear and the project is likely to face audit. 
- Moreover, the scores demonstrated that the XGBoost model is better than the GB algorithm.

#### Why XGB model outperforms GB model? 
- XGBoost applies L1 (Lasso) or L2 (Ridge) regularization to avoid overfitting and improve model generalization. These techniques are unavailable in GB model.
- XGBoost uses second-order derivatives (Hessian information) for optimizing the loss function, providing more precise gradient updates and better convergence than GB, which uses only first-order gradient information. 







