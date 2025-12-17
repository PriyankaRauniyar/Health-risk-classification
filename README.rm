
# Scripts Directory

This folder contains all R scripts used for **data exploration, preprocessing,
modeling, evaluation, and visualization** in the *Health Risk Classification* project.

---

## Script Overview

### 1. `SourceCode.R` — Data Exploration & Preprocessing
This script performs **initial data analysis and cleaning** before modeling.

**Key tasks performed:**
- Importing the cleaned dataset
- Exploratory Data Analysis (EDA)
  - Summary statistics
  - Distribution analysis of numerical variables
- Data cleaning and preparation
  - Handling missing values
  - Variable type conversion (categorical vs numerical)
- Outlier detection and visualization
  - Boxplots for variables such as:
    - Age
    - BMI
    - Sleep duration
  - Identification of extreme values and skewed distributions
- Data transformation (if required)
- Splitting the dataset into:
  - Training set
  - Testing set

This script ensures the data is **clean, consistent, and suitable for predictive modeling**.

---

### 2. `Logistic_Regression_Model.R` — Logistic Regression Modeling
Implements **Logistic Regression** for binary health-risk classification.

**Key tasks performed:**
- Model training using `glm(family = "binomial")`
- Estimation of regression coefficients and statistical significance
- Prediction of probabilities and binary class labels
- Model evaluation on training and testing datasets
  - Confusion matrix
  - Accuracy
  - Sensitivity (Recall)
  - Specificity
  - Type I Error (False Positive Rate)
  - Type II Error (False Negative Rate)
- Visualization of model behavior
  - Logistic S-curve plots for:
    - BMI
    - Age
    - Sleep duration
  - Distribution of predicted probabilities
  - Predicted class distribution

---

### 3. `DecisionTree_Model.R` — Decision Tree Classification
Implements a **Decision Tree classifier** using the `rpart` package.

**Key tasks performed:**
- Decision tree model training (`method = "class"`)
- Tree visualization using `rpart.plot`
- Interpretation of decision rules and split variables
- Prediction on training and testing datasets
- Performance evaluation
  - Confusion matrix
  - Accuracy
  - Type I and Type II error analysis
- Model comparison with Logistic Regression

---

## How to Run the Scripts

1. Open **RStudio**
2. Set the working directory to the project root
3. Run scripts in sequence:

```r
source("scripts/SourceCode.R")
source("scripts/Logistic_Regression_Model.R")
source("scripts/DecisionTree_Model.R")
