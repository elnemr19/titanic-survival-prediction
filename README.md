# titanic-survival-prediction

## Project Overview

 --This project aims to build a machine learning model to predict whether a passenger on the Titanic would survive the disaster, based on features such as passenger class, sex, age, and more

## Dataset
--Source of the dataset (Kaggle :'https://www.kaggle.com/datasets/yasserh/titanic-dataset/data')

--the shape of dataset is (891, 10) ,we have features such as ['PassengerId', 'Survived', 'Pclass', 'Name', 'Sex', 'Age', 'SibSp', 'Parch', 'Ticket', 'Fare', 'Cabin', 'Embarked']
  first i remove features that won't affect on machine accuracy  ,such as ['PassengerId' ,'Name' ] ,then i check for duplication and null values and i fount that 
  'Cabin' contain around 70% null so i removed it ,and the 'Age' contain 177 null value and i replace them with the mean value of age ,and i found that 'Ticket' wan not important so 
  i removed it 




 
