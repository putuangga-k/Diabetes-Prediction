# Diabetes Prediction Using Random Forest and K Nearest Neighbors

This project aims to predict diabetes among Data Science Students class of 2022 using two popular machine learning algorithms: Random Forest and K Nearest Neighbors (KNN). The goal is to compare the performance of these models and determine the most effective one for diabetes prediction.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Algorithms Used](#algorithms-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Diabetes is a chronic disease that requires early detection and effective management to prevent complications. This project leverages machine learning techniques to predict diabetes in a specific cohort: the Data Science Students class of 2022. By applying Random Forest and KNN algorithms, we aim to identify the most accurate model for predicting diabetes based on a given dataset.

## Dataset
The dataset used in this project consists of train data from UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/529/early+stage+diabetes+risk+prediction+dataset) and test data that is collected from a survey includes health-related information of Data Science students that is collected using forms. It consists of various features such as:
* Age
* Gender
* Polyuria
* Polydipsia
* Sudden Weight Loss
* Other medical data

The dataset is anonymized to protect the privacy of the students.

## Algorithms Used
* **Random Forest**: An ensemble learning method that builds multiple decision trees and merges them to get more accurate and stable predictions.
* **K Nearest Neighbors (KNN)**: A simple yet powerful algorithm that classifies data points based on their proximity to other data points.

## Installation
To run this project, you'll need to have Python installed along with several libraries. Here are the libraries necessary for this project :
* Pandas
* Scikit-learn
* Statsmodels
* Seaborn
* Matplotlib
* Xgboost
* Imblearn

 ## Usage 
 1. Clone the repository
    ```bash
    git clone https://github.com/putuangga-k/Diabetes-Prediction.git
 2. Navigate to the project directory:
    ```bash
    cd diabetes-prediction
 3. Install required libraries
    ```bash
    pip install -r library name 
 5. Start jupyter notebook
    ```bash
    jupyter notebook

 ## Results
 The results of the predictions will be displayed, showing the accuracy, precision, recall, and F1 score of both Random Forest and KNN models. A comparison will be made to determine the more effective algorithm for this specific dataset.

 ## Conclusion
This project demonstrates the application of Random Forest and KNN in predicting diabetes among Data Science students. The findings provide insights into the strengths and limitations of these models in medical diagnostics, guiding future research and practical applications.

 ## Contributors 
 Contributions are welcome! Please feel free to submit a Pull Request.

 ## License 
 This project is licensed under the Apache License. See the LICENSE file for details.
