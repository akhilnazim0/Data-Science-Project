# Data-Science-Project
## Overview
This project leverages machine learning to predict heart disease in diabetic patients by analyzing their clinical and demographic data. The goal is to develop a tool that assists doctors in identifying high-risk patients early, thereby improving their treatment plans and outcomes.

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
│ ├── raw/
│ ├── processed/
│ └── ...
├── notebooks/
│ ├── data_preprocessing.ipynb
│ ├── exploratory_analysis.ipynb
│ └── model_training.ipynb
├── src/
│ ├── data_processing.py
│ ├── model.py
│ └── utils.py
├── tests/
├── README.md
├── requirements.txt
└──
~~~
### Usage

- **Data Preprocessing:** Run the data preprocessing notebook to clean and prepare the data.
  - [notebooks/data_preprocessing.ipynb](notebooks/data_preprocessing.ipynb)

- **Principle Component Analysis:** Perform PCA to understand the data and identify important features.
  - [notebooks/exploratory_analysis.ipynb](notebooks/exploratory_analysis.ipynb)

- **Model Training:** Train the machine learning model using the prepared dataset.
  - [notebooks/model_training.ipynb](notebooks/model_training.ipynb)

- **Prediction:** Use the trained model to predict heart disease risk on new data. Refer to `src/model.py` for prediction scripts.
### Datasets

- **Description:** The dataset used in this project contains clinical and demographic data of diabetic patients.
- **Source:** [https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset]

- **Structure:** 
  - **Features:** diabetes _ 012 _ health _ indicators _ BRFSS2015.csv is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_012 has 3 classes. 0 is for no diabetes or only during pregnancy, 1 is for prediabetes, and 2 is for diabetes. There is a class imbalance in this dataset. This dataset has 21 feature variables (Diabetes_012 is 0 = no diabetes 1 = prediabetes 2 = diabetes, high BP, high cholesterol, CholCHeck is 0 = no cholesterol check in 5 years 1 = yes cholesterol check in 5 years Smoker is Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] 0 = no 1 = yes, Stroke is (Ever told) you had a stroke. 0 = no 1 = yes, HeartDiseaseorAttack is coronary heart disease (CHD) or myocardial infarction (MI), PhysActivity is physical activity in past 30 days - not including job, having Fruits, etc).
  - **Target Variable:** .

### Dependencies

- **Python:**
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - jupyter
    
### Contact
- **Name:** AKHIL NAZIM
- **Email:** akhilnka@gmail.com
- **GitHub:** https://github.com/akhilnazim0/Data-Science-Project.git


