# **Bankruptcy Prediction Model**

## **Overview**
This project focuses on developing a machine learning model to predict the bankruptcy of companies based on financial data. Utilizing a dataset encompassing over 6800 companies with detailed financial ratios, the model aims to discern patterns that indicate potential bankruptcy.

## **Dataset**
The dataset includes financial data from 1999 to 2000, covering 6819 companies and 95 financial ratios. Each company is labeled with '1' (bankrupt) or '0' (not bankrupt), based on their bankruptcy status.

## **Features and Analysis**
Key Features: 95 financial ratios (X1-X95), including 'Debt Ratio %', 'Current Liability To Assets', and 'Current Liability To Current Assets'.

Analysis Insights: Identification of critical financial indicators that are significantly higher in bankrupt organizations.

Correlation Study: Exploration of relationships between various financial ratios and bankruptcy status.

## **Data Preprocessing**
The raw data underwent extensive preprocessing, including cleaning, transformation, and dimensionality reduction, using libraries like Pandas and NumPy.
The dataset was split into training and testing sets (80-20 ratio) to evaluate the model's performance on unseen data.

## **Model Development and Performance**
A Logistic Regression model was developed to predict bankruptcy.
The model achieved an accuracy of 96.13%, demonstrating its effectiveness in predicting bankruptcy.

## **Repository Contents**
Jupyter Notebooks detailing the data analysis and model building process.
CSV files containing the cleaned and preprocessed dataset.
Documentation on the methodology and findings.

## **How to Use**
Clone or download this repository.
Install the required Python libraries (Pandas, NumPy, scikit-learn).
Run the Jupyter Notebooks to replicate the analysis or to apply the model to new data.

## **Requirements**
Python 3 

Pandas 

NumPy 

scikit-learn 
