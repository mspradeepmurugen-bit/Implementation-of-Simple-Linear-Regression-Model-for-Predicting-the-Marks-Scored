# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: Pradeep.M
RegisterNumber: 212225220071

import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
x=np.array([1,2,3,4,5,]).reshape(-1,1)
y=np.array([35,50,65,70,85])
model=LinearRegression()
model.fit(x,y)
x_i=float(input("Enter hours studied:"))
p_m=model.predict([[x_i]])
print("Predicted Marks:",p_m[0])
y_p=model.predict(x)
plt.scatter(x, y, label='Data Points')
plt.plot(x, y_p,label='Regression Line')
plt.title("Linear Regression")
plt.xlabel("X")
plt.ylabel("Y")
plt.legend()
plt.show()
```

## Output:
<img width="729" height="511" alt="Screenshot 2026-08-20 212256" src="https://github.com/user-attachments/assets/efddc217-f97e-4fbd-a9bd-76f3c10625a0" />

## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
