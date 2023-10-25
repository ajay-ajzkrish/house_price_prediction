# House_rent_prediction_Regression

## Introduction

Welcome to my Data Science ! 

## Milestones

### Step 1: Data Preparation

- **Read the Dataset**: I started by loading the dataset, which contained information about various properties and their rent prices.

- **Exploratory Data Analysis (EDA)**: I performed EDA to gain insights into the dataset. This included data visualization, summary statistics, and identifying patterns in the data.

- **Data Insights**: EDA revealed valuable insights about the dataset, such as the distribution of rent prices, correlations between features, and potential outliers.

### Step 2: Base Model - Linear Regression

- **Base Model**: Initially, I implemented a basic Linear Regression model to establish a baseline for prediction.

- **Accuracy**: The base Linear Regression model achieved an accuracy of 67%, which served as a starting point for improvement.

### Step 3: Feature Engineering

- **Feature Engineering**: To enhance the model's predictive power, I performed feature engineering. This involved creating new features, encoding categorical variables, and addressing outliers through capping.

### Step 4: Model Selection and Tuning

I explored various regression models and optimization techniques to improve prediction accuracy.

- **Linear Regression, Lasso, Ridge, ElasticNet**: I experimented with these linear regression variants.

- **GridsearchCV**: Hyperparameter tuning was carried out using GridsearchCV to find the optimal hyperparameters.

- **SequentialFeatureSelector**: This technique helped in selecting the best combination of features.

- **Recursive Feature Elimination (RFE)**: RFE helped identify the most important features.

- **Leave-One-Out (LOO)** and **K-Fold Cross-Validation**: Cross-validation methods were used to ensure the models' robustness.

- **RandomForestRegressor**: Finally, I trained a RandomForestRegressor model, which showed remarkable promise.

### Step 5: Model Evaluation

- **Best Features**: The models helped identify the most important features for prediction.

- **RandomForestRegressor**: This model emerged as the winner, achieving an impressive accuracy of 99%.

- **Root Mean Squared Error (RMSE)**: The RMSE for the RandomForestRegressor model was 186623, indicating the model's strong predictive performance.

## Conclusion

This Data Science Challenge journey has been an incredible learning experience. Starting with a basic Linear Regression model and gradually incorporating feature engineering and advanced regression techniques, we achieved a remarkable accuracy .

