# Employee Attrition Prediction

This repository contains the code for predicting employee attrition using a machine learning model. The model is built using various classifiers and can predict whether an employee will leave the company based on several features.

# Overview

The goal of this project is to predict whether an employee will leave the company or not based on various features such as age, business travel, department, job satisfaction, and more. The prediction model is trained on a dataset from Kaggle and uses a voting classifier combining multiple machine learning algorithms.
Dataset

The dataset used for this project is the IBM HR Analytics Employee Attrition & Performance dataset available on Kaggle. This dataset contains various features related to employees and their work environment.
Model Training

The model is built using several classifiers, including Logistic Regression, SVM, Neural Network, Random Forest, and Gradient Boosting. The classifiers are combined into a voting classifier to improve the prediction accuracy.

# Installation

Clone the repository:
``` git clone https://github.com/juinaik-1/employee-attrition-prediction.git ``` 
``` cd employee-attrition-prediction ``` 

Create and activate a virtual environment:
``` python -m venv venv ``` 
``` source venv/bin/activate   # On Windows, use `venv\Scripts\activate` ``` 

Install the required packages:
``` pip install -r requirements.txt  ```

# References

  Kaggle Dataset: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
  Kaggle Notebook: [link to my kaggle notebook](https://www.kaggle.com/code/juinaik/attrition-prediction)

# Acknowledgements

Thanks to IBM and the contributors on Kaggle for providing the dataset and resources for this project.
