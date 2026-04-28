# 🧠 Population Health Intelligence System

## 📌 Overview
This project presents an AI-driven population health intelligence system designed to analyze demographic and behavioral data in order to identify obesity risk patterns across different population groups.

The solution transforms raw health survey data into structured insights that support data-informed decision-making in public health and policy development.

---

## 📌 Problem Statement
Can population-level health data be leveraged to accurately identify groups at high risk of obesity and uncover underlying demographic patterns?

---

## 📌 Dataset
- Source: Behavioral Risk Factor Surveillance System (BRFSS-style dataset)  
- Features: Geographic location, year, demographic segments, obesity prevalence metrics  
- Target Variable: Obesity Risk (Binary Classification — High Risk vs Low Risk)  

---

## 📌 Methodology
The project follows a structured end-to-end machine learning workflow:

1. Data Cleaning and Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering and Encoding  
4. Model Development (Random Forest Classifier)  
5. Model Evaluation and Validation  
6. Feature Importance Analysis  

---

## 📌 Model Performance
- Model Used: Random Forest Classifier  
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score  
- Validation Tools: Confusion Matrix, Classification Report  

The model demonstrates the ability to distinguish between high-risk and low-risk population groups based on observable patterns in the data.

---

## 📌 Key Insights
- Obesity risk exhibits clear variation across geographic regions  
- Demographic characteristics significantly influence risk distribution  
- Certain population segments consistently show elevated risk levels  
- Data-driven segmentation enables targeted public health interventions  

  ---

  ## 📌 Visual Insights

### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

### Feature Importance
![Feature Importance](feature_importance.png)

---

## 📌 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📌 Limitations
- The dataset represents aggregated population data rather than individual-level records  
- Risk classification is derived from threshold-based labeling, which simplifies real-world complexity  
- External behavioral factors (e.g., diet, physical activity) are not directly captured  

---

## 📌 Future Improvements
- Integrate individual-level health datasets for more granular predictions  
- Apply advanced models such as XGBoost or Gradient Boosting  
- Deploy the system as an interactive web application using Streamlit or Flask  
- Incorporate additional behavioral and lifestyle features for improved accuracy  

---

## 📌 Author
Daniella Edeh  
Data Scientist 
