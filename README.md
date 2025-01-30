# machine_learning_in_pyspark
# LBB Regression using MLlib

## Overview
This repository contains an implementation of Linear Regression using Apache Spark's MLlib. The project demonstrates how to leverage Spark's powerful machine learning library to build predictive models efficiently at scale.

## Features
- **Data Preprocessing**: Handling missing values, feature scaling, and encoding categorical variables.
- **Model Training**: Utilizing Spark MLlib's `LinearRegression` to train a model.
- **Model Evaluation**: Assessing model performance using RMSE and R² metrics.
- **Hyperparameter Tuning**: Optimizing model parameters to improve accuracy.
- **Scalability**: Running on distributed computing environments using Spark.

## Installation
To run this project, you need to have Apache Spark installed. You can install it via:
```bash
pip install pyspark
```

## Usage
Run the following command to execute the regression analysis:
```bash
spark-submit lbb_regression.py
```
Ensure that your Spark environment is properly set up before running the script.

## Dataset
The dataset used in this project consists of multiple numerical and categorical features, which are preprocessed before being fed into the regression model.

## Results
The model's performance is evaluated using:
- **Root Mean Square Error (RMSE)**
- **R² Score**

## Contributions
Feel free to fork this repository and contribute improvements. Pull requests are welcome!

## Author
Developed by Siti Nurul Azizah

