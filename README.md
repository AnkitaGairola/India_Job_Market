# 📌 Project Overview
This project presents an end-to-end analysis of the Indian job market and salary trends using a large, realistic dataset covering job roles, companies, cities, experience levels, demand indicators, and work modes.

The objective is to understand salary distribution, hiring demand, experience-driven progression, remote work impact, and to build interactive dashboards and predictive models that support workforce planning and career insights.
________________________________________

# 🧠 Dataset Description
The dataset contains 30,000 job-market records generated using realistic Indian labor-market patterns observed across major companies and cities over multiple years.

Each record represents a job-market snapshot, making the dataset suitable for trend analysis, aggregation, and machine-learning modeling.

## 🔹 Key Features

Record_Date	: Date of job-market observation

Company_Name :	Hiring company

Job_Role :	Role / designation

Experience_Level :	Required experience bracket

City :	Job location

Salary_INR :	Annual salary (INR)

Demand_Index	: Hiring demand score (0–100)

Remote_Option_Flag :	1 = Remote/Hybrid, 0 = On-site

Salary_Trend_Pct :	Monthly salary change

Experience_Years :	Engineered numeric experience

Role_Seniority :	Senior vs non-senior role
________________________________________

# 🎯 Objectives

•	Analyze company-wise and city-wise salary benchmarks

•	Study salary growth across experience levels

•	Understand demand vs hiring saturation

•	Compare remote vs on-site compensation

•	Identify seniority-driven salary differences

•	Build interactive dashboards for decision-making

•	Develop a machine-learning model for salary prediction
________________________________________

# 🔍 Exploratory Data Analysis (EDA)

The EDA phase includes:

•	Salary distribution analysis

•	Company-wise salary benchmarking

•	City-wise compensation comparison

•	Experience-based salary progression

•	Demand Index vs hiring saturation analysis

•	Remote vs on-site salary comparison

•	Time-series salary trend analysis

•	Correlation analysis between salary, demand, and experience
________________________________________

# 📊 Visualizations Used

•	KPI cards for high-level metrics

•	Bar charts for salary benchmarking

•	Line charts for experience progression and trends

•	Scatter plots for demand vs saturation analysis

•	Donut charts for remote vs on-site comparison

•	Stacked bars for hiring concentration
________________________________________

# 🛠 Feature Engineering

Key engineered features:

•	Numeric conversion of experience ranges

•	Role seniority classification

•	Label mapping for remote/on-site roles

•	Aggregation-ready metrics for BI and ML
________________________________________
# 🗄️ SQL Analysis (MySQL)

Key SQL tasks performed:

•	Database & table creation

•	Feature engineering using SQL

•	Indexing for query performance

•	Company-wise salary benchmarking

•	Role × experience salary analysis

•	Demand Index vs hiring saturation queries

•	Remote vs on-site salary comparison
________________________________________

# 📊 Power BI Dashboard

## Page 1 – Executive Overview
•	KPIs:

o	Total Jobs

o	Average Salary

o	Average Demand Index

o	Senior Role %

•	High-level salary, demand, and trend insights

•	Interactive slicers for city, company, remote type, role, and experience

## Page 2 – Role & Experience Deep Dive

•	Filter-aware KPIs

•	Salary progression by experience and role

•	Senior vs non-senior salary comparison

•	Demand vs salary positioning

•	Hiring concentration by experience
________________________________________

# 🤖 Modeling Approach

Model Used: Random Forest Regressor

## Why Random Forest?

•	Handles non-linear relationships

•	Robust to noisy real-world data

•	Performs well with mixed categorical and numeric features

## 📐 Train–Test Strategy

•	Train-test split with engineered features

•	One-hot encoding for categorical variables

•	Pipeline-based preprocessing
________________________________________

# 📏 Evaluation Metrics

•	R² Score – model explanatory power

•	MAE (Mean Absolute Error) – average salary error

•	Feature importance analysis
________________________________________

# 📈 Key Insights

•	Senior roles command significantly higher salaries

•	Salary growth is non-linear across experience levels

•	High demand does not always translate to higher pay due to saturation

•	Remote and on-site salaries are largely comparable

•	Certain companies consistently pay above market average
________________________________________

# 🚀 Possible Extensions

•	Advanced ML models (XGBoost, LightGBM)

•	Hyperparameter tuning

•	Geographic salary heatmaps

•	Automated data refresh pipelines

•	Deployment to Power BI Service
________________________________________

# ⚙️ Technologies Used

•	Python

•	Pandas, NumPy

•	Matplotlib, Seaborn

•	MySQL

•	Power BI

•	Scikit-learn














