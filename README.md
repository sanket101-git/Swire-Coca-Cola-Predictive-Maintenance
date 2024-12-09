# 🚀 Predictive Maintenance for Swire Coca-Cola

## 📊 Project Overview

This project focuses on developing a **predictive maintenance model** for Swire Coca-Cola to reduce unplanned machine downtimes and improve production efficiency. By leveraging historical downtime data, the model anticipates equipment failures, enabling proactive maintenance and minimizing costly disruptions.

---

## 🏢 Business Problem

Unplanned machine downtimes in Swire Coca-Cola's six production plants result in:

- **Production inefficiencies**
- **Financial losses** due to disrupted workflows
- **Resource Strain:** Reactive maintenance substantially strains resources, diverting time and effort from strategic, long-term objectives.

### 🎯 Goal:
Enhance maintenance strategies by predicting failures and recommending timely maintenance actions to optimize plant operations.

---

## 🎯 Project Objectives

1. **Understand Maintenance Patterns:**
   - Analyze planned and unplanned maintenance activities across different production locations.

2. **Develop Predictive Models:**
   - Implement time series and survival analysis models to forecast machine downtimes.

3. **Optimize Maintenance Scheduling:**
   - Enable proactive and efficient maintenance planning.

4. **Business Efficiency:**
   - Reduce downtime costs and improve spare parts inventory management.

---

## 🛠️ Analytics Approach

### 1. Exploratory Data Analysis (EDA)
- Investigated the distribution of planned vs. unplanned maintenance.
- Analyzed downtime patterns across locations.
- Identified key features such as:
  - `ACTUAL_WORK_IN_MINUTES`
  - `MAINTENANCE_TYPE_DESCRIPTION`
  - `FAILURE_RISK_SCORE`

### 2. Feature Engineering
Derived metrics to enhance model accuracy:
- **`TIME_USED_TO_LIFESPAN_RATIO`**
- **`TOTAL_LIFESPAN`**
- **`FAILURE_RISK_SCORE`**

### 3. Modeling

#### Time Series Models:
- **ARIMA / SARIMA:** Forecasting machine downtimes using autoregressive models.
- **Prophet:** Decomposing trends and seasonality for robust forecasting.
- **XGBoost:** Regression models for high predictive accuracy.

#### Survival Analysis:
- Modeled **time-to-failure probabilities** for different machines.

### 4. Web Deployment
Developed a **Streamlit Web App** for interactive visualization:
- Group data by production location.
- Resample data monthly for trend analysis.
- Visualize failure risk scores and maintenance forecasts.

---

## 💼 Business Value

- **Reduced Downtime:** Proactive maintenance reduces unexpected failures.
- **Cost Savings:** Minimize financial impact due to downtimes.
- **Efficiency Gains:** Optimize maintenance schedules and resource allocation.
- **Data-Driven Decisions:** Improved planning for spare parts and repairs.

---

## 👥 My Contributions

- **EDA & Data Cleaning:** Maintenance trends analysis and data preprocessing.
- **Feature Engineering:** Derived informative features for modeling.
- **Model Development:** Built time series.
- **Web Application:** Developed an interactive Streamlit app for visual insights and forecasting.

---

## ⚠️ Challenges Encountered

1. **Data Quality Issues:**
   - Inconsistent timestamps and missing values required extensive preprocessing.

2. **Model Complexity:**
   - Balancing accuracy and interpretability in predictive models.

3. **Deployment:**
   - Integrating models into a user-friendly web interface.
  
4. **Feature Selection and Engineering:**
   - Managing a large dataset with numerous interdependent features presented difficulties in identifying the most relevant predictors for maintenance and failure      risk.
   - Extensive iterations were required to optimize the **Failure Risk Score** and ensure meaningful insights.

---

## 📚 Key Learnings

- **Time Series Forecasting:** ARIMA, SARIMA, Prophet, and XGBoost.
- **Survival Analysis:** Predicting machine failure times.
- **Web Deployment:** Deploying models via Streamlit for stakeholders.
- **Collaboration:** Effective teamwork in data analysis, modeling, and deployment.

---

## 📂 Repository Contents

- **`EDA.ipynb`:** Exploratory Data Analysis of maintenance data.
- **`MODELING.ipynb`:** Feature engineering and predictive model development.
- **`TimeSeries_Streamlit_WebApp.ipynb`:** Code for the Streamlit web application and time series models.

---

### 📊 Interactive Dashboard

[View Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjJjNWZmYTAtMGVhNy00NTE5LTk0YjYtY2Q3ZDQwYTA0ZDlhIiwidCI6IjUyMTdlMGU3LTUzOWQtNDU2My1iMWJmLTdjNmRjZjA3NGY5MSIsImMiOjZ9)
