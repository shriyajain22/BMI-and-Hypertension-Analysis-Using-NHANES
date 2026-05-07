# BMI and Hypertension Analysis Using NHANES

This project investigates the relationship between Body Mass Index (BMI) and hypertension risk using NHANES (National Health and Nutrition Examination Survey) data. Statistical modeling and exploratory data analysis were performed in R to evaluate how BMI, age, gender, and race contribute to hypertension prevalence in U.S. adults.

The project focuses on logistic regression modeling, model evaluation, and biological interpretation of public health data using reproducible statistical workflows.

## Project Objectives

The primary objectives of this project were to:
- Analyze the relationship between BMI and hypertension
- Explore demographic effects on hypertension prevalence
- Build and compare logistic regression models
- Evaluate model performance using ROC and AUC analysis
- Visualize predicted hypertension probabilities
- Perform reproducible statistical analysis using R

## Dataset

The analysis uses publicly available NHANES datasets containing:
- Demographic information
- BMI measurements
- Blood pressure indicators
- Health questionnaire responses

Variables analyzed include:
- BMI
- Age
- Gender
- Race/Ethnicity
- Hypertension status

## Statistical Analysis Workflow

### 1. Data Cleaning & Preprocessing
- Missing value handling
- Variable transformation
- Categorical encoding
- Dataset merging and filtering

### 2. Exploratory Data Analysis (EDA)
- BMI distribution analysis
- Hypertension prevalence visualization
- Demographic comparisons
- Correlation analysis

### 3. Logistic Regression Modeling
Three models were evaluated:

#### Model 1
Baseline intercept-only model

#### Model 2
Adjusted logistic regression using:
- BMI
- Age
- Gender
- Race

#### Model 3
BMI categorical model with demographic covariates

## Model Evaluation

The models were evaluated using:
- ROC curves
- Area Under the Curve (AUC)
- AIC/BIC model comparison
- Hosmer–Lemeshow goodness-of-fit test
- Odds ratio interpretation

### Key Findings
- BMI showed a positive association with hypertension risk
- Age demonstrated a strong effect on hypertension prevalence
- Adjusted models substantially improved predictive performance
- Model 2 achieved the best balance between interpretability and performance

## Visualizations

The project includes:
- BMI distribution plots
- Hypertension prevalence plots
- ROC curves
- Predicted probability trend plots
- Correlation visualizations
- Demographic comparison plots

Visualization tools:
- `ggplot2`
- `pROC`
- `dplyr`

## Tools & Technologies

### Programming & Analysis
- R
- R Markdown

### Statistical Packages
- ggplot2
- dplyr
- pROC
- caret
- ResourceSelection

### Statistical Methods
- Logistic regression
- ROC analysis
- Odds ratio analysis
- Model comparison metrics

Note: *This project was developed as a part of the Data Science and Statistical Modeling in R (BS845) coursework at Boston University.*
