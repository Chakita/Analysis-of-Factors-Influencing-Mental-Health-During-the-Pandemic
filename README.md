# Data-Analytics-Project
Repo for project titled - Analysis of factors influencing mental health during the Pandemic, done as a part of the Data Analytics ( UE19CS312 ) course at PES University.

This project aims to observe the degree by which trust in various authorities, sources of information and methods of coping influence levels of stress in certainpopulations. We also aim to take into consideration factors such as the country’s average expenditure on healthcare in the past decade along with stringency scores that indicate the level of
strictness in a country and analyse how these factors influence Perceived Stress Scores in different countries. Finally, we also perform clustering analysis to find out which countries responded similarly to the pandemic.

Considering the problem statements, data set and the length of the list of features, certain popular classification and regression methods have been used. The ordinal nature of
the target variable was taken into account as well. Ordinal Regression, Decision Trees, AdaBoost, XGBoost, Ridge and Lasso Regression and Support Vector Regression are the
models presented in this project.

## Ordinal Models
Ordinal Regression is performed using a Generalized Linear Model. The model computes the coefficient vector and thresholds for the problem. Given a set of observations
denoted by vectors x1,x2..xn each of length d and a set of the corresponding values of the dependent variable denoted by y1through yn, the model finds a coefficient vector W and a set of thresholds &theta;1 &theta;2...&theta;d-1 such that &theta;1 > &theta;2... > &theta;d-1.
The model can be formulated according to the expression given below<br>
![image](https://user-images.githubusercontent.com/62837028/144746919-3d3b34af-5115-4c47-b177-31531699e075.png)

## Classifier Models

The decision tree used in this project employed the CART algorithm.The CART algorithm builds decision trees based on the feature that gives the largest information gain at every
node.

Adaboost is an ensemble machine learning technique. Multiple weak learners learn sequentially on the whole data to classify new instances. Incorrectly classified instances by a
particular estimator or learner are given larger weights for that iteration so future learners focus on accurately classifying those points.

XGboost, a decision tree based ensemble learning algorithm was employed to achieve a greater accuracy.

## Regression Models
Ridge and Lasso regression help us by choosing important features themselves by giving more weight to relevant features.Here, the target variable, ’Perceived Stress’ is not binned, and hence is a regression model
Support Vector Regression uses the concept of support vector machines to unravel regression problems. The algorithm tries to find a hyperplane that suitably classifies data instances

## Clustering Analysis
We performed clustering analysis in order to answer the question, ”Which countries are most similar in terms of trust in media and government ?”

Full results of this study can be found in the corresponding paper.
