# Simple Linear Regression

## Overview

This project demonstrates the implementation of Simple Linear Regression using Python and the scikit-learn library. Simple Linear Regression is a basic machine learning algorithm used for predicting a dependent variable based on a single independent variable.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Description

The project uses a dataset (`Salary_Data.csv`) to predict salary based on years of experience. It includes the following steps:

1. **Importing Libraries:** Numpy, Matplotlib, and Pandas are imported to handle data and visualization.

2. **Importing Dataset:** The project reads the dataset and separates the independent variable (`x`: years of experience) and dependent variable (`y`: salary).

3. **Splitting Dataset:** The dataset is divided into training and test sets using `train_test_split` from scikit-learn.

4. **Training Model:** The Simple Linear Regression model is trained on the training set using scikit-learn's `LinearRegression`.

5. **Predictions:** The model predicts the salaries on the test set, and the results are visualized.
## Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/repoabhi-git/simple-linear-regression.git
Install the required libraries:

bash
Copy code
pip install numpy matplotlib pandas scikit-learn
Run the Python script:

bash
Copy code
python your_script_name.py
Usage
Modify the script as needed or use it as a template for your own Simple Linear Regression tasks. Ensure that you have a dataset in the same format as Salary_Data.csv for training and testing.

##Results
The project visualizes the training set and test set results using Matplotlib. The scatter plots and regression lines provide insights into the relationship between years of experience and salary.
