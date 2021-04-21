# student-exam-predict
Predicting student performance on exams is useful in school environments. With ML, we can predict students' test score efficiently and accurately. 
In this project, I used data visualization tools (seborn, matplotlib), methods for datapreprocessing, and the linear regression algorithm.
## Download Data
The dataset used here can be found on Kaggle at this link : https://www.kaggle.com/spscientist/students-performance-in-exams
## Data Specifics
In the data, you are given several features: 

 1. gender
 
 2. race/ethnicity
 
 3. parental level of education
 
 4. lunch
 
 5. test preparation course
 
Based on these features, predictions will be made on the students' math score, reading score, and writing score. 
My model gives the prediction of the overall score for the student.
## Algorithm
This is a regression problem, where we need to predict a value based on the attributes (that value is the overall score) as opposed to classify features. I used linear regression for this problem. In linear regression, the model minimizes the residual sum of squares between the true y values and predicted values. More about linear regression can be found [here](https://en.wikipedia.org/wiki/Linear_regression#:~:text=In%20statistics%2C%20linear%20regression%20is,as%20dependent%20and%20independent%20variables).

| Type | Root Mean Squared Error (RMSE) |  Mean Squared Error (MSE)| Mean Absolute Error MAE|
|--|--|--|--|
| Linear Regression | ~ 9.49262 | ~ 9.01098|  ~ 6.56577|
## Use
There is a csv file with the dataset: 
        contains my code.
        
        
  is my linear regression model.
        
Use of matplotlib, pandas, numpy, seaborn, scikit learn, and tensorflow.keras is needed. Update to Python 3.5 is recommended.
