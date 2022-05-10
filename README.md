# Credit Card Approval Logreg
This Project is making Model Machine learning to predict whether or not the Credit card being approved.

The dataset is retrived from the [http://archive.ics.uci.edu/ml/datasets/credit+approval](http://archive.ics.uci.edu/ml/datasets/credit+approval) 

For making Machine Learning Model there are steps to begin with:
1. [Data Collecting](#data-collecting)
2. [Data Cleaning](#data-cleaning)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Fitting](#model-fitting)
5. [Model Evaluating](#model-evaluating)

<a id='data-collecting'></a>
## 1. Data Collecting
In Data Collecting, I use one of python's library that is pandas. after that, I Inspecting the dataset to make sure that dataset is categorical or regression.

<a id ='data-cleaning'></a>
## 2. Data Cleaning
In order to clean data, I need to make that the data has in correct data type such as: integer, category, date time. After that, inspecting the unrelevant as missing value by giving the Nan value. So then, missing value can be treat by its column and datatype.

<a id ='data-preprocessing'></a>
## 3. Data Preprocessing
After the Missing Value has been treat, the next step is to preprocess the data:
1. Making dummies for categorical data.
2. Rescale all data into the same scale.
3. Split the data into features and targets then split into train set and test set.

<a id ='model-fitting'></a>
## 4. Model Fitting
Time to fit the model, the model I use is Logistic Regression.

<a id ='model-evaluating'></a>
## 5. Model Evaluating
After fitting the model, the model can be use to predict the new data set and use it for evaluating with accuracy and confusion matrix.
