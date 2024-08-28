# Data-Science-Project
## Overview
This project applies machine learning techniques to predict the risk of heart disease in diabetic patients by analyzing their clinical and demographic data. The goal is to assist healthcare professionals in identifying high-risk patients early, enabling better treatment planning and improving patient outcomes.
### Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Datasets](#datasets)
- [Dependencies](#dependencies)
- [Contact](#contact)
### Project Structure
~~~
├── data/
│   ├── raw/                      # Raw dataset files
│   ├── processed/                # Processed and cleaned datasets
│   └── ...
├── notebooks/
│   ├── data_preprocessing.ipynb  # Data cleaning and preprocessing steps
│   ├── pca_analysis.ipynb        # Principal Component Analysis (PCA)
│   ├── model_training.ipynb      # Model training and evaluation
│   └── model_evaluation.ipynb    # Model evaluation and risk score analysis
├── src/
│   ├── data_processing.py        # Scripts for data processing
│   ├── model.py                  # Scripts for model training and prediction
│   └── utils.py                  # Utility functions for the project
├── tests/                        # Test cases for the project
├── README.md                     # Project overview and instructions (this file)
├── requirements.txt              # List of required Python libraries
└── ...
~~~
### Usage

- **Data Preprocessing:** Run the data preprocessing notebook to clean and prepare the data.
  - [notebooks/data_preprocessing.ipynb]
- **Principle Component Analysis:** Perform PCA to understand the data and identify important features.
  - [notebooks/exploratory_analysis.ipynb]

- ### Model Training
Train various machine learning models using the prepared dataset. The models include Logistic Regression, Random Forest, and K-Nearest Neighbors. This step also involves applying SMOTE to balance the dataset and scaling the features for better model performance.
- Notebook: `notebooks/model_training.ipynb`

### Model Evaluation & Risk Score Calculation
Evaluate the trained models using various metrics and calculate a risk score for heart disease. The risk score is derived from a Logistic Regression model and normalized for comparison. This step also includes plotting the predicted vs. actual risk scores to visually assess the models' performance.
- Notebook: `notebooks/model_evaluation.ipynb`

### Prediction
Use the trained models to predict heart disease risk on new data. Refer to `src/model.py` for the prediction scripts, which include functions for making predictions using the trained models.

### Datasets

- **Description:** The dataset used in this project contains clinical and demographic data of diabetic patients.
- **Source:** [https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset]

- **Structure:** 
  - **Features:** diabetes _ 012 _ health _ indicators _ BRFSS2015.csv is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_012 has 3 classes. 0 is for no diabetes or only during pregnancy, 1 is for prediabetes, and 2 is for diabetes. There is a class imbalance in this dataset. This dataset has 21 feature variables (Diabetes_012 is 0 = no diabetes 1 = prediabetes 2 = diabetes, high BP, high cholesterol, CholCHeck is 0 = no cholesterol check in 5 years 1 = yes cholesterol check in 5 years Smoker is Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] 0 = no 1 = yes, Stroke is (Ever told) you had a stroke. 0 = no 1 = yes, HeartDiseaseorAttack is coronary heart disease (CHD) or myocardial infarction (MI), PhysActivity is physical activity in past 30 days - not including job, having Fruits, etc).
  - **Target Variable:** .

### Dependencies

- **Python:**
- **Libraries:**
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `imblearn` (for SMOTE)
- `jupyter`
    
### Contact
- **Name:** AKHIL NAZIM
- **Email:** akhilnka@gmail.com
- **GitHub:** https://github.com/akhilnazim0/Data-Science-Project.git


