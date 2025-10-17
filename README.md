#  Tsunami Classification Project

## Overview
This project focuses on building a machine learning model to classify tsunami occurrences based on historical data.  
The dataset was collected from publicly available online sources and contains **782 records** covering the years **2001 to 2022**.

- **Total records:** 782  
- **No Tsunami:** 478 records  
- **Tsunami:** 304 records
- **Data RangeYears Covered:** 2001 – 2022

The goal of this project is to accurately predict whether a tsunami event occurred based on various input features.


---

## Project Pipeline

1. **Dataset Download** – Acquired from publicly available online sources.  
2. **Loading Dataset** – Imported into the environment using `pandas`.  
3. **Preprocessing** – Handling missing values, encoding categorical variables, and normalizing data using `scikit learn`
4. **Feature Standardization** – Standardizing the features for consistent scaling using `scikit learn`.  
5. **Data Splitting** – Dividing the dataset into training and testing sets using `scikit learn`.  
6. **Model Training** – Implemented two models:
   - Random Forest Classifier  
   - Logistic Regression  
7. **Model Evaluation** – Evaluated using accuracy and F1 scores using `scikit learn`.
8. **Result Visualization** - Graphical Visualization for  Correlation between features and Confusion matrix using `seaborn` and `matplotlib`.

---

## Results

| Model | Accuracy | F1 (No Tsunami) | F1 (Tsunami) |
|--------|-----------|----------------|--------------|
| **Random Forest** | **91%** | **93** | **91** |
| **Logistic Regression** | 84% | 86 | 83 |

The **Random Forest Classifier** outperformed the Logistic Regression model, providing higher accuracy and balanced F1 scores for both classes.

---

## Improvement Opportunities

- Explore **feature engineering** to extract more meaningful or deeper features.  
- Experiment with **different model architectures** (e.g., XGBoost, SVM).  
- Perform **hyperparameter tuning** for optimal performance.  
- Incorporate **additional data sources** to improve generalization.

---


