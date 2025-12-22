# Framingham Heart Disease ML Analysis

## Authors
Mostafa Badawe, Mariam Yaser, Mohamed Maher, Mohamed Azoz, Mariam Melad

## Project Overview
Analysis of the Framingham Heart Disease Dataset to predict coronary heart disease (CHD) risk using:

- Regression (Linear & Lasso)
- Classification (Logistic Regression & Decision Tree)
- Clustering (K-Means)

## Dataset
- 4,240 patients, 16 features
- Target: `TenYearCHD` (0 = No CHD, 1 = CHD in 10 years)

## Key Results

**Regression:** Age and BMI are main predictors of systolic BP. Lasso improves interpretability.  

| Model | Dataset | R² |
|-------|--------|----|
| Linear Regression | Testing | 0.22 |
| Lasso Regression  | Testing | 0.22 |

**Classification:** Logistic Regression prioritizes recall; Decision Tree gives better overall accuracy.  

| Model | Accuracy | Recall (CHD) |
|-------|---------|--------------|
| Logistic Regression | 0.61 | 0.68 |
| Decision Tree       | 0.67 | 0.57 |

**Clustering:** K-Means identifies 3 patient groups with varying cardiovascular risk.

## Usage
1. Clone repository  
2. Install dependencies from `requirements.txt`  
3. Run `notebooks/analysis.ipynb`
