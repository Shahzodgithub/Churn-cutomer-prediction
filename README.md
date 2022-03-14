# Churn-cutomer-prediction
The project is structured as follows:
1.	Exploratory Data Analysis
2.	Data Preprocessing
3.	Model Creation and Evaluation


In order to achieve the best possible lead accuracy of this project work by using the machine learning methodologies. Our goal is to predict churn rate of customers.
First of all, I converted the “churn.txt” file to utf-8 txt file (https://subtitletools.com/convert-text-files-to-utf8-online), because it has strange characters which are not readable.

1. Supervised learning - because we have a label in the data. 
2. Regression model - If we say "prediction", then it is solved using regression algorithms
3. Offline - because the data was given to us once before. There is no constant data flow.

o	Changed some datatypes, dropped some columns, analyzed target columns, finding correlation the churn and the other columns.
o	Normalized data by using Max-Min Scaling

o	Then started model building, created two dataframes, X with predictor variables and Y with target variable Churn.


Conclusion,
It was achieved an overall accuracy of almost 76% in Logistic Regression model. We can improve the accuracy by using the other models but I used only one model.

