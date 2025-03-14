# Data Augmentation for Customer Transactions

## Overview
This project enhances customer transaction data through cleaning and augmentation techniques to improve dataset quality, balance, and generate synthetic transactions. The final dataset is saved as `customer_transactions_augmented.csv`.

## Steps Followed

### 1. Load the Dataset
- Loaded `customer_transactions.csv` into a Pandas DataFrame.
- Displayed initial rows to examine data structure.

### 2. Data Cleaning & Missing Values
- Checked for missing data.
- Filled missing values:
  - **Numerical columns**: Mean imputation.
  - **Categorical columns**: Mode imputation.
- Verified missing values were handled.

### 3. Data Augmentation

#### 3.1 Adding Random Noise
- Added random noise to `purchase_amount` to simulate variation.

#### 3.2 Balancing with SMOTE
- Used **SMOTE** to balance the dataset if class imbalance was detected.

#### 3.3 Feature Transformation
- Applied **log transformation** to `purchase_amount` to reduce skewness.

#### 3.4 Generating Synthetic Transactions
- Created synthetic transactions by sampling with replacement and adding noise.
- Merged synthetic data with the original dataset.

### 4. Export Augmented Data
- Saved the augmented dataset as `customer_transactions_augmented.csv`.

## Final Output
- The augmented dataset includes both original and synthetic data, with better balance and transformations.

## Tools & Libraries Used
- **Python**
- **Pandas** (for data handling)
- **NumPy** (for noise addition)
- **imblearn (SMOTE)** (for dataset balancing)

## Notes
- Install dependencies before running:
  ```bash
  pip install pandas numpy imbalanced-learn
                    