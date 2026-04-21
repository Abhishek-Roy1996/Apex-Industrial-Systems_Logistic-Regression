# 🧠 Manufacturing Defect Prediction

## Overview
Modern manufacturing systems (ERP, MES, QMS, SCADA) generate detailed production data. 
This project uses that data to identify factors driving defects and build a model to improve defect detection at Apex Industrial Systems.

## Objective
The primary goal of this project is to develop a Logistic Regression model to predict whether a manufactured unit is defective.

## Target Variable: `defect_flag`
- 1 → Defective product  
- 0 → Non-defective product  

## Models Implemented
- Logistic Regression (primary model)
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
- K-Nearest Neighbors (KNN)

## Key Insights
- Identified important features influencing product defects  
- Compared performance of multiple classification models  
- Evaluated model effectiveness using standard metrics  

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

## Libraries Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  

## Business Impact
- Enables early detection of defective units  
- Helps reduce manufacturing costs and waste  
- Improves production efficiency and quality control

 ## Results
- Logistic Regression achieved **96% accuracy**, demonstrating strong predictive performance  
- Precision: **~0.90** (low false positives)  
- Recall: **~0.95** (captures most defective units)  
- The model shows excellent balance between detecting defects and minimizing false alarms  

## Confusion Matrix Insights
- Correctly identified **2565 non-defective units**  
- Correctly detected **940 defective units**  
- Only **50 defective units missed** (false negatives)  
- Minimal false alarms (**106 false positives**)

Overall, the model is highly effective for real-world manufacturing scenarios where early and accurate defect detection is critical.
