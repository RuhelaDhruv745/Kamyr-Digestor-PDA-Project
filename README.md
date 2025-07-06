# 📊 Kamyr Digester Process Data Analysis

This project performs a detailed **Exploratory Data Analysis (EDA)** and **Feature Engineering** on industrial process data (Kamyr Digester) to uncover patterns, improve data quality, and identify critical factors affecting pulp quality (Y-Kappa).

---

## 🔍 Project Objectives

- Understand structure and quality of industrial sensor data.
- Handle and visualize missing values using various techniques.
- Compute and visualize statistical summaries (mean, std, CV).
- Identify and visualize correlations between process variables.
- Conduct feature engineering to improve modeling readiness.
- Identify critical variables affecting **Y-Kappa** (a pulp quality metric).

---

## 📁 Project Structure

### 1. **Exploratory Data Analysis (EDA)**

- Dataset shape, column names, data types
- Missing value inspection (table + heatmap)
- Summary statistics with formatting
- Coefficient of Variation (CV) analysis with color coding
- Histograms and KDE plots for all input variables
- Box plots for outlier detection

### 2. **Missing Value Imputation**

- Mean Imputation
- KNN Imputer (k=5)
- Visual heatmaps before and after imputation

### 3. **Correlation Analysis**

- Compute and visualize correlation heatmap (numeric features only)
- Detect multicollinearity and feature redundancy

### 4. **Feature Engineering**

- Interaction features (e.g., `ChipRate * BlowFlow`)
- Lagged features and rolling averages (planned)
- Standard scaling of numeric features

### 5. **Target Variable Analysis: Y-Kappa**

- Scatter plots of Y-Kappa vs each process input
- Optional regression lines to assess relationships

---

## 📈 Key Visualizations

- 🔥 Missing value heatmaps
- 📉 Distribution plots
- 📦 Box plots for outlier detection
- 🧬 Correlation heatmap
- 📊 Y-Kappa vs Process Variables (23+ scatter plots)

---

## 🛠️ Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
