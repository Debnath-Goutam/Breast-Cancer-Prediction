# Breast-Cancer-Prediction

## Project Overview
This project aims to predict whether a patient has breast cancer based on certain features such as radius, perimeter, smoothness etc. the project aims to correctly predict as many malignant cases as possible.

## Data
The data used in this project is sourced from **Breast Cancer Wisnonsin (Diagnostic)**. The dataset contains 569 real instances, computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.  They describe characteristics of the cell nuclei present in the image. For the dataset, click here. [Breast Cancer Wisconsin (Diagnostic) dataset](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

## Methodology
In this project we first do an **Exploratory Data Analysis** to find out any relations and correlations between the features and diagnosis and among the features themselves. Data Visualization is carried out using libraries such as matplotlib and seaborn. Then we move to model building and training. For this project, we have selected three machine learning algorithms, and the model giving the best estimateis chosen for making predictions. The three algorithms are:
- **Logistic Regression**
- **Random Forest Classifier**
- **XGBoost Classifier**

Hyperparameter tuning is done using **5-fold Grid Search Cross Validation** technique. **Recall (Sensitivity)** is giver a higher preference in the evaluation of the models, as we aim to rather miissclassify some benign cases than miss any malignant cases. Post model training and evaluation, we find that **XGBoost Classifier** gives the best estimate out of the three algorithms.

## How to Run the Project
Instructions on how to run the analysis on your local machine:
- Clone the repository.
- Make sure you have the Jupyter Notebook, Python and the necessary libraries installed.
- Open the '[Breast Cancer Predictive Analysis.ipynb](https://github.com/Debnath-Goutam/Breast-Cancer-Prediction/blob/master/Breast%20Cancer%20Predictive%20Analysis.ipynb)' file in your Jupyter Notebook.
- Click on Cells -> Run All

