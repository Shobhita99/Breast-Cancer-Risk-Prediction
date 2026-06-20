# Breast Cancer Survival Prediction Using Machine Learning

## Overview

This project predicts the **10-year survival risk of breast cancer patients** using the **METABRIC dataset**. It combines **Survival Analysis** and **Machine Learning** techniques to identify important clinical factors affecting patient outcomes and build predictive models.

---

## Objectives

* Analyze factors affecting breast cancer survival.
* Estimate patient survival probability.
* Predict whether a patient is likely to die within 10 years of diagnosis.
* Compare different machine learning models and select the best-performing model.

---

## Dataset

**Dataset:** Breast Cancer METABRIC Dataset

The dataset contains clinical and survival-related information such as:

* Age at Diagnosis
* Tumor Size
* Tumor Stage
* ER Status
* HER2 Status
* Menopausal Status
* Treatment Information
* Overall Survival Time
* Survival Status

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Lifelines
* Statsmodels
* Power BI
* Jupyter Notebook

---

## Methodology

### Data Preprocessing

* Removed unnecessary columns
* Handled missing values
* Applied log transformation to skewed features
* Encoded categorical variables
* Scaled numerical features

### Survival Analysis

* Kaplan-Meier Survival Curve
* Cox Proportional Hazards Model
* Hazard Ratio Analysis

### Machine Learning Models

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

### Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

---

## Results

* Compared multiple machine learning models.
* Random Forest achieved the best overall performance.
* Identified key clinical factors influencing patient survival.
* Developed an interactive prediction system for patient risk assessment.

---

## Power BI Dashboard

The project includes a Power BI dashboard to visualize:

* Patient demographics
* Survival trends
* Tumor characteristics
* Treatment analysis
* Mortality risk insights

---

## Project Files

```text
Breast-Cancer-Survival-Prediction/
│
├── Breast Cancer METABRIC.csv
├── Breast_Cancer_Survival_Prediction.ipynb
├── Breast_Cancer_Dashboard.pbix
├── Breast_Cancer_Presentation.pptx
├── README.md
└── requirements.txt
```

## Future Improvements

* Deploy using Streamlit
* Implement XGBoost and LightGBM
* Include genomic features
* Build a real-time prediction application

---

## Author

**Shobhita Sisodia**

B.Tech Biotechnology | Data Analytics & Machine Learning Enthusiast
