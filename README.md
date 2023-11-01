# Insurance Churn Machine Learning Case Study
This repository contains the implementation and evaluation of a machine learning case study by Harvey Allen. The study involves data exploration, data pre-processing, and model evaluation. Here's a summary of the key components of the project:

## Data Exploration
Exploratory data analysis (EDA) is used to analyze the dataset, uncover underlying patterns, identify anomalies, and test hypotheses. Key techniques used in this phase include:

- **Violin Plots and Box Plots**: These are used to visualize the distribution of numerical data for each target category, exposing outliers.

- **Grouped Bar Charts**: Show the distribution of categorical features by target variables.

- **Correlation Heat Map**: Visualizes the strength of relationships between numeric features.

## Data Pre-processing
Pre-processing involves cleaning, transforming, and organizing the data for modeling. Key steps in this phase include:

- **Value Manipulation**: Data type changes to align numeric and categorical features.

- **Missing Value Handling**: Imputation methods for missing values.

- **Data Scaling**: Robust Scaling and Standard Scaling to preprocess numerical data.

- **One-Hot Encoding**: Used for categorical data.

- **Data Reduction**: Removing unnecessary features to reduce dimensionality.

## Model Evaluation and Implementation
The project evaluates three classification models:

- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Decision Tree Classification**

Key performance metrics used for evaluation include accuracy, precision, recall, and F1-score. Cross-validation and hyperparameter optimization are also employed to enhance model performance.

The optimal model selected for this classification problem is the **Support Vector Machine (SVM)**, which demonstrated strong performance metrics.

## Results Analysis and Discussion
The SVM model achieved an accuracy of 0.708 and a balanced F1 score of 0.742. However, there is room for improvement, especially in terms of recall-precision balance. Further exploration of classification thresholds, kernel functions, and additional features may enhance the model's performance.

## Bibliography
Zhang, C. 2013. Challenges in machine learning
Jakkula, V. 2006. Tutorial on Support Vector Machine (SVM)
