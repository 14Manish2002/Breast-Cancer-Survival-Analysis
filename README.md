# 🩺 Breast Cancer Survival Analysis

## 📖 Overview

Breast cancer is one of the leading causes of cancer-related mortality worldwide, making survival prediction and risk assessment essential for effective clinical decision-making. This project presents a comprehensive survival analysis of **15,054 breast cancer patients** using advanced biostatistical methods to evaluate overall survival patterns and identify key prognostic factors associated with mortality risk.

Using **Kaplan–Meier Estimation**, **Log-Rank Testing**, **Cox Proportional Hazards Modeling**, and **Weibull Accelerated Failure Time (AFT) Modeling**, the study investigates survival outcomes and quantifies the impact of clinical characteristics on patient prognosis. Model assumptions were validated through **Schoenfeld Residual Diagnostics** and time-varying covariate assessment to ensure robust interpretation and reliable inference.

The analysis identified **Tumor Size (HR = 1.62)** and **HER2-Positive Status (HR = 1.44)** as significant predictors of mortality risk. This project demonstrates the practical application of survival analytics in oncology and highlights how statistical modeling can support evidence-based treatment planning, patient risk stratification, and healthcare decision-making.

---

## 🎯 Objectives

* Estimate overall survival probabilities among breast cancer patients.
* Compare survival outcomes across clinical subgroups.
* Identify significant prognostic factors associated with mortality risk.
* Develop interpretable survival models for patient risk assessment.
* Generate clinically meaningful insights to support treatment planning.

---

## 📊 Dataset Information

| Attribute          | Details               |
| ------------------ | --------------------- |
| Domain             | Oncology / Healthcare |
| Patients           | 15,054                |
| Clinical Variables | 34                    |
| Outcome            | Overall Survival      |
| Analysis Type      | Survival Analysis     |

---

## 🛠️ Tools & Technologies

* R
* survival
* survminer
* ggplot2
* dplyr
* tidyr

---

## 🔬 Methodology

### 1. Data Preparation

* Data quality assessment
* Missing value handling
* Variable transformation
* Feature engineering
* Survival object creation

### 2. Exploratory Data Analysis

* Patient demographics analysis
* Clinical feature exploration
* Survival outcome assessment

### 3. Kaplan–Meier Survival Analysis

* Estimated survival probabilities over time
* Generated survival curves for patient subgroups
* Evaluated survival patterns and trends

### 4. Log-Rank Testing

* Compared survival distributions between groups
* Assessed statistical significance of survival differences

### 5. Cox Proportional Hazards Model

Developed a multivariable Cox regression model to evaluate the effect of clinical variables on mortality risk and estimate hazard ratios for significant prognostic factors.

### 6. Model Validation

* Schoenfeld residual diagnostics
* Proportional hazards assumption testing
* Time-varying covariate assessment

### 7. Weibull Accelerated Failure Time (AFT) Model

* Modeled survival time directly
* Estimated survival-time acceleration effects
* Improved interpretation of patient prognosis

---

## 📈 Results

### Significant Predictors of Mortality Risk

| Variable             | Hazard Ratio (HR) |
| -------------------- | ----------------- |
| Tumor Size           | 1.62              |
| HER2-Positive Status | 1.44              |

### Model Performance

| Metric                      | Value |
| --------------------------- | ----- |
| Concordance Index (C-Index) | 0.66  |

---

## 💡 Key Findings

* Larger tumor size was associated with significantly increased mortality risk.
* HER2-positive patients demonstrated poorer survival outcomes.
* Survival probabilities varied substantially across clinical subgroups.
* Cox regression effectively identified high-risk patient populations.
* Weibull AFT modeling provided interpretable estimates of survival-time effects.
* Findings support evidence-based prognosis assessment and treatment planning.

---

## 📊 Visualizations

The project includes:

* Kaplan–Meier Survival Curves
* Log-Rank Survival Comparisons
* Cox Hazard Ratio Forest Plot
* Schoenfeld Residual Diagnostics
* Weibull AFT Model Outputs

---

## 📂 Repository Structure

```text
breast-cancer-survival-analysis/
│
├── data/
│   └── breast_cancer_data.csv
│
├── scripts/
│   ├── data_preprocessing.R
│   ├── survival_analysis.R
│   ├── cox_model.R
│   └── weibull_aft_model.R
│
├── outputs/
│   ├── km_survival_curve.png
│   ├── logrank_test_results.png
│   ├── cox_forest_plot.png
│   ├── schoenfeld_diagnostics.png
│   └── weibull_aft_results.png
│
├── README.md
└── requirements.txt
```

---

## 🚀 Skills Demonstrated

* Survival Analysis
* Biostatistics
* Clinical Data Analytics
* Healthcare Analytics
* Kaplan–Meier Estimation
* Log-Rank Testing
* Cox Proportional Hazards Modeling
* Weibull AFT Modeling
* Hazard Ratio Interpretation
* Statistical Inference
* Risk Stratification
* Data Visualization

---

