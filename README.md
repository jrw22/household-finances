# Project Title: Household Finance Analysis and Prediction

## Overview

This project provides a comprehensive analysis of household financial decisions in the UK, using data from the NMG Survey (2011–2023). The project explores trends in household savings, annual savings rates, and the impact of demographic, regional, and macroeconomic factors, including inflation and interest rates. Additionally, a machine learning model (Random Forest Regressor) is developed to predict annual household savings based on demographic and financial features.

The entire analysis and model implementation were completed in a Jupyter Notebook, providing a clear and interactive environment for data exploration and modeling.

---

## Objectives

1. **Analyse Household Savings Trends**:
   - Investigate savings behavior by age, housing tenure, and region.
   - Explore macroeconomic impacts, including inflation and interest rates.

2. **Develop a Predictive Model**:
   - Train a Random Forest Regressor to predict annual household savings.
   - Evaluate the model's performance using R² and Mean Squared Error (MSE).

3. **Provide Policy Insights**:
   - Highlight systemic disparities in savings behavior.
   - Suggest actionable recommendations for policymakers.

---

## Features

- **Exploratory Data Analysis**:
  - Visualisations of household savings trends by age, region, and housing tenure.
  - Analysis of macroeconomic influences on savings behavior.

- **Machine Learning**:
  - A Random Forest Regressor trained to predict annual savings using demographic, regional, and macroeconomic features.
  - Evaluation metrics (R² and MSE) to assess model performance.

- **Interactive Visualisations**:
  - Clear, styled charts created with `matplotlib` and `seaborn` for insights into savings trends and model results.

---

## Repository Structure

```
.
├── data/                # Raw and processed data files
├── analysis.ipynb       # Jupyter Notebook containing all analysis and modeling
├── README.md            # Project documentation
├── requirements.txt     # Python dependencies
```

---

## Environment Setup

This notebook was created with **Python 3.11.10** and the following libraries:

- **pandas**: 2.2.3
- **matplotlib**: 3.9.2
- **seaborn**: 0.13.2
- **scikit-learn**: 1.5.2

To replicate this environment, install the dependencies using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url/household-finance-analysis.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

4. Run all cells in the notebook to:
   - Explore data insights.
   - Visualise trends in household savings.
   - Train and evaluate the machine learning model.

---

## Results

### **Exploratory Insights**:
- Savings trends show significant disparities based on age, region, and housing tenure.
- Homeowners, particularly those who own outright, consistently save more than renters.
- Regional disparities highlight Greater London and the South East as leaders in annual and total savings.

### **Model Performance**:
- **R² Score**: 0.16 (explains 16% of the variance in savings).
- **Mean Squared Error (MSE)**: 49,857,511.31 (reflects significant prediction error, with room for improvement).

### **Recommendations**:
- Targeted policies to support renters and younger households.
- Focus on reducing regional inequalities and addressing inflationary pressures.

---

## Future Work

1. **Feature Engineering**:
   - Explore additional predictors, such as household spending patterns or debt levels.
   - Incorporate lagged features (e.g., previous year’s savings).

2. **Model Improvement**:
   - Tune hyperparameters and test advanced algorithms (e.g., Gradient Boosting, XGBoost).
   - Address outliers and normalise data for better performance.

3. **Policy Analysis**:
   - Simulate the impact of potential policies on savings behavior.
   - Incorporate household expenditure data to assess financial resilience.
