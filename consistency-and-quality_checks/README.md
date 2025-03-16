Part 3: Data Consistency and Quality Checks
Objective: Ensure that the preprocessed dataset is clean, structured, and machine learning-ready.

Tasks:
Data Integrity Checks:
Check for duplicate entries.
Ensure all categorical values are correctly mapped.
Validate that all customer transactions match a valid social profile.
Statistical Summarization:
Generate describe() reports for all numerical columns.
Visualize the distribution of transaction amounts before and after augmentation.
Feature Selection for Machine Learning:
Identify highly correlated features using a correlation heatmap.
Select the top 10 most important features using a feature selection algorithm.
Final Data Export:
Save the final dataset as final_dataset_ready_[groupNumber].csv.

Bonus Challenge (Extra Points)
Apply a Machine Learning Model to Predict Customer Spending

Use the final preprocessed dataset to train a simple machine learning model (Linear Regression, Random Forest, or XGBoost).
Predict customer spending behavior based on merged data.
