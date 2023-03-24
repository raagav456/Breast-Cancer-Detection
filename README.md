# Breast-Cancer-Detection

<p align="center">
  <img  src="https://user-images.githubusercontent.com/78891081/227557114-d8256b00-b03e-4a56-88b7-2954fbfe69f6.jpeg" width = "600" height = "300" >
</p>


# Overview

Among many cancers, breast cancer is the second most common cause of death in women. Early detection and early treatment reduce breast cancer mortality. MachineLearning plays an important role in breast cancer detection because it can detect it is benign or not using Logistic Regression (Supervised Learning Algorithm).
  
### Logistic Regression

<p align="center">
  <img  src="https://user-images.githubusercontent.com/78891081/227564652-cb467568-7f5b-4238-9d5e-5bdc30402600.png" width = "840" height = "320" >
</p>

<li>Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables.
  
<li>Logistic regression predicts the output of a categorical dependent variable. Therefore the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.

## Main Packages Used
  
```
import pandas as pd
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import confusion_matrix, accuracy_score
```

