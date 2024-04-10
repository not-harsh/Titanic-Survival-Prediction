# Titanic-Survival-Prediction

This project implements a logistic regression model to predict survival on the Titanic dataset. It includes data preprocessing, model training, and accuracy evaluation

**Dependencies**

- pandas
- scikit-learn
- numpy

  
**Usage**

Place the Titanic dataset CSV file (Titanic-Dataset.csv) in the project directory.

Run the titanic_survival.ipynb file

**Data**

The dataset used in this project is the Titanic dataset (Titanic-Dataset.csv), which contains information about passengers on the Titanic.

The dataset includes features such as age, gender, fare, and embarkation port.

Missing values in the 'Age' and 'Embarked' columns are handled by imputing the mean and mode, respectively.

**Model Training**

Logistic regression is used as the machine learning model.

The dataset is split into training and testing sets using a 80-20 ratio.

The model is trained on the training set and evaluated on the testing set.

Accuracy score is used as the evaluation metric.

**Results**

The accuracy of the model on the training set is printed.

The accuracy of the model on the testing set is printed.

A sample input data is provided to make predictions using the trained model.
