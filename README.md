# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Read the csv file

### Step2
Get the value of X and y variables



### Step3:
Create the linear regression model and fit

### Step4
Predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm cube.



### Step5
Print the predicted output.

## Program:
```


Developed by: BALAJI J
Reg.No: 212221243001
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))





```
## Output:

### Insert your output

![image](https://github.com/Balaji-Jothiramalingam/Multivariate-Linear-Regression/assets/114234865/d3078e32-df36-4297-9038-d0b67c1015d8)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
