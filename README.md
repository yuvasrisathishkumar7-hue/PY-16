# MEDICAL INSURANCE COST ANALYSIS AND PREDICTION SYSTEM (KAGGLE DATASET)

---

## PROJECT OVERVIEW

The **Medical Insurance Cost Analysis and Prediction System** is a data analytics and machine learning project that analyzes health insurance customer data using **Exploratory Data Analysis (EDA)**, **Linear Regression**, **Multiple Linear Regression**, **Logistic Regression**, and **Interactive Dashboard Visualization** techniques.

This project studies important customer-related factors such as **age, gender, BMI (Body Mass Index), number of children, smoking habits, region, and insurance charges** using a real-world medical insurance dataset obtained from Kaggle.

The system helps insurance companies understand customer behavior, identify high-risk customers, estimate insurance premiums, analyze healthcare cost patterns, and support data-driven decision-making through visualization and predictive analytics.

---

## PROBLEM STATEMENT

Health insurance companies collect large volumes of customer information including age, gender, BMI, number of children, smoking habits, region, and medical insurance charges.

Manually analyzing this information to estimate insurance costs and identify high-risk customers is difficult, time-consuming, and prone to errors.

Incorrect insurance cost estimation can lead to:

* Financial losses for insurance companies
* Unfair premium charges for customers
* Poor risk assessment
* Inefficient policy planning
* Inaccurate decision-making

Therefore, there is a need for an automated system that can analyze customer data, identify key factors affecting insurance costs, and predict future medical insurance charges accurately.

---

## DATASET DESCRIPTION

| COLUMN NAME | DESCRIPTION                  |
| ----------- | ---------------------------- |
| age         | Age of the customer          |
| sex         | Gender of the customer       |
| bmi         | Body Mass Index              |
| children    | Number of dependents covered |
| smoker      | Smoking status               |
| region      | Residential region           |
| charges     | Medical insurance charges    |

**Dataset Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/mirichoi0218/insurance

---

## PROJECT OBJECTIVES

* Load and analyze the medical insurance dataset
* Perform data cleaning and preprocessing
* Handle missing values and duplicates
* Calculate descriptive statistics
* Analyze insurance cost patterns
* Study the impact of age, BMI, smoking habits, and children on insurance charges
* Identify high-cost customer segments
* Perform risk classification
* Build Simple Linear Regression model
* Build Multiple Linear Regression model
* Build Logistic Regression model
* Evaluate model performance
* Create an interactive dashboard using Plotly
* Generate insurance-related insights and business recommendations

---

## LIBRARIES USED

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn

---

## DATA CLEANING STEPS

* Loaded insurance dataset from Kaggle
* Checked missing values using `isnull()`
* Removed duplicate records
* Verified data types
* Encoded categorical variables:

  * Sex
  * Smoker
  * Region
* Created BMI Categories
* Created Age Groups
* Created Risk Categories
* Prepared data for machine learning models

---

## DATA ANALYSIS PERFORMED

### Descriptive Statistics

* Average Age
* Average BMI
* Average Number of Children
* Average Insurance Charges
* Minimum and Maximum Charges
* Standard Deviation Analysis

### Insurance Cost Analysis

#### Smoking Status Analysis

* Smoker vs Non-Smoker Charges
* Average charges by smoking status

#### Gender Analysis

* Male vs Female Insurance Charges

#### BMI Category Analysis

* Underweight
* Normal Weight
* Overweight
* Obese

#### Age Group Analysis

* Young
* Adult
* Middle Age
* Senior

### Group-Based Analysis

* Age Group vs Charges
* BMI Category vs Charges
* Children vs Charges
* Region vs Charges
* Smoking Status vs Charges
* Gender vs Charges

### Relationship Analysis

* Age vs Charges
* BMI vs Charges
* Children vs Charges
* Smoking Status vs Charges
* Correlation Analysis
* Influencing Factor Analysis

### Risk Analysis

Customers are classified into:

* Low Cost Customers
* Medium Cost Customers
* High Cost Customers

The system identifies customers likely to generate higher medical expenses and insurance claims.

---

## PREDICTIVE MODELING

### Simple Linear Regression

**Objective:** Predict insurance charges using age.

**Independent Variable**

* Age

**Dependent Variable**

* Charges

**Evaluation Metrics**

* R² Score
* MAE
* MSE
* RMSE

---

### Multiple Linear Regression

**Objective:** Predict insurance charges using multiple customer attributes.

**Independent Variables**

* Age
* BMI
* Children
* Smoker

**Dependent Variable**

* Charges

**Evaluation Metrics**

* R² Score
* MAE
* MSE
* RMSE

---

### Logistic Regression

**Objective:** Classify customers into High Cost and Low Cost categories.

**Independent Variables**

* Age
* BMI
* Children
* Smoker

**Dependent Variable**

* Insurance Category

**Classes**

* 0 = Low Cost Customer
* 1 = High Cost Customer

**Evaluation Metrics**

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

## DATA VISUALIZATION

| CHART        | PURPOSE              | GRAPH UNDERSTANDING                 |
| ------------ | -------------------- | ----------------------------------- |
| Histogram    | Age Distribution     | Shows customer age frequency        |
| Histogram    | BMI Distribution     | Shows BMI distribution              |
| Histogram    | Charges Distribution | Shows insurance charge distribution |
| Scatter Plot | Age vs Charges       | Relationship analysis               |
| Scatter Plot | BMI vs Charges       | Impact of BMI on charges            |
| Bar Chart    | Region vs Charges    | Regional insurance comparison       |
| Bar Chart    | Smoker vs Charges    | Smoking impact analysis             |
| Box Plot     | Charges Analysis     | Outlier detection                   |
| Heatmap      | Correlation Matrix   | Feature relationship analysis       |
| Pie Chart    | Smoker Distribution  | Smoking population distribution     |
| Pie Chart    | Gender Distribution  | Gender proportion analysis          |
| Bar Chart    | Risk Distribution    | Customer risk categories            |

---

## AGE DISTRIBUTION

Displays the distribution of customer ages.

---

## BMI DISTRIBUTION

Shows how BMI values are distributed among customers.

---

## INSURANCE CHARGES DISTRIBUTION

Displays the frequency of insurance charges.

---

## AGE VS INSURANCE CHARGES

Illustrates how insurance charges change with age.

---

## BMI VS INSURANCE CHARGES

Shows the relationship between BMI and insurance premiums.

---

## REGION-WISE CHARGES

Compares average insurance charges across different regions.

---

## SMOKER VS NON-SMOKER ANALYSIS

Highlights the impact of smoking on insurance charges.

---

## OUTLIER DETECTION

Uses Box Plot to identify unusual insurance charges.

---

## CORRELATION HEATMAP

Displays relationships among all insurance variables.

---

## RISK DISTRIBUTION

Shows customer classification into:

* Low Cost
* Medium Cost
* High Cost

---

## MODEL PERFORMANCE EVALUATION

### Simple Linear Regression

Evaluates how age alone predicts insurance charges.

### Multiple Linear Regression

Evaluates how multiple factors improve prediction accuracy.

### Logistic Regression

Evaluates customer classification performance.

---

## DASHBOARD FEATURES

### Insurance Charges Distribution

Interactive chart displaying charge distribution.

### Age vs Charges Analysis

Interactive scatter plot for age and insurance charges.

### BMI vs Charges Analysis

Interactive BMI impact visualization.

### Smoker vs Non-Smoker Comparison

Interactive comparison of smoking impact.

### Region-Wise Charges

Regional insurance cost comparison.

### Gender-Wise Charges

Gender-based insurance charge analysis.

### Correlation Heatmap

Interactive feature relationship analysis.

### Risk Level Analysis

Customer risk category visualization.

### Dynamic Data Exploration

Allows users to explore customer behavior interactively.

---

## TECHNOLOGIES USED

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn
* Google Colab / Jupyter Notebook

---

## EXPECTED OUTCOME

* Understand medical insurance cost behavior
* Identify major factors affecting insurance charges
* Analyze smoking impact on insurance costs
* Detect high-risk customers
* Improve premium estimation accuracy
* Support risk assessment and policy planning
* Enable data-driven decision-making
* Enhance insurance business efficiency

---

## CONCLUSION

This project demonstrates how medical insurance customer data can be analyzed using **Python**, **EDA**, **Machine Learning**, and **Data Visualization Techniques**.

By applying **Exploratory Data Analysis**, **Risk Classification**, **Simple Linear Regression**, **Multiple Linear Regression**, **Logistic Regression**, and **Interactive Dashboards**, the system transforms raw insurance data into meaningful business insights.

The project helps insurance companies improve premium estimation, identify high-risk customers, optimize policy planning, reduce financial risk, and support effective healthcare insurance decision-making.
