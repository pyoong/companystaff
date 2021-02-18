Project to create a machine learning model to predict the attrition of the employees of a company. 
Based on the given data, Hierarchical Clustering was carried out to identify the clusters.
Four clusters were obtained and a deduction of the classes are made. The classes are as follows :- Class 0: permanent employee, Class 1: temporary employee, Class 2: predicted to leave the company, Class 3: contractual employee.
After identifying the clusters, various machine learning models such as Logistic Regression, Random Forest, Support Vector Machine, Decision Tree were applied.
Hyperparameter tuning is carried out to determine the optimal values for a given model.
The best model is Support Vector Machine classifier which has the highest accuracy, precision and F1-score.
A Flask web application is created where a user is able to key in the new data of an employee https://analyticsattrition.herokuapp.com.
Prediction is then made by the machine learning model whether the employee is more likely to leave the company with the given attributes.
The target class is Class 2 where the employee is predicted to leave the company while in other classes the employee is expected to remain in the company.
