

---

# Ola Driver Churn Prediction

![Ola Logo](https://upload.wikimedia.org/wikipedia/en/thumb/0/0f/Ola_Cabs_logo.svg/801px-Ola_Cabs_logo.svg.png?20210518001051)  
*(Prediction of driver churn using machine learning techniques)*

## Project Overview

This project focuses on predicting driver churn for Ola, based on various driver attributes such as age, gender, education level, income, quarterly ratings, and total business value. The goal is to predict whether a driver will leave the company and explore the factors that contribute to their retention or churn.

### Problem Statement

The objective is to:
1. Analyze driver data to understand the factors influencing their performance and churn.
2. Predict driver churn using ensemble models.
3. Identify actionable insights that Ola can use to improve driver retention.

### Key Tasks

1. **Exploratory Data Analysis (EDA)**:
   - Perform univariate and bivariate analysis on key variables like Age, Income, Total Business Value, Quarterly Rating, etc.
   - Visualize the data through scatter plots, box plots, and correlation heatmaps.

2. **Data Preprocessing**:
   - Handle missing values using **KNN Imputation**.
   - Perform feature engineering, class balancing, and encoding to prepare the data for machine learning models.

3. **Model Building**:
   - Build predictive models using ensemble methods like Random Forest and XGBoost.

4. **Results Evaluation**:
   - Evaluate models using confusion matrix, ROC-AUC curve, and classification report.

---

## Steps Completed

### 1. Exploratory Data Analysis (EDA)

- Loaded the dataset and performed initial checks.
- Univariate analysis of continuous and categorical variables.
- Bivariate analysis, observing correlations between key variables.

### 2. Data Preprocessing

- **KNN Imputation** to handle missing values.
- **Feature Engineering** to create new variables for better prediction.

### 3. Next Steps

- Address class imbalance using SMOTE.
- Standardize numerical data and one-hot encode categorical variables.
- Build ensemble models for accurate prediction.

---

## Data Description

The dataset includes driver data from 2019 to 2020 with features like:

- **Driver_ID**
- **Age**
- **Gender**
- **City**
- **Income**
- **Quarterly Rating**
- And more...

---

## Installation

To run this project locally:

1. **Clone the Repository**:
   ```bash
   (https://github.com/Srinivaskoruprolu007/OLA-Ensemble-Learning.git)
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**:
   Open the Jupyter notebook to follow the steps for EDA and preprocessing.

---

## Tech Stack

![Python Logo](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)  
- **Language**: Python
- **Libraries**: pandas, scikit-learn, XGBoost, matplotlib

---

## Contact

For inquiries or further discussion:

- **Name**: Srinivas Koruprolu
- **Email**: srinivasg3112@gmail.com
- **LinkedIn**: [Srinivas LinkedIn](https://www.linkedin.com/in/srinivas-koruprolu)

---
