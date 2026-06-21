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



<img width="1764" height="418" alt="image" src="https://github.com/user-attachments/assets/ac26e9ab-b79c-42f6-97d3-a918fb351e91" />





---

## BMI DISTRIBUTION

Shows how BMI values are distributed among customers.





<img width="1765" height="419" alt="image" src="https://github.com/user-attachments/assets/01410d11-8df7-4e51-bc13-9fd1886235cd" />




---

## INSURANCE CHARGES DISTRIBUTION

Displays the frequency of insurance charges.




<img width="1762" height="416" alt="image" src="https://github.com/user-attachments/assets/d70a4f92-bc83-495b-9f2e-414f5d9008c4" />




---

## AGE VS INSURANCE CHARGES

Illustrates how insurance charges change with age.



<img width="1767" height="412" alt="image" src="https://github.com/user-attachments/assets/8084c368-38ef-450b-981d-fe53b5996126" />




---

## BMI VS INSURANCE CHARGES

Shows the relationship between BMI and insurance premiums.



<img width="1764" height="421" alt="image" src="https://github.com/user-attachments/assets/dc7a888f-3977-463c-b821-629f55827cd4" />




---

## REGION-WISE CHARGES

Compares average insurance charges across different regions.




<img width="1769" height="421" alt="image" src="https://github.com/user-attachments/assets/fc3d4ba5-c8b5-4ef2-adc8-917ccc15a66d" />




---

## SMOKER VS NON-SMOKER ANALYSIS

Highlights the impact of smoking on insurance charges.





<img width="1767" height="423" alt="image" src="https://github.com/user-attachments/assets/1b069817-54ba-420d-abf4-8b2dcf77a7c1" />






---

## OUTLIER DETECTION

Uses Box Plot to identify unusual insurance charges.




<img width="1758" height="412" alt="image" src="https://github.com/user-attachments/assets/7604b565-e6cf-4c98-876c-082a93241af6" />





---

## CORRELATION HEATMAP

Displays relationships among all insurance variables.



<img width="1761" height="416" alt="image" src="https://github.com/user-attachments/assets/3486a551-1c32-4294-bfaf-0bf199cafb7c" />





---

## RISK DISTRIBUTION

Shows customer classification into:

* Low Cost
* Medium Cost
* High Cost




<img width="1764" height="418" alt="image" src="https://github.com/user-attachments/assets/e0649531-5642-46e1-9ef3-7e089f111e51" />



---

## MODEL PERFORMANCE EVALUATION

### Simple Linear Regression

Evaluates how age alone predicts insurance charges.



<img width="571" height="372" alt="image" src="https://github.com/user-attachments/assets/75fff7d0-0319-4db6-9678-365f05f185b6" />




### Multiple Linear Regression

Evaluates how multiple factors improve prediction accuracy.



<img width="1762" height="420" alt="image" src="https://github.com/user-attachments/assets/2b39fe8a-106d-453c-938c-4b68398a515b" />



### Logistic Regression

Evaluates customer classification performance.

<img width="427" height="362" alt="image" src="https://github.com/user-attachments/assets/7e527fbd-e3e4-4c38-a831-6ce31c7cb4dc" />


---

## DASHBOARD FEATURES

### Insurance Charges Distribution

Interactive chart displaying charge distribution.



<img width="1762" height="418" alt="image" src="https://github.com/user-attachments/assets/dbcdbf3b-c643-487a-a5fd-89a40cd537e6" />




### Age vs Charges Analysis

Interactive scatter plot for age and insurance charges.



<img width="1765" height="422" alt="image" src="https://github.com/user-attachments/assets/be8b7434-04dc-41c3-9858-a902a581bc2b" />




### BMI vs Charges Analysis

Interactive BMI impact visualization.



<img width="1762" height="421" alt="image" src="https://github.com/user-attachments/assets/5a117120-3063-444f-818a-69ecb6ba2cff" />




### Smoker vs Non-Smoker Comparison

Interactive comparison of smoking impact.



<img width="1759" height="422" alt="image" src="https://github.com/user-attachments/assets/e50b794c-9f5a-4ff9-8447-a120f46781d0" />




### Region-Wise Charges

Regional insurance cost comparison.


<img width="1760" height="420" alt="image" src="https://github.com/user-attachments/assets/c22cc70d-b7fe-4b54-994b-21c3b6f8081e" />



### Gender-Wise Charges

Gender-based insurance charge analysis.



<img width="1762" height="424" alt="image" src="https://github.com/user-attachments/assets/0cd650ee-0069-4c6d-8d5f-f88072afbd99" />




### Correlation Heatmap

Interactive feature relationship analysis.




<img width="1771" height="425" alt="image" src="https://github.com/user-attachments/assets/a0ca87e8-a1d1-457e-87f4-5914634d3ccd" />




### Risk Level Analysis

Customer risk category visualization.



<img width="1760" height="421" alt="image" src="https://github.com/user-attachments/assets/1a26fa16-017b-4e22-aaa4-df5eb3e241e9" />




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
