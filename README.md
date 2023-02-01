# kaggle_mobile_classification

 kaggle classification competition


About Dataset:

Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.

In this problem you do not have to predict actual price but a price range indicating how high the price is


# In this notebook, I use the method of ensembling algorithms Stacking
## As basic algorithms I used
* LogisticRegression
* GradientBoostingClassifier
* KNeighborsClassifier
* Support Vector Machine
* DecisionTreeClassifier

## As a meta algorithm I used
* XGBoost Classifier

With the help of GridSearchCV, the optimal parameters for the basic algorithms and the XGBoost meta algorithm were selected

## Basic algorithms accuracy
* LogisticRegression Accuracy score : 0.971
* GradientBoostingClassifier Accuracy score : 0.883
* KNeighborsClassifier Accuracy score : 0.923
* SVC Accuracy score : 0.940
* DecisionTreeClassifier Accuracy score : 0.838

## Meta algorithm accuracy
* Meta Algorithm - XGBoost Accuracy score : 0.975






