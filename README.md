# Credit Risk Modeling
## Project: PD Modeling in Consumer Credit
SGH Big Data, Master's degree

Authors:
* Antoni Ballaun
* Laura Hoang
* Jędrzej Joniec
* Piotr Zambrzycki

This project was developed as part of the **"Credit Risk Modeling"** university course. Its main goal was to model **loan defaults** based on real-world loan data and to evaluate the performance of various predictive models.
Data: https://www.kaggle.com/datasets/henryokam/prosper-loan-data?resource=download
Report: https://drive.google.com/file/d/1KOXMnvp9_GyhhpnrUkVNrZK8ofxlpyf1/view?usp=sharing

### Project Overview

The workflow consisted of several stages:

1. **Data Preprocessing** – Cleaning and preparing the dataset for analysis.
2. **Variable Binning** – Discretizing continuous variables for better interpretability and model stability.
3. **Feature Selection** – Selecting key variables using **Information Value (IV)** and **L1 regularization**.
4. **Model Development** – Building and training four models:

   * Logistic Regression
   * Random Forest
   * XGBoost
   * Neural Network
5. **Model Evaluation** – Comparing models based on predictive performance metrics to identify the most effective approach.
6. **Financial Simulation** – Simulating the financial score under three different **LGD (Loss Given Default)** scenarios to assess risk sensitivity.
