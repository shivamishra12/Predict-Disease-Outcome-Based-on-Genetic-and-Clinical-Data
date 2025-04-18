# Predict-Disease-Outcome-Based-on-Genetic-and-Clinical-Data
# Predict Disease Outcome Based on Genetic and Clinical Data

## 📝 Problem Statement
Use supervised machine learning to classify patients based on genetic markers, clinical symptoms, and lifestyle factors. The goal is to predict whether a patient is at risk for a particular disease.

---

## 📌 Introduction
This project leverages machine learning techniques to predict disease outcomes based on genetic and clinical data. Using a dataset with 30 features derived from digitized images of cell nuclei, the model learns patterns associated with benign and malignant cases.

---

## 🔍 Methodology

1. **Data Cleaning**: Removed irrelevant columns and handled missing values.  
2. **Encoding**: The target column (`diagnosis`) was encoded (M = 1, B = 0).  
3. **Data Splitting**: Data split into training and test sets (80:20).  
4. **Modeling**: Trained a Random Forest Classifier using scikit-learn.  
5. **Evaluation**: Assessed with accuracy score and classification report.  
6. **Visualization**: Top 10 important features were visualized using a bar plot.

---

## 💻 Code

The model is implemented in Python using the following libraries:

- `pandas`  
- `numpy`  
- `scikit-learn`  
- `seaborn`  
- `matplotlib`  

Notebook used: **Google Colab**

---

## ✅ Output / Result

- **Accuracy**: 96.49%
- **Classification Report**:
  - Precision, Recall, F1-Score for both classes
  - Macro and weighted average scores above 96%

- **Feature Importance**:
  Top features influencing the prediction include:
  - `area_worst`
  - `concave points_worst`
  - `concave points_mean`
  - `radius_worst`
  - `concavity_mean`

---

## 📊 Screenshot

*Refer to the included image in this repository for the output screenshot showing the classification report and feature importance graph.*

---

## 📚 References / Credits

- Dataset: Breast Cancer Wisconsin (Diagnostic) Dataset  
- Tools: Python, Google Colab  
- Libraries: pandas, scikit-learn, matplotlib, seaborn
