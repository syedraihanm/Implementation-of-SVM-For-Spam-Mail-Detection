# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm:

1. Import the packages.

2. Analyse the data.

3. Use modelselection and Countvectorizer to preditct the values.

4. Find the accuracy and display the result.

## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
Developed by: Syed Mohamed Raihan M
RegisterNumber:  212224240167
*/

```
```
import pandas as pd
data=pd.read_csv("spam.csv", encoding='Windows-1252')
data

data.shape

x=data['v2'].values
y=data['v1'].values
x.shape

y.shape

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test = train_test_split(x,y,test_size=0.2, random_state=0)
x_train

x_train.shape
```

## Output:

### data 
![image](https://github.com/user-attachments/assets/751a0eb7-9d1c-4c77-9552-e7f52e59c769)

### data.shape()
![image](https://github.com/user-attachments/assets/cb1d2538-503a-4335-b566-078b0d78a405)

### x.shape()
![image](https://github.com/user-attachments/assets/6cb6109a-30f9-4004-a04d-491cd86a3c39)

### y.shape()
![image](https://github.com/user-attachments/assets/b535acc6-1ca7-413f-83d5-6617fa18cf85)

### x_train
![image](https://github.com/user-attachments/assets/ce406a1b-0ca9-487e-8268-498e2e1e322a)

### x_train.shape()
![image](https://github.com/user-attachments/assets/600711fd-5877-427a-b219-d878dc0cddf1)

### y_pred
![image](https://github.com/user-attachments/assets/b5ad8b3d-b11b-42a1-a6eb-8cf71cf47391)


### acc (accuracy)
![image](https://github.com/user-attachments/assets/e1cfbd5b-f292-411b-b631-2980c7d013f8)

### con (confusion matrix)
![image](https://github.com/user-attachments/assets/b5a887a9-fe31-4bad-80b7-260ec2ed3408)

### cl (classification report)
![image](https://github.com/user-attachments/assets/4f3c39d7-d93b-4384-a3b4-e7cbded34fb7)

## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
