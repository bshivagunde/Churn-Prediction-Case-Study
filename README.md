# Churn Prediction Case Study

## Problem Statement
In this Kaggle competition, the objective is to build machine learning models to predict customer churn. The predictive models will serve two main purposes:

### 1. Churn Prediction: 
- Develop a model to predict whether a high-value customer will churn in the near future. This information can be crucial for the company to take proactive steps such as offering special plans or discounts on recharge to retain valuable customers.

### 2. Variable Identification: 
- Build a model to identify important variables that act as strong predictors of churn. Understanding these variables may provide insights into why customers choose to switch to other networks.

While overall accuracy is the primary evaluation metric, it is essential to consider other metrics like precision, recall, etc., based on different business objectives. For example, one business goal might be to identify churned customers with higher accuracy. Strategies for managing customer churn should be recommended based on the observations.

## General Information

### 1. Data Understanding, Preparation, and Pre-Processing
- **Data Understanding:** Explore and identify potentially useful and non-useful attributes. Evaluate variable importance and estimate their impact.

- **Data Preparation:** Clean the data by handling missing values, removing outliers, and standardizing columns (e.g., date) into a consistent format.

### 2. Exploratory Data Analysis (EDA)
- **Preliminary Data Analysis:** Perform basic analysis, including correlation between variables and scatter plots to identify relationships.

- **Advanced Data Analysis:** Use visualizations like heatmaps, histograms, and basic clustering to uncover patterns in the data.

### 3. Feature Engineering and Variable Transformation
- **Feature Engineering:** Create new potentially useful variables through methods such as deriving the day from the date.

- **Variable Transformation:** Apply transformations to convert categorical variables into numerical data and scale numerical variables.

### 4. Model Selection, Building, and Prediction
- **Identify the Problem Type:** Determine whether it's a classification problem and list potential models.

- **Model Building:** Choose a training mechanism (e.g., cross-validation) and tune hyperparameters for each model.

- **Model Evaluation:** Test each model using relevant evaluation metrics and choose the best model based on dataset fit and output variable.

- **Ensemble Methods:** Explore ensemble options to improve model efficacy based on the specified evaluation metric.



### Data Used
- **Data File:** The Dataset Used for this Project is provided by Kaggle in the form of '.csv' file
- **Data Description:** 69999 Rows, 172 Columns
- **Years Covered:** 2006 and 2008


## Technologies Used
- numpy - version 1.23.5
- pandas - version 1.5.3
- matplotlib - version 3.7.1
- seaborn - version 0.12
- sklearn - version 1.2.2

## Acknowledgements
This project was conducted by Mr. B. M. Shivagunde.

## Contact
Created by [@bshivagunde](https://github.com/bshivagunde) - Feel free to contact me!
