# Starbucks Capstone Project
The Starbucks Capstone Project, which is part of the Udacity Data Science Nanodegree program, can be accessed through this [link](https://www.udacity.com/school-of-data-science).


![alt text](https://github.com/eisbilen/Starbucks-Capstone-Project/blob/main/hans-vivek-gfLlvYFD7NE-unsplash.jpg)
Photo by <a href="https://unsplash.com/@oneshotespresso?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Hans Vivek</a> on <a href="https://unsplash.com/photos/gfLlvYFD7NE?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>  

## Project Overview
This project focuses on identifying reward program offers that effectively engage Starbucks’ current customers and attract new ones.

Starbucks is a data-driven company that invests in obtaining a complete understanding of its customers by utilizing datasets containing customer information, special offers, and transaction data.

To develop a model capable of determining the success of a reward program, I divided the project into three phases:

Inspecting and cleaning the data provided by the Udacity.
Creating a dataset that combines all relevant information.
Building and evaluating the performance of three classification models to predict the success or failure of a reward program for a specific person.

## Problem Statement
Making a significant investment in a marketing campaign is a complex decision that requires approval from various stakeholders, financial resources, and time. Therefore, having a predictive model that can classify whether it is worthwhile to launch a particular offer for a specific target group becomes a strategic asset for any company.

In order to create this model, we will employ supervised learning techniques for binary classification.

The outcome of the model will indicate whether the offer is expected to be effective or not.

## Motivation

The primary objective of this project is to establish a robust and reliable model that enables the generation of engaging promotional offers tailored to the customers of any organization, such as Starbucks.



## Resources


The project comprises various resources in file format, including the followings:

The analysis, cleaning, data exploration, and model construction based on the dataset generated from the preceding steps are organized into one jupytre noteboo:

#### Jupyter Notebooks

`Starbucks_Capstone_Project_notebook.ipynb`


#### Datasets
Datasets (provided by Udacity) used for this project are the following:

data/`portfolio.json`: containing offer ids and meta data about each offer (duration, type, etc.)

data/`transcript.json`: records for transactions, offers received, offers viewed, and offers completed

data/`profile.json`: demographic data for each customer


Through the process of data wrangling and feature engineering, a combined dataset is generated as a result:

data/`combined_data.json`: dataset prepared and built in the notebook with the objective of building the classification models

## Libraries

* [Pandas: An open source data analysis and manipulation tool](https://pandas.pydata.org/)

* [Numpy: The fundamental package for scientific computing with Python](http://www.numpy.org/)

* [Matplotlib: comprehensive library for creating static, animated, and interactive visualizations in Python](https://matplotlib.org/)

* [seaborn: Statistical Data Visualization](https://seaborn.pydata.org/)

* [re: Regular expression operations](https://docs.python.org/3/library/re.html)

* [scikit-learn: Machine Learning in Python](https://scikit-learn.org/stable/)

## Acknowledgements
See below the resources, including websites, books or papers that have helped me to find solutions and develop this project.

* [datasets provided by Udacity/Starbucks](https://www.udacity.com/school-of-data-science)
  
* [scikit-learn: User Manual](https://scikit-learn.org/stable/user_guide.html)
  
* [Google: AUC-ROC curve](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc)
  
* [Hands-on ML with Scikit-Learn, Keras and Tensorflow by Aurélien Géron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)

## Summary analysis

In order to identify the optimal model, three distinct supervised classification algorithms have been employed:

* Logistic Regression
* Gradient Boosting
* Random Forest

Accuracy outcome of the inital models before fien tuning the hyper parameters:

|                 | Log. Regression | Gradient Boosting | Random Forest  |
| -------------   |:---------------:| -----------------:| --------------:|
| accuracy        |    0.692        |     0.703         |     0.702      |


Metrics outcome after fine tuning the hyperparameters:

|                 | Log. Regression | Gradient Boosting | Random Forest  |
| -------------   |:---------------:| -----------------:| --------------:|
| accuracy        |    0.693        |     0.703         |     0.704      |
| f1score         |    0.694        |     0.710         |     0.707      |
| precission      | 0.657           | 0.659             |    0.665       |
| recall          | 0.735           | 0.771             |    0.755       |

## 

For further information, please refer to [my technical article](https://erdemisbilen.medium.com/b32b77dcf9b8?sk=3c56192b9942f3e642aae70dddcc86f5)  published on Medium.
