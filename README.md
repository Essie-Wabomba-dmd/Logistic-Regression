## Logistic Regression 
#### What you need to know.
Linear regression is better for classification problems like predicting whether it will rain tomorrow. 
For any ML problem, first identify if it's a classification or regression problem

#### Classification problems
- problems where each input must be assigned a discrete category (also called label or class)
##### Examples:
- Rainfall prediction
- Breast cancer prediction - predicting whether a tumor is "benign" (noncancerous) or "malignant" (cancerous) using
information like its radius, texture etc
- Loan repayment prediction
- Handwritten Digit Recognition - Identifying which digit from 0 to 9 a picture of handwritten text represents etc
Classifications problems can be binary (yes/no) or multiclass (picking of many classes)

#### Regression problems
Problems where a continous numeric values must be predicted for each input.
##### Examples:
- Medical Charges prediction
- House Price Prediction
- Ocean temperature Prediction
- Weather Temperature Prediction etc
### Linear Regression for solving Regression problems
Linear regression is commonly used to solve the regression problems.  
In a linear regression model, the target is modeled as a linear combination (or weighted sum) of input features.  
The predictions from the model are evaluated using a loss function like the Root Mean Square Error (RMSE)

### Logistic Regression for Solving Classification Problems
- Logistic regression is a commonly used technique for solving binary classificatio problems. In a linear regression model:

- We take linear combination (or weighted sum of the input feature)
- We apply sigmoid function to the result to obtain a number between 0 and 1
- This number represents the probability of the input being classfied as "Yes"
- Instead of RMSE, the cross entropy loss function is used to evaluate the results
  
The output of the sigmoid function is called **a logistic**, hence the name **Logistic regression**.   
Logistic regression can also be applied to multi-class classification problems, with a few modifications.  

- Classification and regresssion are both **supervised ML problem**, because they use labeled data.   
- ML applied to unlabeled data is known as **unsupervised learning**- Clustering.
