# Starbucks Capstone Project
The Starbucks Capstone Project, which is part of the Udacity Data Science Nanodegree program, can be accessed through this [link](https://www.udacity.com/school-of-data-science).


![alt text](https://github.com/eisbilen/Starbucks-Capstone-Project/blob/main/hans-vivek-gfLlvYFD7NE-unsplash.jpg)
Photo by <a href="https://unsplash.com/@oneshotespresso?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Hans Vivek</a> on <a href="https://unsplash.com/photos/gfLlvYFD7NE?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>  

## Project Overview

## Problem Statement

## Motivation

The primary objective of this project is to establish a robust and reliable model that enables the generation of engaging promotional offers tailored to the customers of any organization, such as Starbucks.



## Resources


The project comprises various resources in file format, including the followings:

The analysis, cleaning, data exploration, and model construction based on the dataset generated from the preceding steps are organized into two files that need to be executed in the specified sequence:

#### Jupyter Notebooks

`Starbucks_Capstone_Project_PreProsessing.ipynb`

`Starbucks_Capstone_Project_Models.ipynb`

#### Datasets
Datasets (provided by Udacity) used for this project are the following:

data/`portfolio.json`: containing offer ids and meta data about each offer (duration, type, etc.)

data/`transcript.json`: records for transactions, offers received, offers viewed, and offers completed

data/`profile.json`: demographic data for each customer


Through the process of data wrangling and feature engineering, two distinct datasets are generated as a result:

data/`portfolio_cleaned.csv`: processed information related to initial portfolio dataset

data/`combined_data.json`: dataset prepared and built in the first notebook with the objective of building the classification models

## Libraries

* [Pandas: An open source data analysis and manipulation tool](https://pandas.pydata.org/)

* [Numpy: The fundamental package for scientific computing with Python](http://www.numpy.org/)

* [Matplotlib: comprehensive library for creating static, animated, and interactive visualizations in Python](https://matplotlib.org/)

* [seaborn: Statistical Data Visualization](https://seaborn.pydata.org/)

* [re: Regular expression operations](https://docs.python.org/3/library/re.html)

* [scikit-learn: Machine Learning in Python](https://scikit-learn.org/stable/)

## Summary analysis

In order to identify the optimal model, three distinct supervised classification algorithms have been employed:

* Logistic Regression
* Gradient Boosting
* Random Forest

Metrics outcome:

|                 | Log. Regression | Gradient Boosting | Random Forest  |
| -------------   |:---------------:| -----------------:| --------------:|
| accuracy        |    0.698        |     0.726         |     0.734      |
| f1score         |    0.694        |     0.725         |     0.729      |
| precission      | 0.667           | 0.691             |    0.707       |
| recall          | 0.725           | 0.763             |    0.749       |

## 

For further information, please refer to [my technical article](https://erdemisbilen.medium.com/b32b77dcf9b8?sk=3c56192b9942f3e642aae70dddcc86f5)  published on Medium.
