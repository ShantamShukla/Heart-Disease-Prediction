# README
## Introduction
This ML code is designed to predict the likelihood of heart disease in patients based on a dataset obtained from the Behavioral Risk Factor Surveillance System (BRFSS) which is collected annually by the Centers for Disease Control and Prevention (CDC). The dataset used in this code contains responses from 441,455 individuals and has 330 features. The code uses different machine learning algorithms like Random Forest, Logistic Regression, Support Vector Machine, and K-Nearest Neighbors to train the models and predict the likelihood of heart disease in patients based on their features.

## Installation
To run this code, you need to have Python installed on your system. You also need to install the required libraries like pandas, scikit-learn, and numpy. You can install these libraries using pip, by running the following command:
pip install pandas scikit-learn numpy

## Usage
To use this code, you need to download the "heart_disease_health_indicators_BRFSS2015.csv" dataset and save it in the same directory as the code. Then, you can simply run the code using a Python IDE or from the command line.

The code will load the dataset and split it into training and testing sets. It will then train different machine learning models like Random Forest, Logistic Regression, Support Vector Machine, and K-Nearest Neighbors on the training set and test them on the testing set. The code will then select the best model based on its accuracy on the testing set.

Next, the code will perform feature importance analysis using the selected model and print the top features that contribute most to the prediction of heart disease. Finally, the code will prompt the user to enter values for the top features and predict the likelihood of heart disease in the patient based on the entered values.

## Conclusion
This ML code is designed to predict the likelihood of heart disease in patients using different machine learning algorithms. It uses the BRFSS dataset to train the models and select the best model based on its accuracy on the testing set. The code also performs feature importance analysis and prompts the user to enter values for the top features to predict the likelihood of heart disease in the patient. This code can be used as a tool to assist clinicians in diagnosing coronary heart disease in patients.

## Reference
Kaggle Dataset:- https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset