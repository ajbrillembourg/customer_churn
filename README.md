# Bank Customer Churn
## Purdue University Krannert School of Management
## MGMT MGMT58600-B03: Python Programming

Contained herein is our final project for the Summer 2021 Python Programming course based on the Kaggle dataset for bank customer churn found [here](https://www.kaggle.com/sakshigoyal7/credit-card-customers).

## Outline
- Part 1 - Overview 
- Part 2 - Architecture
- Part 3 - Dependencies

## 1. Overview 
![Project Flowchart](https://github.com/ajbrillembourg/customer_churn/raw/main/Images/Project_flowchart.png)

As part of our Python Programming final project, we had the freedom to choose any topic and present a project after exploring the dataset. Since attrition/churn is a major concern both for companies internally and externally, we considered focusing on this topic to create a prediction model for customer churn. After doing some exploratory analysis, we identified independent variables that could have a more significant impact on customer churn and their relations. Then, we continued with some data pre-processing before constructing a model to derive some insights. We note that given the limitations of the data, this model might not be as accurate, but it allowed us to practice exploratory analysis, data pre-processing, and predictive model constructions using Python. 

The general business problem for the data set is the following: 
_A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction_.

## 2. Architeture

The exploratory analysis is contained in a separate Jupyter Notebook file from the data pre-processing and model Jupyter Notebook file. There is no app deployed, but the dataset is included for reproducibility. Most graphics were recreated in MS Excel mirroring graphics produced in Python with Matplotlib.

## 5. Dependencies:
```Python

library(pandas)
library(numpy)
library(matplotlib)
library(sklearn)
library(seaborn)

```

