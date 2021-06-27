# Machine Learning Sprint
# Le Wagon "Women in Data Day: Explore Machine Learning", 19 June 2021

This sprint contains two Jupyter notebooks with prediction exercises I completed with Scikit-learn at the Le Wagon event.

## 1. OLS prediction of salaries
The challenge was to predict a new hire's salary using the data about existing employees at the company and their salaries.

I started with an exploratory data analysis (EDA) using pandas, NumPy, matplotlib, and Seaborn to understand and visualize the dataset. 

Building upon the EDA, I used Scikit-learn an OLS regression model of an employee's gross salary as shaped by their age, gender, department, years of experience, and length of tenure at the company. I then applied the model to predict new hires' salary.

## 2. KNN prediction of customer churn
This challenge consisted of predicting whether a bank's customer would leave the bank, using data about other customers.

After a quick EDA and visualization, I built a K-nearest-neighbors machine learning model with Scikit-learn. It predicts the probability that a customer will leave the bank (churn) based on their:
* demographics (age and gender), 
* financials (credit score, estimated salary), and 
* existing use of the bank's products (number of products they use, bank balance, whether they have a credit card, etc.).
