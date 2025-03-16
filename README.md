# Customer Data Processing & Feature Engineering

## Overview
 The goal is to augment, merge, and enhance the data while ensuring consistency in a machine learning pipeline.

## Folder Structure
```
📂 project_root/
├── 📂 notebooks/                  # Jupyter notebooks for merging and feature engineering
│   ├── DataAugmentation.ipynb       # Notebook for dataset merging
│   ├── Merging_Datasets_with_Transitive_Properties.ipynb # Notebook for feature engineering
|   ├── Part3_Ml_and_Bonus_Colab.ipynb
│
├── 📂 initial_dataset/           # Raw datasets provided
│   ├── customer_transactions_augmented.csv
│   ├── customer_social_profiles.csv
│   ├── id_mapping.csv
│
├── 📂 derived_datasets/  
|   ├── customer_transactions_augmented.csv       # Processed datasets
│   ├── merged_customer_data.csv  # Output after merging
│   ├── final_customer_data_group15.csv   # Feature-engineered dataset
│                 
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
- **Document Link:** https://docs.google.com/document/d/1EvFQiVNZxP1QEkyiCeRiEzqeGiWneJyybneeH71aP5Y/edit?usp=sharing
- **Video Walkthrough:** https://vimeo.com/1066390812?share=copy




