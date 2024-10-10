# ChurnPrediction
Data Science Challenge for Churn Prediction

## Summary
The data science challenge from Coursera helped me understand how to improve real-world data by processing it effectively before modeling and applying machine learning algorithms.

## Solution
I started by examining the data characteristics, specifically the data types of each feature, checking for missing data, and preparing the data for training. Since the data was imbalanced, which could lead to bias in the model's learning, I balanced the dataset first. With too many features, I needed to select only the most relevant ones. Then, I proceeded to choose the appropriate algorithm to train the model, aiming to achieve a satisfactory accuracy rate.


## Approach
- **Step 1: Clean and Explore Data**

  - Clean the dataset by handling missing values, correcting data types, and eliminating outliers.
  - Perform exploratory data analysis (EDA) to understand the distribution of features, correlations, and target variable (churn).

- **Step 2: Pre-process Data and Balance for Training**

  - Handle class imbalance by resampling the minority class (oversampling or undersampling).
  - Normalize using ```MinMaxScaler()``` numerical features as needed.
  - Convert categorical variables into numerical representations using one-hot encoding.

- **Step 3: Feature Selection**

  - Identify the most relevant features that impact customer churn through techniques such as:
Correlation analysis.
  - Feature importance from models
    
**Step 4: Create the Model**
  - Create Model using LogisticRegression algorithms
    
    ``` lr = LogisticRegression()```
    
**Step 5: Submit the Assignment**

- Generate predictions and evaluate the model using the AUC score to determine the model's effectiveness.
