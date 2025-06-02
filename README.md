#  Used Toyota Car Price Prediction for Discount Motors in the UK

This project was developed as part of a data science case study for Discount Motors, a UK-based used car dealership. The goal is to help the sales team **automate the process of pricing used cars**, especially in preparation for the retirement of their most experienced pricing expert.

---

##  Project Overview

The business aim is to **accurately estimate the selling price of a car** using historical sales data. Accurate predictions will enable the dealership to list cars more efficiently and competitively.

Objectives:

- Predict the **price of a car within 10% accuracy**
- Outperform the current manual method, which has a 30% error margin
- Provide insights and a reliable pricing model for future listings

---

##  Data Description

The dataset contains the following fields:

| Column        | Description                                                      |
|---------------|------------------------------------------------------------------|
| `model`       | Car model (18 different values)                                  |
| `year`        | Year of registration (1998–2020)                                 |
| `price`       | Selling price in GBP                                             |
| `transmission`| Gearbox type: Manual, Automatic, Semi-Auto, Other                |
| `mileage`     | Total distance driven (miles)                                    |
| `fuelType`    | Fuel category: Petrol, Diesel, Hybrid, Other                     |
| `tax`         | Road tax in GBP (may depend on emissions or be fixed)           |
| `mpg`         | Miles per gallon                                                 |
| `engineSize`  | Size of the engine in liters                                     |

---

##  Methodology

## Data Validation & Cleaning
- Checked for missing values, inconsistencies
- Converted data types as necessary
- Handled outliers and performed sanity checks on numerical ranges

###  Exploratory Data Analysis (EDA)
- Visualized price distributions and car attributes
- Correlation matrix to identify influential predictors
- Bivariate analysis of price vs features

###  Modeling
- **Baseline model**: Linear Regression
- **Advanced model**: Random Forest Regressor
- Split data into training and test sets
- Evaluated using MAE, RMSE, and within-10%-error accuracy

###  Business Metric
- Proposed tracking % of predictions within 10% of actual sale price
- Benchmarked current model performance against 30% manual error rate

---

##  Key Findings

- Strong correlation between price and mileage, year, and engine size
- Transmission and fuel type showed moderate influence
- Random Forest outperformed baseline, achieving close to the 10% accuracy target

---




