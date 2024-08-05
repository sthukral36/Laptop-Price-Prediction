# Laptop-Price-Prediction
## Laptop Price Prediction using Regression Algorithms

Project Ovrview- This machine learning project is associated  with predicting laptop prices using a dataset 
containing various laptop specifications. The goal was to build a predictive model
that accurately estimates laptop prices.
 The dataset includes information on laptops and their prices. The key features used for prediction are:

- Company: The brand of the laptop.
- TypeName: The type or category of the laptop (e.g., Gaming, Ultrabook).
- Ram: Amount of RAM in GB.
- Weight: Weight of the laptop.
-Touchscreen: Whether the laptop has a touchscreen (Yes/No).
- ppi: Pixels per inch (calculated from screen resolution and screen size).
- Cpu Brand: The brand of the CPU.
- HDD: Hard Disk Drive capacity in GB.
- SSD: Solid State Drive capacity in GB.
- Gpu brand: The brand of the GPU.
- os: Operating system.

## Data Preprocessing
Before training the models, the data underwent several preprocessing steps like filled missing data , converted categorical variables into numeric variables,
handling outliers ,made some meaningful insights from the data using barplots and histplot and removed some of the unwanted columns that were having useless values.

## Feature Engineering

Extracted and engineered features to enhance the model's predictive power. For example, calculated pixel density (ppi) from screen resolution and screen size.
Addressed columns with mixed values (like screen resolution, CPU, and GPU) by extracting more useful features. For instance:
Screen Resolution: Split the resolution into width and height components to compute pixel density.
CPU and GPU: Extracted brand and model information, categorizing them into different sub groups.

## Model Training
Implemented multiple regression algorithms, including Linear Regression, Random Forest Regressor, and Gradient Boosting Regressor, KNN, Ridge Regression etc to find out
best fit model for our data. 
The models were evaluated based on metrics such as:


## Mean Squared Error (MSE)
R-squared (R²)
Results
The Random Forest Regression model achieved the best performance with   R2 score 0.881926561554801
MAE 100 .
