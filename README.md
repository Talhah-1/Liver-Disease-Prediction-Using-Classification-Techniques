# Liver Disease Classification Project

This repository contains the code and data on predicting liver disease using classification techniques in Python 3.12.7 through Jupyter Notebook.

The models include:
- Logistic Regression
- Decision Tree
- Random Forest
- Naïve Bayes
- XGBoost

Feature selection, hyperparameter tuning (for Random Forest and XGBoost), and three ensemble models are created and evaluated.

## Project Structure

```
Liver-Disease-Classification-Project/
│
├── Data/
│   ├── indian_liver_patient.csv
│   └── indian_liver_patient_clean.csv
│
├── Models/
│   ├── 1. Soft Voting Liver Ensemble (Default LR, Tuned RF, Tuned XGBoost).pkl
│   ├── 2. Soft Voting Liver Ensemble (Default LR, Default RF, Default XGBoost).pkl
│   └── 3. Hard Voting Liver Ensemble (Default LR, Default RF, Default XGBoost).pkl
│
├── Notebooks/
│   ├── Model_Development.ipynb
│   └── Ensemble_Model_Testing.ipynb
│
└── README.md
```

## Dataset

- Original File: `indian_liver_patient.csv`  
  Raw dataset downloaded from the UCI Machine Learning Repository.  
  Contains 583 records with some missing values and unbalanced labels.

- Cleaned File: `indian_liver_patient_clean.csv`  
  Preprocessed version used in this project.  
  Outliers removed and missing values imputed. Label encoding is applied to prepare data for classification.

## How to Run

1. Download the ZIP file from GitHub, ensure that the ZIP file is saved to your "Downloads" folder

2. In your "Downloads" folder, extract the ZIP file in the same location.

3. Launch Jupyter Lab or Jupyter Notebook.

4. In Jupyter, navigate to the "Downloads" folder and access the "Liver-Disease-Classification-Project" then access the "Notebooks" folder, you will see 3 notebooks.

5. Open and run the following notebooks from the first cell:
   - `Model_Development.ipynb`
   - `Ensemble_Model_Testing.ipynb`

There is no need to clean the dataset. All necessary libraries are imported at the top of each notebook.

## Python Version

- Developed and tested with **Python 3.12.7**

## Notes

- You do not need to process the raw file as `indian_liver_patient_clean.csv` is ready to use.
- The `Models/` folder already contains trained ensemble `.pkl` files used in testing.

## Author

Talhah Altafi
=======
