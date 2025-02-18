# Multiple Linear Regression for Vehicle Performance Prediction  

This repository contains a **Multiple Linear Regression** model for predicting **horsepower** and **torque** based on various vehicle attributes. It utilizes **data preprocessing, feature engineering, exploratory data analysis (EDA), and model evaluation techniques** to build accurate regression models.  

## Dataset  
The dataset (`cars.csv`) includes specifications such as:  
- **Engine Information** (Horsepower, Torque, Hybrid, Driveline, Transmission)  
- **Fuel Information** (City & Highway MPG, Fuel Type)  
- **Vehicle Dimensions** (Length, Width, Height)  
- **Identification Details** (Year, Make, Model)  

## Features & Processing  
- **Feature Engineering:**  
  - `Size_Factor` = Length × Width × Height  
  - `Vehicle_Age` = 2025 - Year  
  - `Power_Density` = Horsepower / Size_Factor  
  - `MPG_Combined` = (City MPG + Highway MPG) / 2  
  - One-hot encoding of categorical variables  

- **EDA & Visualization:**  
  - Distribution & box plots  
  - Scatter matrix for key numerical features  
  - Year-wise horsepower & torque trends  
  - Correlation heatmap  

- **Outlier Detection & Removal** using the **3-sigma rule**  
- **Variance Inflation Factor (VIF) analysis** to detect multicollinearity  

## Model Training  
- **Target Variables:**  
  - **Horsepower Prediction**  
  - **Torque Prediction**  
- **Feature Scaling:** **RobustScaler**  
- **Linear Regression Model**  
- **Performance Metrics:**  
  - **R² Score**  
  - **Root Mean Squared Error (RMSE)**  
  - **Cross-validation scores**  
- **Feature Importance Analysis**  

##  Results & Visualizations  
- **Actual vs. Predicted Scatter Plots**  
- **Residual Distribution Analysis**  
- **Top 10 Most Important Features for Predictions**  


---
