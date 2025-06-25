
##  Credit Score Classification

A brief description of what this project does and who it's for

You are working as a data scientist in a
global finance company. Over the
years, the company has collected basic
bank details and gathered a lot of
credit-related information. The
management wants to build an
intelligent system to segregate the
people into credit score brackets to
reduce the manual efforts. Given a
person’s credit-related information,
build a machine learning model that
can classify the credit score.
## Dataset
dataset link: (https://www.kaggle.com/datasets/parisrohan/credit-score-classification)

About this Dataset
This dataset contains information about a sample of over 100 people across the world. Credit score dataset contains 1 lac records with 28 features. The data includes the following information:
![image](https://github.com/user-attachments/assets/a91684a4-796e-4d8d-b079-d4589b09c1d3)


## Importing python libraries


We start off this project by importing all the necessary
libraries that will be required for the process.

![image](https://github.com/user-attachments/assets/1a0b5441-95e7-4968-82ed-7510f96a893a)

->Import Libraries(pandas, numpay, matplotlib, seaborn)

->Loading the Dataset

->Handling the missing values
  
  ![image](https://github.com/user-attachments/assets/8dec8da6-fd90-4876-8a30-a86b57adb318)

  ![image](https://github.com/user-attachments/assets/8dcd97c0-3cd7-47b8-bf6c-830115807a19)


## Data Cleaning


Replacing the special
characters with empty
string or with null
values according to
the data and
converting it into int
or float datatype. Also,
Converting the
categorical values of
some columns into
integer values.

![image](https://github.com/user-attachments/assets/93e79c8f-5b18-45d9-8cca-f56f44266530)

![image](https://github.com/user-attachments/assets/48ebdf2f-f6ce-4346-bf77-18b83e714fbc)

After replacing the
special characters with
null value. The new
missing value is shown
in the figure. Here
Forward and backward
filling method is used
to fill the missing
values.

![image](https://github.com/user-attachments/assets/34be9949-d8d4-4564-aefa-0c7124771240)

![image](https://github.com/user-attachments/assets/747db467-1175-41a8-9190-9709f952a692)

![image](https://github.com/user-attachments/assets/f023b703-1730-4e2e-b459-131f79fc055b)



Removing outliers
from age since all
other columns
values are
relevant.

![image](https://github.com/user-attachments/assets/00c957cf-9071-4553-a602-681afe254310)

![image](https://github.com/user-attachments/assets/ae7ed8e5-5d0e-4d2a-b4e1-d069aa08ffae)

![image](https://github.com/user-attachments/assets/a539e05a-4481-44cb-b2f0-69176d19d4ea)

![image](https://github.com/user-attachments/assets/c819b305-8f29-44e0-b6e1-d7f043fc2971)


Performing One Hot Encoding for categorical features of a dataframe

![image](https://github.com/user-attachments/assets/94816942-2629-432c-acc1-21983bd36110)

![image](https://github.com/user-attachments/assets/2c870e74-a7f4-4756-8dd4-c801facad1d9)


## Feature Selection 

->VIF(Variance Inflation Factor)

Selecting the features using VIF. VIF should be less
than 5. Here, all features have VIF value less than
5, So we will select all the features. 

![image](https://github.com/user-attachments/assets/c5ecc853-c711-42a4-9b52-7741bc6f87b0)

![image](https://github.com/user-attachments/assets/63c17eb4-19d0-4366-acec-161a96839ca0)


->Logistic Regression

The accuracy of the logistic regression model is
61.8 percentage.

![image](https://github.com/user-attachments/assets/77fc9814-9bdf-4786-8b20-b9d191dc80ea)

![image](https://github.com/user-attachments/assets/7019b4bb-2c11-43d5-abe9-8116b3e4bf9f)

![image](https://github.com/user-attachments/assets/91b72b7d-059e-4e20-9694-c3b29b9f8731)


->Decision Tree

The accuracy of the decision tree model is
69.7 percentage.

![image](https://github.com/user-attachments/assets/0f2fb887-8f85-4b6a-9f93-2f335f411565)

![image](https://github.com/user-attachments/assets/3c6462a5-741e-4b23-ac00-3775b5fb7bb0)

![image](https://github.com/user-attachments/assets/b6972371-2e45-4173-9351-e7c54c1beadf)


->Hyperparameter Tuning on Decision Tree

Here, We are using
GridSearch CV technique
which is used to identify the optimal
hyperparameters for a model and the
accuracy obtained from Decision
Tree is 70.93.

![image](https://github.com/user-attachments/assets/938f8646-b910-4cbc-84a5-d064b18988c6)

![image](https://github.com/user-attachments/assets/6a6e7a89-5d5a-45a2-a0a6-0c29af073ae2)


->Random Forest

The accuracy of the random forest model is
79.7 percentage.

![image](https://github.com/user-attachments/assets/84f4353d-8ed7-42de-87ba-d5f0bbec7645)

![image](https://github.com/user-attachments/assets/127c95eb-25e4-4885-abbf-e24b0d1f18fb)

![image](https://github.com/user-attachments/assets/b6160cfc-9ba7-461f-b4c1-104d05b22438)






