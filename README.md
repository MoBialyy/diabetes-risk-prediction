# Diabetes Risk Prediction

## 📌 Project Overview
This project predicts the risk of diabetes using **data mining** and **machine learning** techniques applied to medical and biochemical parameters.  
It follows the course requirements by implementing preprocessing, outlier detection, correlation analysis, multiple classification models, and visualization of results.

The dataset includes:
- **Demographics:** Age, Gender
- **Biochemical Parameters:** Sugar Level, Creatinine Ratio (Cr), Urea, Cholesterol (Chol), LDL, VLDL, HDL, Triglycerides (TG)
- **Clinical Indicators:** BMI, HbA1C
- **Target Class:** Non-Diabetic, Predict-Diabetic, Diabetic

---

## 🎯 Project Objectives
1. **Data Preprocessing**
   - Handle missing values (`fillna`)
   - Replace inconsistent entries (`replace`)
   - Encode categorical variables (`LabelEncoder`)
   - Normalize features (`MinMaxScaler`)

2. **Outlier Detection**
   - Apply IQR method with quantiles
   - Visualize outliers using boxplots

3. **Feature Analysis**
   - Correlation heatmap to identify strong relationships between features
   - Bar plots for class distribution

4. **Classification Models**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - Support Vector Classifier (SVC)
   - K-Nearest Neighbors (KNN)
   - Gaussian Naive Bayes (GaussianNB)

5. **Model Evaluation**
   - Accuracy comparison for all classifiers

---

## 📊 Tools & Libraries
- **Language:** Python
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Outlier Detection:** IQR method

---

## 🗂 Project Structure
