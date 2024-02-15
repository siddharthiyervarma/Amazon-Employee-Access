 ## Predicting Amazon Employee Access needs given thier Role and position using Catboost 
Project Overview:
Description:

In this project, the goal is to develop a machine learning model that can accurately predict the access requirements for Amazon employees based on their assigned roles and positions within the company. Access management is crucial for maintaining security and ensuring that employees have the appropriate permissions to perform their job responsibilities without granting unnecessary access.

The project utilizes the CatBoost algorithm, a gradient boosting library that excels in handling categorical features and is well-suited for classification tasks. The dataset for training the model would likely include information about employee roles, positions, historical access data, and potentially other relevant features.



## 🛠 Skills Used 
Machine Learning,
Data Cleaning and Processing,
Model Building,
Feature Engineering,
Data Visualization and
Model Evaluation


## Authors

- [@siddharthiyervarma](https://www.github.com/siddharthiyervarma)


## Roadmap
1. Data Processing:

Value Counts of Unique Columns: Understanding the distribution of unique values in each column provides insights into the diversity of the data. It's particularly useful for categorical columns, helping you identify potential issues like missing values or rare categories.
Understanding 'Action' Column: Recognizing the dependent variable is a critical step. In this case, 'Action' is identified as the dependent variable, indicating that it will be predicted by the model.

2. Visualization:

Displot of Features: Creating distribution plots (displot) for features can help visualize their distributions, identifying patterns, outliers, or skewness.

Box Plot: Box plots are useful for visualizing the distribution of numerical features and identifying outliers.

sns Heatmap: Seaborn (sns) heatmaps can reveal correlations between different features, assisting in understanding relationships and potential multicollinearity.

3. Model Building:

Dividing Data: Splitting the dataset into training and testing sets is crucial for evaluating the model's performance on unseen data.

Importing CatBoost: Importing the CatBoost library is a necessary step to leverage its functionalities for training the model.

Plotting a Tree: Visualizing a decision tree from the CatBoost model can provide insights into how the model is making decisions.

Getting Most Important Features: Identifying the most important features can help in feature selection and interpretation of the model.

Fixing Data Imbalance: Addressing data imbalance issues is essential for improving the model's performance, especially when dealing with a binary classification problem like predicting 'Action.'The Final Score of the CatBoost Model after Fixing the data Imbalance =94.5