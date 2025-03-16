# Machine Learning Data Preprocessing Pipeline

## Overview
This project demonstrates a complete data preprocessing pipeline suitable for a real-world machine learning project, including data augmentation, merging datasets using transitive properties, feature engineering, data consistency checks, and predictive modeling using Linear Regression and Random Forest algorithms.

## Project Structure

```
├── datasets/
│   ├── customer_transactions.csv
│   ├── customer_social_profiles.csv
│   ├── id_mapping.csv
│   ├── customer_transactions_augmented.csv
│   ├── final_customer_data_group15.csv
│   └── final_dataset_ready_group15.csv
├── notebooks/
│   ├── Part_1_Data_Augmentation.ipynb
│   ├── Part_2_Data_Merging_Feature_Engineering.ipynb
│   └── Part_3_Data_Consistency_and_ML_Modeling.ipynb
├── models/
│   ├── linear_regression_model.pkl
│   └── random_forest_model.pkl
├── README.md
└── REPORT.pdf
```

## Steps and Tasks Completed

### Part 1: Data Augmentation
- Handled missing values through mean imputation.
- Applied log transformation to normalize skewed data.
- Generated synthetic data by adding random noise to numeric columns.
- Expanded dataset to double the size to improve model training.

### Part 2: Data Merging and Feature Engineering
- Merged augmented transactions and social profiles datasets via transitive ID mappings.
- Created engineered features such as Customer Engagement Score and Transaction Moving Averages.
- Handled inconsistencies and missing mappings effectively.

### Part 3: Data Consistency, Quality Checks, and Machine Learning
- Conducted data integrity checks, identified and removed duplicates.
- Performed categorical and numerical data consistency validations.
- Visualized data distributions and correlations.
- Trained and evaluated predictive models:
  - **Linear Regression**: RMSE ~ 0, R² = 1.0
  - **Random Forest**: RMSE = 0.44, R² ≈ 1.0

## Bonus Task
- Implemented Linear Regression and Random Forest Regression models.
- Achieved high predictive accuracy, validated by performance metrics.

## Instructions to Run the Project

### Step 1: Environment Setup
Install necessary libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 2: Running Notebooks
Use Google Colab or Jupyter Notebooks:
- Open and sequentially execute each notebook in the `/notebooks` directory.

### Step 3: Model Usage
Models saved in `/models` can be loaded and used for predictions:

```python
import joblib

# Load Random Forest Model
rf_model = joblib.load('models/random_forest_model.pkl')

# Make a prediction
sample_input = [[4.5, 85, 4.7, 31.4, 300]]
prediction = rf_model.predict(sample_input)
print(prediction)
```

## Contributions
| Team Member | Contribution |
|-------------|--------------|
| Member 1    | Data augmentation, cleaning, merging datasets |
| Member 2    | Feature engineering, consistency checks |
| Member 3    | Machine learning modeling and evaluation |

## References
- All resources used in this assignment are cited in the provided report according to IEEE citation standards.

## Contact
For any questions or issues regarding this project, please contact [your contact information].

