# Logistic Regression - Binary Classification

## Objective
Build a binary classification model using Logistic Regression to predict whether a tumor is malignant or benign.

## Dataset
Breast Cancer Wisconsin Dataset  
Target Variable:
- M (Malignant)
- B (Benign)

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Steps Performed
1. Loaded dataset in Jupyter Notebook.
2. Removed unnecessary columns (`id`, `Unnamed: 32`).
3. Converted diagnosis into binary values (M=1, B=0).
4. Split data into training and testing sets.
5. Standardized features using StandardScaler.
6. Trained Logistic Regression model.
7. Evaluated using:
   - Accuracy
   - Confusion Matrix
   - Precision & Recall
   - ROC-AUC

## Result
The model successfully classified tumors with high accuracy and good precision-recall balance.

## Conclusion
This task helped in understanding:
- Binary Classification
- Logistic Regression
- Sigmoid Function
- Model Evaluation Metrics
