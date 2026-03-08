
# Melbourne Housing Market Analysis & Price Prediction

This project explores the Melbourne housing market and tries to understand what factors influence property prices.  
It also uses machine learning models to predict housing prices based on different property features.

The project includes both **macro-level analysis** (housing market trends over time) and **micro-level analysis** (individual property features).

---

## Project Overview

In this project I:

- Analyzed housing price trends in Victoria
- Explored how prices changed during **Pre-COVID, COVID, and Post-COVID periods**
- Cleaned and prepared the Melbourne housing dataset
- Built multiple machine learning models to predict property prices
- Compared model performance
- Built a **Power BI dashboard** to visualize insights

---

## Data Used

Two datasets were used for this project:

- **ABS Dwelling Data** – used for macro housing market analysis  
- **Melbourne Housing Dataset** – used for property-level analysis and machine learning

---

## Macro Analysis

The macro analysis focuses on the overall housing market trend.

Things analyzed include:

- Average dwelling prices across years
- Price changes during **Pre-COVID, COVID, and Post-COVID periods**
- Quarterly price changes
- Housing price volatility

This helped understand how the housing market behaved over time.

---

## Micro Analysis

For the micro analysis, the Melbourne housing dataset was cleaned and prepared for modeling.

Steps included:

- Handling missing values
- Removing outliers
- Feature engineering
- Encoding categorical variables
- Preparing features for machine learning

---

## Machine Learning Models

Several models were tested to predict housing prices:

- Linear Regression
- Ridge Regression
- Decision Tree
- Random Forest
- XGBoost

Models were evaluated using:

- **R² Score**
- **MAE (Mean Absolute Error)**
- **RMSE**

Among all models, **XGBoost performed the best**.

---

## Key Insights

Some important findings from the analysis:

- Housing prices increased significantly from **Pre-COVID to Post-COVID**
- **Location-related features** strongly influence housing prices
- **Distance from CBD and property type** also affect prices
- Machine learning models can reasonably predict housing prices

---

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Power BI

---

## Project Structure

melbourne-housing-price-analysis

│  
├── melbourne_housing_analysis.ipynb  
├── README.md  

├── data/  
│   ├── ABS_dwelling_data.xlsx  
│   ├── Melbourne_housing_FULL.csv  

├── cleaned_data/  
│   ├── cleaned_housing_data.csv  
│   ├── macro_vic_clean.csv  

├── results/  
│   ├── model_results.csv  
│   ├── feature_importance.csv  

├── dashboard/  
│   └── melbourne_housing_dashboard.pbix  

---

## Dashboard

A Power BI dashboard was created to visualize:

- Housing price trends
- Macro housing market insights
- Machine learning model results
- Feature importance


