# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import NumPy and LinearRegression from sklearn.
2. Create the input data (study hours) and output data (marks scored).
3. Train the linear regression model using the fit() function.
4. Predict the marks using the predict() function and display the result.

## Program:
```

import numpy as np
from sklearn.linear_model import LinearRegression

X = np.array([1, 2, 3, 4, 5]).reshape(-1, 1)
Y = np.array([20, 30, 40, 50, 60])

model = LinearRegression()
model.fit(X, Y)

hours = np.array([[6]])
predicted_marks = model.predict(hours)

print("Slope:", model.coef_[0])
print("Intercept:", model.intercept_)
print("Predicted Marks:", predicted_marks[0])

```

## Output:
<img width="213" height="82" alt="image" src="https://github.com/user-attachments/assets/2ad594c1-9b0d-4f3a-a947-f4290caa85b7" />


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
