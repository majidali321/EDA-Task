# Diabetes Dataset Analysis

## Overview
This project analyzes the **Diabetes dataset** to uncover insights about key health indicators related to diabetes. The analysis explores distributions, correlations, and statistical summaries of the data.

## Dataset
- The dataset contains **768 rows** and **9 columns**.
- No missing values are present.
- The dataset includes the following features:
  - Pregnancies (int)
  - Glucose (int)
  - BloodPressure (int)
  - SkinThickness (int)
  - Insulin (int)
  - BMI (float)
  - DiabetesPedigreeFunction (float)
  - Age (int)
  - Outcome (int - Diabetes diagnosis: 0 = No, 1 = Yes)

## Key Findings

### 1. Statistical Summary
- **Mean, Median, and Standard Deviation of Glucose and BMI:**
  - **Glucose:** Mean = 120.89, Median = 117, Std Dev = 31.97
  - **BMI:** Mean = 31.99, Median = 32, Std Dev = 7.88

### 2. Most Common Age Group
A histogram of the **Age** column shows that most individuals are in their **20s to 30s**.

### 3. Correlation with Diabetes (Outcome)
- **Glucose (0.47), BMI (0.29), and Age (0.23)** have the highest correlation with diabetes.
- A heatmap was used to visualize the feature correlations.

### 4. Outliers in Insulin
- A boxplot of the **Insulin** column indicates the presence of **extreme values (outliers).**

### 5. Relationship Between BMI and Diabetes
- **Diabetic individuals tend to have a higher BMI** (35.14) compared to non-diabetics (30.30).
- A KDE histogram illustrates this distinction.

### 6. Average Glucose Level for Diabetic vs. Non-Diabetic Patients
- **Non-Diabetic:** 109.98
- **Diabetic:** 141.26
- A histogram confirms that diabetics generally have **higher glucose levels**.

### 7. Pairplot Analysis
- A **pairplot** visualizing feature relationships highlights patterns where diabetics tend to have higher glucose and BMI levels.

## Visualizations
- Histograms for **Age, BMI, and Glucose levels**
- Heatmap for **feature correlations**
- Boxplot for **outliers in Insulin levels**
- Pairplot to **visualize relationships between multiple features**

## Conclusion
- **Higher Glucose and BMI levels are strong indicators of diabetes.**
- **Insulin levels show extreme values**, suggesting possible errors or distinct cases.
- Further analysis can explore predictive modeling using machine learning.

---
### **How to Run the Analysis**
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Run the Python script to generate insights and plots.

### **Next Steps**
- Implement **Machine Learning Models** to predict diabetes.
- Investigate **feature engineering techniques** to enhance predictive power.
