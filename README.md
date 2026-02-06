## Urban Pluvial Flood Risk Prediction System (ML Notebook)

This repository contains the **machine learning analysis and model development** for an Urban Flood Risk Prediction System. The work was carried out using Jupyter Notebook for data preprocessing, feature engineering, and model training.

> Note: The interactive Streamlit GUI demonstrated in our exhibition is **not included in this repository**. This repo focuses on the data science and modeling component.

---

## Project Objective  
To predict high-risk urban flood zones using machine learning so that planners and policymakers can take preventive measures before disasters occur.

---

##  Dataset  
The model was trained using data from:
- **2,963 urban segments**
- **77 cities**
- **6 continents**

The dataset includes features related to rainfall, elevation, drainage, and urban infrastructure.

---

##  Machine Learning Model  
We trained a **Random Forest Classifier** with the following performance:

-  **92.75% Test Accuracy**
-  **89% Recall for high-risk areas**

This ensures that fewer dangerous locations are mistakenly classified as safe.

---

##  Feature Engineering  
We created new features such as:
- Drainage efficiency  
- Rainfall pressure on low elevation  
- Elevation–drainage interaction  

These engineered features contributed about **55%** of the model’s predictive power.

---



