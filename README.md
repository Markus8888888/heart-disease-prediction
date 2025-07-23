# Heart Disease Risk Prediction

### By Markus Chu

---

## Introduction
According to the World Health Organization, heart disease is still the leading cause of death globally, with over **17.9 million deaths per year**, which is about **32% of all global fatalities** (World Health Organization, 2021). Even with medical advancements like the use of AI, it is still hard to detect heart disease in its early stages. It is important to consider that traditional diagnostic methods rely on clinical assessments, tests, and imaging, which are time-consuming, expensive, and sometimes even inaccessible.

Using machine learning (ML) offers an approach to predict heart disease risk efficiently and cost-effectively. These predictive models can consider a variety of health factors to analyze patterns related to heart disease risk. This allows for earlier responses, such as potential lifestyle adjustments, medical treatment, or additional diagnostic testing.

---

## Objective

The goal of this project is to develop a supervised machine learning model to **predicts one's risk of getting heart disease** with patient data.

This project will:
1. Explore the heart disease dataset with EDA
2. Predict heart disease risk with binary classification (presence or absence of heart disease)
3. Identify key contributing factors of heart disease within the dataset
4. Find a baseline ML model with the greatest performance

Intended use cases:
1. Help doctors make early decisions
2. Let patients check their own health risks
3. Support research on how health risk factors work together

---

## Repository Structure

```
heart-disease-risk-prediction/
│
├── data/
│   ├── heart_disease.csv                     # Original dataset
│   ├── preprocessed_heart_disease.csv        # Cleaned and processed dataset
│   └── split_data/                           # Serialized train/test data
│       ├── x_train.pkl
│       ├── x_test.pkl
│       ├── y_train.pkl
│       └── y_test.pkl
│
├── models/
│   └── best_rf_model.pkl                     # Final trained Random Forest model
│
├── notebooks/                                # Jupyter notebooks for each project stage
│   ├── 1_exploratory_data_analysis.ipynb     # Exploratory Data Analysis (EDA)
│   ├── 2_data_preprocessing.ipynb            # Data cleaning and preprocessing
│   ├── 3_modeling.ipynb                      # Model training and tuning
│   └── 4_results_and_interpretation.ipynb    # Final results, evaluation and interpretation
│
├── .gitignore                                # Python dependencies
├── README.md                                 # Files/folders ignored by Git
└── requirements.txt                          # Project documentation
```

---

## Dataset Overview
The dataset is from Kaggle ("Heart Disease"), and contains multiple health indicators and lifestyle factors to assess heart disease risk.

Link to Dataset: https://www.kaggle.com/datasets/oktayrdeki/heart-disease

More details under **1_exploratory_data_analysis.ipynb** notebook

---

## Installation

Requirements:
- Python 3.11.0
- Recommended using a virtual environment

Clone the repo:  
```
git clone https://github.com/Markus8888888/Life-Expectancy-Project
```

Install pip packages:  
```
pip install -r requirements.txt
``` 

---

## Usage
Run notebooks in order:
1. 1_data_analysis_preprocessing.ipynb
2. 2_exploratory_analysis.ipynb
3. 3_modeling.ipynb (CHANGE ALL THIS LATER)

---

## Key Findings

---

## References
- Cardiovascular diseases (Cvds). (n.d.). Retrieved July 12, 2025, from https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)
- https://www.heart.org/en/health-topics/high-blood-pressure/understanding-blood-pressure-readings 

---