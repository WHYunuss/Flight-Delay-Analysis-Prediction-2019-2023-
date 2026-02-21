# Flight Delay Analysis & Prediction (2019–2023)

## Overview

This project explores flight delays in U.S. domestic aviation between 2019 and 2023, using over 3 million flight records. The analysis identifies delay patterns across airlines, airports, routes, and seasons, and builds predictive models to estimate the likelihood of a flight being delayed.

The workflow reflects a professional data science approach — moving from large-scale data cleaning and exploratory analysis to machine learning modeling and interpretation — with the goal of turning raw aviation data into actionable intelligence for airlines, airports, and passengers.

---

## Project Context

The project was designed as a comprehensive deep dive into flight delays and their predictability.  

Rather than simply plotting raw delay counts, the analysis connects trends across multiple dimensions (airlines, routes, seasons) and transitions into predictive modeling using:

- Logistic Regression  
- Random Forest  
- XGBoost  

This combination of descriptive and predictive analysis provides both insights and practical forecasting capability.

---

## Key Aspects

- Cleaned and prepared a dataset of 3M flight records (2019–2023).  
- Conducted exploratory data analysis (EDA) on delay patterns by airline, airport, route, and month.  
- Built predictive models for flight delay likelihood.  
- Compared Random Forest and XGBoost feature importance to understand model behavior.  
- Created clear visualizations for both insights and model results.  

---

## What's Included

- **aviation.ipynb** – Full Jupyter Notebook with analysis, visualizations, and commentary.  
- **aviation.py** – Clean Python script version of the workflow.  
- **aviation_images/** – Exported plots (heatmaps, trend lines, feature importance charts).  
- **README.md** – Project overview and documentation.  

---

## Modeling Overview

Three machine learning models were implemented to predict delays:

- **Logistic Regression** – A simple, interpretable baseline model.  
- **Random Forest** – A tree-based model capturing nonlinear relationships, with departure time contributing ~44% importance.  
- **XGBoost** – A gradient boosting model distributing importance more evenly across airline, airport, and timing features.  

The comparison between Random Forest and XGBoost highlighted how different models interpret the data, offering richer insights into delay drivers.

---

## Metrics & Insights

### Descriptive Analysis
- Delay rates by airline and route.  
- Heatmap of delay-prone routes.  
- Monthly and hourly delay rates.  
- Airline-wise delay progression across 60 months (2019–2023).  

### Predictive Analysis
- Accuracy, precision, recall, and F1-score for each model.  
- Feature importance rankings.  
- Comparative model behavior (Random Forest vs. XGBoost).  

---

## Visualizations

- **Matplotlib bar charts** – Static comparisons (delay-prone airlines and routes).  
- **Seaborn heatmaps** – Route-level delay patterns.  
- **Plotly interactive line charts** – Airline-wise delay trends.  
- **Side-by-side feature importance plots** – Random Forest vs. XGBoost.  

---

## Repository Structure

