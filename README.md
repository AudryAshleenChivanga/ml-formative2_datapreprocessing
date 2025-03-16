# Customer Data Processing & Feature Engineering

## Overview
 The goal is to augment, merge, and enhance the data while ensuring consistency in a machine learning pipeline.

## Folder Structure
```
📂 project_root/
├── 📂 notebooks/                  # Jupyter notebooks for merging and feature engineering
│   ├── task_2_merge.ipynb       # Notebook for dataset merging
│   ├── feature_engineering.ipynb # Notebook for feature engineering
│
├── 📂 initial_dataset/           # Raw datasets provided
│   ├── customer_transactions_augmented.csv
│   ├── customer_social_profiles.csv
│   ├── id_mapping.csv
│
├── 📂 derived_datasets/  
|   ├── customer_transactions_augmented.csv       # Processed datasets
│   ├── merged_customer_data.csv  # Output after merging
│   ├── final_customer_data.csv   # Feature-engineered dataset
│
├── 📂 models/                    # Machine learning models from the bonus challenge
│
├── README.md                     # Documentation
```

## Setup & Execution
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install pandas numpy scikit-learn jupyter
```

### Running the Notebooks
1. Navigate to the `notebook/` folder.
2. Open the Jupyter notebooks using:
   ```bash
   jupyter notebook
   ```
3. Run `task_2_merge.ipynb` to merge datasets.
4. Run `feature_engineering.ipynb` to generate engineered features.

## Video Walkthrough & Documentation
- **Document Link:** [Insert Link Here]
- **Video Walkthrough:** [Insert Video Link Here]



