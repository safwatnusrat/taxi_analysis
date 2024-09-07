## Problem Definition:
The problem is to predict the average money spent on taxi rides across different regions of New York per given day and hours. This is a supervised regression problem, where "supervised" implies that we have the actual values of the target variable for comparison, and "regression" denotes that the target variable is continuous, representing the monetary amount spent.

## The algorithms I tried in the results:
I tried Decision Trees, Random Forest, Gradient Boosting.The benchmark model is a decision tree. In the benchmark model I only included  the original features of the model is stated above and on the normal models I used all original features plus with the newly created ones.

## Performance:
| Algorithm               | MAE   | RMSE   | R2    |
|-------------------------|-------|--------|-------|
| Benchmark model         | 6.918 | 14.916 | 0.689 |
| Decision tree           | 7.173 | 15.113 | 0.689 |
| Random forest           | 6.806 | 13.063 | 0.768 |
| Gradient boosting       | 7.087 | 12.255 | 0.796 |
| Tuned gradient boosting | 7.085 | 12.263 | 0.796 |


## Visulization

### Scatter plot of Random Forest 

![Random forest](/images/random_forest.png)
### Scatter plot of Gradient Boosting
![Gradient Boosting](/images/gradient_boosting.png)
### Scatter plot of Decision Tree
![Decision tree](/images/decision_tree.png)

